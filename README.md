### Instrukcja dla mentora
Drogi mentorze, cały projekt, jak i wytyczne traktuj jako „wskazówki". 
Pamiętaj, że nadrzędnym celem na CodersCamp jest przekazać wiedzę i nauczyć :) 
Wszystko, co wg. Twojej najlepszej wiedzy, będzie służyć do osiągnięcia tego celu, możesz zastosować. 
Jednakże pamiętaj o trzymaniu się ogólnych wytycznych oceny i programu kursu (minimum musi zostać spełnione, abyśmy na koniec kursu mogli potwierdzić uczestnikom opanowanie umiejętności stosownym dokumentem).

Aby przygotować TEN projekt do wykonania przez zespół.
1. Sklonuj repozytorium.
1. Usuń instrukcję dla mentora z README.md
1. Opracujcie pomysł na projekt i wymagania. Lub użyjcie opisu poniżej jako inspirację. 
Aby odkryć, co chcecie wykonać, zastosujcie znane Wam metody. Jeśli czujecie się dobrze w EventStormingu to może być dobra droga.
1. Spotkaj się z zespołem, aby przeprowadzić planning i potworzyć Issues przynajmniej na pierwszy tydzień.
Wyznaczony Development Manager niech organizuje pracę dalej, ale dobrze jakbyś był na spotkaniach planujących zadania.

# CodersCamp 2020 - Projekt końcowy (FullStack — Node.js + React)
Coders Camp (coderscamp.edu.pl) - Projekt MonoKino FullStack. 

### Wprowadzenie
Gratulacje! 
Udało Wam się dotrzeć prawie do końca kursu. 
Posiadacie już wiele umiejętności, które są konieczne, aby rozpocząć karierę programisty.
W trakcie tego projektu powinniście dowieść, że jesteście gotowi wykonywać kompletne aplikacje webowe.
Wraz ze zbieraniem wymagań, dzieleniem pracy, zarządzaniem, całym procesem wytwórczym, testowaniem oraz wdrażaniem.

### Zasady wykonywania projektu (wspólne dla wszystkich grup i mentorów): 

##### W projekcie każdy z uczestników powinien zaprezentować praktyczną znajomość poniższych zagadnień związanych z Node.js i React:

Aplikacja musi korzystać z bazy danych (noSQL lub SQL) i zostać wykonana w architekturze Klient-Serwer (składać się co najmniej z 3 jednostek wdrożeniowych). 

Back-end zależy zaimplementować za pomocą frameworka Express.js lub NestJS (uczą się go backendowcy w ostatnim rozdziale).

Front-end wykonajcie przy użyciu biblioteki React. 
Jeśli czujecie się na siłach zastosujcie Redux do zarządzania stanem (frontendowcy pozanją go w ostatnim dziale).

**Node.js / Express**
- komunikacja klient - server
- logowanie standardowe - jsonWebToken
- endpointy
- routy
- rejestracja użytkownika
- bazy danych (NoSQL, SQL)
- MongoDB, mLab, RoboMongo

**React**
- Czym jest komponent
- functional component
- class component
- state
- props
- tworzenie list komponentów
- zarzadzanie stanem - redux
- JSX

Ponieważ projekt jest bardzo duży, będziecie na niego mieli 2 razy więcej czasu, niż poprzednio.
Sugerujemy w czasie działu 5 implementować część back-endową, a wczasie działu 6-tego część front-endową.
Wiedzę uzyskaną w dziale 6-tym możecie wykorzystać w projekcie, ale nie jest to koniecznie.
Ale to Wy odpowiadacie za powodzenie projektu, więc podejmujcie decyzje, korzystajcie z porad bardziej doświadczonych
i zróbcie coś niesamowitego!

##### W trakcie trwania projektu należy wyznaczyć w zespole następujące role
tak jak opisano w przypadku poprzedniego projektu.

##### Sposób oceny projektu (i wszystkich kolejnych projektów na CodersCamp)
tak jak opisano w przypadku poprzedniego projektu.


### Projekt końcowy — aplikacja webowa
Teraz przechodzimy do przykładowego projektu, który został przygotowany przez organizatorów kursu.
Proponowany projekt pozwala na zastosowania większości umiejętności, jakie powinniście posiąśc w trakcie przerabiania działu.
Jednakże jeśli macie pomysł na projekt podobnej skali, który spełni opisane na górze wymagania i czujecie się na siłach
w zdefiniowaniu funkcjonalności, przygotowaniu ekranów i podzieleniu go na zadania — to nic nie stoi na przeszkodzie,
aby wykonać np. coś związanego z zainteresowaniami Waszej grupy :)
**W tym przypadku zachęcamy jeszcze bardziej niż zazwyczaj, aby wykonać coś innego niż proponowane.
Ten projekt będzie swoistym zwieńczeniem i podsumowaniem wszystkiego co nauczyliście się w trakcie trwania CodersCamp.
Przykładowy projekt dajemy Wam głównie po to, abyście odczuli skalę, w której strone powinniście dążyć przy określaniu własnego pomysłu.**
Możecie też zaimplementować Kino, ale zupełnie inaczej (lepiej) niż tutaj jest zaproponowane. 
Niech wasza prezentacja zwali z nóg uczestników.
Pamiętajcie tylko, że czas jest ograniczony i musicie zdążyć z aplikacją do prezentacji. Powodzenia!

 
Czas porzucić narrację CodersCamp i wcielić się w członka zespołu projektowego, jeśli decydujecie się wykonać aplikację dla kina...

### MonoKino — Założenia projektowe
Gratulacje! 
Po ostatnim sukcesie Waszemu zespołowi udało się znaleźć pierwszego przedsiębiorcę, 
który będzie chciał z Waszą pomocą opracować całą aplikację webową.

Wasz klient jest właścicielem sieci kin o nazwie MonoKino.
MonoKino zaczynało w jednym mniejszym mieście, a teraz chcą wyjść na skalę ogólnopolską.
Obecna prowadzona jest rezerwacja jedynie przez email lub rozmowy telefoniczne, a opłaty za bilety są rozliczanie przy pomocy gotówki.

Ciągle zwiększanie się liczby placówek i klientów wymaga zautomatyzowania tych procesów.
Automatyzacja powinna zostać wykonana przy pomocy aplikacji webowej. Klient w niedalekiej przyszłości zapewne będzie chciał także wersję mobilną.
Może dobrze byłoby przygotować aplikację od razu na działanie na telefonach? Dacie radę zaproponować klientowi coś co spełni także to wymaganie?

Z analizy wynika, że największą konkurencją jest znana sieć kin, której stronę znajdziecie [TUTAJ](https://multikino.pl/repertuar/wroclaw-pasaz-grunwaldzki/teraz-gramy/alfabetyczny). 
Jak to często bywa, klient chce, aby jego strona była: „taka jak u konkurencji". 
Liczy się także czas „time to market”, dlatego na samym początku, trzeba się skupić, tylko na koniecznych do przynoszenia profitu funkcjonalnościach.

Aby sprostać oczekiwaniom klienta, zapoznajcie się z dokładniejszym opisem działania sieci kin.  


#### Filmy dla sieci MonoKino
Cała sieć MonoKino posiada w swojej ofercie wiele filmów. 
Te filmy powinny być zapisywane w bazie danych. 
Należy móc je DODAWAĆ / AKTUALIZOWAĆ / PRZEGLĄDAĆ i USUWAĆ. 
Usunięcie filmu powinno skutkować odwołaniem wszystkich zaplanowanych projekcji i wysłaniem do klientów wiadomości o zwrocie kosztów.

### Kina sieci MonoKino
Sieć ma zamiar posiadać Kina w różnych miastach na całym świecie. 
Dlatego konieczne jest, aby prowadzić ewidencję Kin sieci. 
Kino musi mieć swój numer identyfikacyjny oraz adres.

### Sale kinowe
Każde kino może mieć wiele sal kinowych. 
Każda sala kinowa ma określone ile rzędów po ile miejsc posiada (zakładamy model uproszczony - prostokąt).

### Seans filmowy
Seans Filmowy, to projekcja danego filmu odbywająca się o danej godzinie, w danej sali kinowej. 
Seans ma określoną: film, godzinę, salę.
Seanse nie mogą się na siebie nakładać. 
Należy też doliczyć czas 15 minut między seansami na sprzątanie. 
Każde kino otwarte jest w godzinach 6-22. 
Żaden film nie może się kończyć po zamknięciu, ani zaczynać nie wcześniej niż 15 minut po otwarciu.

### Repertuar
Repertuar jest planowany na każdy dzień. Zawiera seasne filmowe odbywające się w danym dniu w danym kinie. 


### Miejsce na sali
Miejsce na sali dotyczy danego seansu. 



### Prototyp interfejsu użytkownika

//TODO: Link do Figma

Niestety współpraca z grafikiem projektującym interfejs nie układała się najlepiej i jego praca nie została skończona.
Wasz zespół zobowiązał się do pokrycia wymaganych funkcjonalności, chociaż nie na wszystko znajdziecie projekty interfejsu.
Jeśli czegoś brakuje, możecie sami je dorobić na ekranach i/lub od razu implementować.

### Wymagania
Klient wraz z analitykiem biznesowym spisali podstawowe wymagania co do projektu.
Jednakże nie krępujcie się przed ich doprecyzowaniem / zmianami, czy też ulepszeniami.
To Wy jesteście profesjonalistami w swoim fachu i Klient ufa, że zrobicie wszystko jak najlepiej.
Wymagania podzielono na dwie sekcje. Aplikację dla widza, i panel administracyjny.

#### Aplikacja dla widza (repertuar, rezerwacja i zakup biletów)

1. Wyświetlanie NADCHODZĄCE FILMY (to filmy, które już zostały zaplanowane w repertuarze, ale nie prowadzi się jeszcze sprzedaży biletów).
2. Bilet można kupić maksymalnie na tydzień (7 * 24 godziny) przed planowanym seansem.

#### Panel Administracyjny (zarządzanie filmami, planowanie repertuaru, sale kinowe)

- [ ] CRUD dla filmów. Film musi zawierać: Tytuł, rok produkcji, opis fabuły, plakat, kategorie (może być kilka), czas trwania.
- [ ] CRUD dla kin.
- [ ] CRUD dla sal kinowych.
- [ ] Każda sala kinowa ma określone ile rzędów po ile miejsc posiada (zakładamy model uproszczony - prostokąt).
- [ ] Planowanie repertuaru na dany dzień (z wcześniej dodanym filmów). Repertuar zawiera wiele seansów. Seans ma określoną: film, godzinę, salę.
- [ ] 
- [ ] Tryb COVID dla sal - możliwe rezerwowanie miejsc jedynie jak na szachownicy.

1. UI wg. dostarczonego projektu.
2. Przygotowanie i wykonanie UI panelu administracyjnego.


#### Możliwości rozwoju - wymagania dodatkowe

- Integracja z systemem płatności - np. PayU (wykorzystać Sandbox, można bez podpinania konta - robić testowe płatności)
- Sprawdzanie biletów - generowanie kodu QR z zakupionym biletem. Bilet jest "sprawdzony" po zeskanowaniu kodu QR telefonem.
