# challenge_portfolio_pgutomska

# Spis Treści

1. [Task 1](#task-1)
* [Subtask 1. Wyciągmy karteczki](#subtask-1-wyciągamy-karteczki)
* [Subtask 3. O mnie](#subtask-3-o-mnie)
* [Subtask 4. Testy eksploracyjne](#subtask-4-testy-eksploracyjne)
* [Subtask 5. Jira dla chętnych](#subtask-5-jira-dla-chętnych)
2. [Task 2](#task-2)
* [Subtask 1. Pisanie przypadków testowych na podstawie User Story](#subtask-1-pisanie-przypadków-testowych-na-podstawie-user-story)
* [Subtask 2. Pisanie przypadków testowych na podstawie własnych doświadczeń - aplikacja webowa](#subtask-2-pisanie-przypadków-testowych-na-podstawie-własnych-doświadczeń---aplikacja-webowa)
* [Subtask 3. Po co piszemy test case’y?](#subtask-3-po-co-piszemy-test-casey)
* [Subtask 4. Pisanie przypadków testowych na podstawie własnych doświadczeń - aplikacja mobilna](#subtask-4-pisanie-przypadków-testowych-na-podstawie-własnych-doświadczeń---aplikacja-mobilna)
3. [Task 3](#task-3)
* [Subtask 1. Formatka do zgłaszania błędów](#subtask-1-formatka-do-zgłaszania-błędów)
* [Subtask 2. Testowanie według planów testów i raportowanie błędów](#subtask-2-testowanie-według-planów-testów-i-raportowanie-błędów)
* [Subtask 3. Raport](#subtask-3-raport)
4. [Task 4](#task-4)
* [Subtask 1. Formatka do zgłaszania błędów systemu](#subtask-1-formatka-do-zgłaszania-błędów-systemu)
* [Subtask 2. Testowanie eksploracyjne i raportowanie błędów](#subtask-2-testowanie-eksploracyjne-i-raportowanie-błędów)
* [Subtask 3. Do czego służy ta aplikacja?](#subtask-3-do-czego-s%C5%82u%C5%BCy-ta-aplikcja)
* [Subtask 4. Zgłaszanie błędów w Jirze](#subtask-4-zgłaszanie-błędów-w-jirze)
5. [Task 5](#task-5)
* [Subtask 1. Krótki kurs podstaw SQL](#subtask-1-krótki-kurs-podstaw-sql)
* [Subtask 3. Kilka zadań na rozgrzewkę](#subtask-3-kilka-zadań-na-rozgrzewkę)

# Task 1
 
## Subtask 1. Wyciągamy karteczki
  
5 punktów
  
## Subtask 3. O mnie
  
<p align="justify">
Cześć, nazywam się Patrycja. Do challengu dołączyłam, żeby dowiedzieć się czegoś o pracy jako Tester Manualny. Kurs znalazłam ostatniego dnia zapisów i stwierdziłam: raz kozie śmierć - wypełnilam formularz, zapłaciłam i tak oto jestem. Mam nadzieję, że dam radę przejść cały challenge i wynieść z tego coś dla siebie. Już jakiś czas szukam dla siebie ścieżki kariery. Do tej pory nie miałam nic wspólnego z IT, więc zdaję sobie sprawę, że lekko nie będzie :see_no_evil:, ale się nie poddaję.
</p>
 
## Subtask 4 Testy eksploracyjne

### Na czym polega aplikacja? Do czego służy?
Aplikacja służy do wprowadzania danych o piłkarzach, meczach i tworzenia raportów z nich. 

### Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmieniła?

Aplikacja posiada takie funkcjonalności jak: dodawanie gracza, edycja jego danych, tworzenie meczów i raportów i otrymanie statystyk z nich. Można też wydrukować listę graczy z podstawowymi danymi o nich, filtrować graczy po imieniu, nazwisku, wieku, pozycji, klubie i ocenie.

Dodałabym możliwość drukwania raportów i usuwania graczy

Zmieniłabym ikonkę zapisu meczu np. na dyskietkę, żeby było to bardziej oczywiste.

### Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?

Aplikacja jest prosta z wyglądu, ale nie porywa. Działa szybko.

### Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).

Na pewno łatwo wejść do formuarza dodawania gracza - wyświetla się to na głównej stronie.

Wpisywanie raportu nie jest intuicyjne, jak klikam ikonkę pogrubienia, itp. trzeba znów kliknąć w tekst, żeby kontynuować pisanie. 

Długo zajęło mi ogarnięcie, jak dodać statystyki do raportu.

### Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń!

* Weszłam w rozgrywanie meczu, wyszłam bez zapisywania i... Nie mogę wrócić do raportu 😿
![Błąd1](https://i.imgur.com/uHtH7GS.png)
* *Według mnie* powinna być sprawdzana poprawność daty urodzenia, wagi i wzrostu, ponieważ można wpisać datę urodzenia z przyszłości, a wagę i wzrost ujemny.
* Poprawiłabym okna do wpisania imienia i nazwiska, żeby nie można było wprowadzać cyfr i nieużywanych w nazwiskach znaków specjalnych.
* Link do youtuba w dodawaniu gracza może w ogóle nie być linkiem (zatwierdza obojętny ciąg znaków).
* Dodawanie wieku gracza: jak wpisze się za dużą liczbę w dniu miesiąca to zmienia ją automatycznie na 31, a potem wymaga zmienienia tego na poprawną datę.
* Hiperłącze do "dev team contact" przekierowuje do stworzenia Slacka.
* *Według mnie* jest błędne tłumaczenie zdania "rozpoznij mecz" na język angielski ("start report") i jest to mylące. 
* Nie wiem, czy to jest bład, ale na etapie dodawania gracza nie informuje, że trzeba wpisać województwo, a jest ono potrzebne, żeby otrzymać raport.
* W stronie dodawania gracza przycisk Clear nie działa praidłowo, usuwa tylko ostatnie zmiany.
* Na stronie głównej są literówki, tj. za~~a~~ktualizowany lub Aktywnosć.

### Subtask 5. Jira dla chętnych

Dołączyłam do zespołu w [Jirze](https://wannai.atlassian.net/jira/software/projects/DIT/boards/2).

# Task 2

## Subtask 1. Pisanie przypadków testowych na podstawie User Story

Napisane przeze mnie przypadki testowe na podstawie User Story dostępne są pod tym [linkiem](https://docs.google.com/document/d/1Nugy81i-qjqrOQDaUlxDpq8gY8DRlNZDSZEQa8Yp7YA/edit?usp=share_link).

## Subtask 2. Pisanie przypadków testowych na podstawie własnych doświadczeń - aplikacja webowa

Napisane przeze mnie przypadki testowe na podstawie własnych doświadczeń dostępne są pod tym [linkiem](https://docs.google.com/document/d/1YRDIOQvrbB-8L77hRTqiGg1yvgKjiYIGKWvk3LYt234/edit).

## Subtask 3. Po co piszemy test case’y?

*Według mnie* test case'y piszemy po to, by:
* było wiadomo jak test został zrobiony - dla nas i innych testerów
* móc sprawdzać oprogramowanie w trakcie testów regresji
* do oceny, czy oczekiwania klienta są spełnione

## Subtask 4. Pisanie przypadków testowych na podstawie własnych doświadczeń - aplikacja mobilna

Plik z napisanymi przeze mnie przypadkami testowymi dostępny pod tym [linkiem](https://docs.google.com/document/d/1hlEo65Lzn8OgfEHM1tB7eEXgob9C85AyI043NdviVSc/edit).

# Task 3

## Subtask 1. Formatka do zgłaszania błędów

Moja formatka dostępna jest pod [linkiem](https://docs.google.com/document/d/1BgqcYjhT6Az-61R7eg9hDAuFmnwa4Z3-LI_eeVeUUbI/edit).

## Subtask 2. Testowanie według planów testów i raportowanie błędów

Moje raporty błędów znajdują się [tutaj](https://docs.google.com/document/d/1EmkNx5qp1kCTks8WTv7mbIuncSpynDsv53T68aa-5_I), natomiast plany testów są opisane w [Tasku 2](#task-2) - Subtask 1 i Subtask 2

## Subtask 3. Raport

Mój raport z testów dostępny pod tym [adresem](https://docs.google.com/document/d/19ihWjwXELDIiIsyVEEKJ_eT4FaK2ZSFzIaj33SLo9h0).

# Task 4

## Subtask 1. Formatka do zgłaszania błędów systemu

Moja formatka do zgłaszania błędów aplikacji mobilnych znajduje się [tutaj](https://docs.google.com/document/d/1z1fhQujmnakAMaqOj5QjcLpryMzAyexnlqxYytM2weM).

## Subtask 2. Testowanie eksploracyjne i raportowanie błędów

Udało mi się znaleźć jeden błąd, oto moje [zgłoszenie](https://docs.google.com/document/d/14SAxmyREywUqruGBuJfxcgwt88sd567khHbz-pgoBCk) błędu. 

Zdarzyły się też rzeczy, które były nie do zreprodukowania:

* Raz, gdy kliknęłam "Zobacz więcej" pod Prawammi konsumenta to ten napis nie zniknął, jak na obrazku poniżej.

<img src="/images/Screenshot_OLXpl.jpg" alt="screenshot of olx page" width="30%"
height="30%" title="screenshot">

* Po przeglądaniu strony "Szukaj" z wybranymi dla mnie pozycjami miałam wrażenie, że nie klikane przeze mnie produkty pokazywały się potem w "Ostatnio oglądanych ogłoszeniach"

## Subtask 3. Do czego służy ta aplikcja?

*Według mnie* aplikacja OLX służy do:

 * Sprzedawania i kupowania rzeczy, mieszkań i wynajmowania ich
 
 * Szukania pracy

Użytkownikiem końcowym są osoby prywatne i firmy, które chcą coś wystawić na sprzedaż, albo kupić. Może to być też osoba, która poszukuje pracy.

Aplikacja jest czytelna, łatwo dodać nową ofertę przyciskiem na dole ekranu. Wszystko jest wyraźnie oznaczone. Można też wybrać, jakie powiadomienia chcemy dostawać. Jednak nie przypominam sobie, by aplikacja prowadziła mnie po kolei, np. jak dodać nowe ogłoszenie, albo jak coś wyszukać. Klikając w "Pomoc" użytkownik jest przekierowany do strony "Centrum pomocy", które to jest tylko pytaniami i odpowiedziami - nie widzę kontaktu z infolinią, czy czatu. Nie ma też weryfikacji dwuskładnikowej.

Dodałabym opcję kontaktu z supportem - mailowy, telefoniczny, czy poprzez czat. Dodałabym też weryfikację dwuskładnikową do logowania, żeby preciwdziałać oszustwom. Na ten moment weryfikuje się tylko numer telefonu sprzedającego.

Testowanie aplikacji internetowej i natywnej zdecydowanie ma swoje różnice, m. in. w natywnej nie ma takich narzędzi, jak DevToolsy. Aplikację natywną trzeba też zainstalować, internetowej nie. Istnieje też różnica w rozdzielczości, przez co aplikacje mobilne trudniej zrobić czytelnymi. Natywne aplikacje też trudniej zobić dostępne dla wszystkich (np. ustawienie większej czcionki w telefonie dla osób słabowidzących powoduje czasem brak możliwości używania danej aplikacji).

## Subtask 4. Zgłaszanie błędów w Jirze

Zadanie było robione grupowo, moje zgłoszenia w aplikacji Jira dotępne są pod [linkiem](https://wannai.atlassian.net/jira/software/projects/DIT/boards/2) oraz na githubie w [folderze](https://github.com/pgutomska/challenge_portfolio_pgutomska/tree/main/Jira).

# Task 5

## Subtask 1. Krótki kurs podstaw SQL

Poniżej wymieniam poznane zapytania oraz operatoy z kursu ["Szkolenie SQL w 120 minut](https://www.kursysql.pl/szkolenie-sql-w-120-minut/).

**Zapytania:**

* SELECT 
* FROM 
* ORDER BY (DESC) 
* WHERE 

**Oparatory:**

* \=
* \>
* \<
* \<> lub \!=
* BETWEEN
* LIKE
* AND
* OR
* IS NULL
* IS NOT NULL
* IN

## Subtask 3. Kilka zadań na rozgrzewkę

#### 1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

SELECT * FROM actors

ORDER BY surname

![z01](https://user-images.githubusercontent.com/122393705/218308196-81f72d00-ad0f-49af-a451-57434152f7fb.png)

#### 2. Wyświetl film, który powstał w 2019 roku

SELECT * FROM movies

WHERE year_of_production = 2019

![z02](https://user-images.githubusercontent.com/122393705/218308211-4c01d970-3cdd-4f4f-8e04-b1e334061b40.png)

#### 3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

SELECT * FROM movies

WHERE year_of_production >= 1900 AND <= 1999

![z03](https://user-images.githubusercontent.com/122393705/218308221-bb3a0983-6280-4348-b6ab-de79e0f624da.png)

#### 4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$

SELECT title, price

FROM movies

WHERE price < 7

![z04](https://user-images.githubusercontent.com/122393705/218308226-559033a5-6f06-4fc5-9d2c-7b011fe44c3b.png)

#### 5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

SELECT * FROM actors

WHERE actor_id >=  4 AND actor_id <= 7

ORDER BY actor_id

![z05](https://user-images.githubusercontent.com/122393705/218308231-e96f861c-9015-46fc-ba92-08dd695db20e.png)

#### 6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

SELECT * FROM customers

WHERE customer_id =2 OR customer_id = 4 OR customer_id = 6

ORDER BY customer_id

![z06](https://user-images.githubusercontent.com/122393705/218308235-a8d7abf6-1f92-4819-aa43-31c44c13fda2.png)

#### 7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

SELECT * FROM customers

WHERE customer_id IN (1,3,5)

![z07](https://user-images.githubusercontent.com/122393705/218308237-44074615-4c0f-4865-8f36-4871ea08be6b.png)

#### 8. Wyświetl dane wszystkich osób z tabeli 'actors', których imię zaczyna się od ciągu "An".

SELECT * FROM actors 

WHERE name LIKE 'An%'

ORDER BY name

![z08](https://user-images.githubusercontent.com/122393705/218308243-a01267b1-ebf0-43f4-9e72-ddc808eb472e.png)

#### 9. Wyświetl dane klienta, który nie ma podanego adresu email.

SELECT * FROM customers

WHERE email IS NULL

![z09](https://user-images.githubusercontent.com/122393705/218308251-97269814-bb27-460d-b125-941d4eec103f.png)

#### 10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

SELECT * FROM movies

WHERE price > 9 AND movie_id >= 2 AND movie_id <= 8

![z10](https://user-images.githubusercontent.com/122393705/218308254-39f55910-4e38-4b0d-b4a3-6a91e8e0f665.png)
