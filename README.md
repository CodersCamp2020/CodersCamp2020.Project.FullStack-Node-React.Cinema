# CodersCamp - Edycja VI (2020)

## Projekt końcowy - MonoKino

### Wprowadzenie
Gratulacje! Waszemu zespołowi udało się znaleźć pierwszego klienta, który będzie chciał z Waszą pomocą opracować aplikację webową.
MonoKino to sieć kin, która zaczyna funkcjonować w wielu miastach w Polsce. 
Ich największą konkurencją jest jedno ze znanych kin, którego stronę znajdziecie [TUTAJ](https://multikino.pl/repertuar/wroclaw-pasaz-grunwaldzki/teraz-gramy/alfabetyczny). Jak to często bywa, klient chce, aby jego strona była: "taka jak u konkurencji". Liczy się także czas "time to market" dlatego na samym początku trzeba się skupić tylko na koniecznych do działania funkcjonalnościach.  


### Opis wycinka rzeczywistości (domeny problemu)

Naszy klient - sieć kin MonoKino obecnie prowadzi wszystkie rezerwacje poprzez email lub rozmowy telefoniczne. Każda rezerwacja jest zapisywana u osoby, która rezerwuje. Następnie bilety są kupowane wg. wcześniej zapisywanych rezerwacji. Klient rozszerza swoją działaność na wiele miast, dlatego chciałby zautomatyzować proces rezerwacji i zakupów biletów. 

CEL: Implementacja aplikacji, która zautomatyzuje proces sprzedaży biletów. To powinna być aplikacja webowa, ale klient w niedalekiej przyszłości zapewne będzie chciał także wersje mobilną. A może zaproponujecie klientowi coś co spełni od razu oba wymagania?


#### Filmy dla sieci MonoKino
Cała sieć MonoKino posiada w swojej ofercie wiele filmów. Te filmy powinny być zapisywane w bazie danych. Należy móc je DODAWAĆ / AKTUALIZOWAĆ / PRZEGLĄDAĆ i USUWAĆ. Usunięcie filmu powinno skutkować odwołaniem wszystkich zaplanowanych projekcji i wysłaniem do klientów wiadomości o zwrocie kosztów.

### Kina sieci MonoKino
Sieć ma zamiar posiadać Kina w różnych miastach na całym świecie. Dlatego konieczne jest, aby prowadzić ewidencję Kin sieci. Kino musi mieć swój numer identyfikacyjny oraz adres.

### Sale kinowe
Każde kino może mieć wiele sal kinowych. Każda sala kinowa ma określone ile rzędów po ile miejsc posiada (zakładamy model uproszczony - prostokąt).

### Seans filmowy
Seans Filmowy, to projekcja danego filmu odbywająca się o danej godzinie, w danej sali kinowej. Seans ma określoną: film, godzinę, salę.
Seanse nie mogą się na siebie nakładać. Należy też doliczyć czas 15 minut między seansami na sprzątanie. 
Każde kino otwarte jest w godzinach 6-22. Żaden film nie może się kończyć po zamknięciu, ani zaczynać nie wcześniej niż 15 minut po otwarciu.

### Repertuar
Repertuar jest planowany na każdy dzień. Zawiera seasne filmowe odbywające się w danym dniu w danym kinie. 


### Miejsce na sali
Miejsce na sali dotyczy danego seansu. 



### Prototyp interfejsu użytkownika

//TODO: Link do Figma

Niestety współpraca z grafikiem projektującym interfejs nie układała się najlepiej i jego praca nie została skończona.
Wasz zespoł zobowiązał się do pokrycia wymaganych funkcjonalnośći, chociaż nie na wszystko znajdziecie projekty.
Jeśli czegoś brakuje możecie sami je dorobić i/lub od razu implementować.

### Wymagania

#### Rezerwacja i zakup biletów

1. Wyświetlanie NADCHODZĄCE FILMY (to filmy, które już zostały zaplanowane w repertuarze, ale nie prowadzi się jeszcze sprzedaży biletów).
2. Bilet można kupić maksymalnie na tydzień (7 * 24 godziny) przed planowanym seansem.

#### Panel Administracyjny

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
