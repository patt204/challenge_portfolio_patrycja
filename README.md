# "Zostań Testerem Manualnym" - 7-weeks course organized by DareIT (https://www.dareit.io/). 
The scope of the course: 
* Exploratory tests, 
* Test cases, 
* Error reporting, 
* Mobile application testing.

# TASK 1

## Subtask 1

8 punktów na 10

## Subtask 3 

### Dlaczego zdecydował_ś się na udział w challenge portfolio?
Zdecydowałam się aby wziąć udział w tym challenge'u, ponieważ chciałabym zapoznać się z tematyką testowania. Mam nadzieję znaleźć pierwszą pracę w IT i być może będzie to obszar, który będzie tym jedynym. Jestem zmotywowana tym, że w tym wyzwaniu będzie wiele praktycznych zadań, które poprzez robienie ich pomogą mi zdobyć doświadczenie i poszerzyć portfolio w CV, które jest tak bardzo potrzebne do znalezienia pracy w IT.

## Subtask 4

### Na czym polega ta aplikacja? Do czego służy?

Aplikacja ScountsPanel służy do katalogowania informacji o zawodnikach piłki nożnej, zbierania ich statystyk z rozegranych spotkań oraz pozwala na przeszukiwanie danych.

### Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a?

* Wyświetlanie strony w języku polskim lub angielskim
* Logowanie użytkowników
* Zarządzanie wpisami w katalogu zawodników
  * dodawanie nowego profilu zawodnika do katalogu
  * edytowanie już istniejącego profilu zawodnika
  * usuwanie już istniejącego profilu zawodnika
  * przeszukiwanie katalogu przy pomocy filtrów
  * pobranie całego katalogu do pliku csv
  * wydrukowanie całego katalogu
* Dodawanie rozegranych meczów do profilu zawodnika
* Tworzenie dla profilu zawodnika raportów meczowych "na żywo" 
    * dodawanie informacji o zdarzeniach boiskowych dotyczących zawodnika, wraz ze wskazaniem miejsca zdarzenia na boisku
    * licznik rozegranych połów meczu
    * licznik czasu meczu / czasu zawodnika na boisku (nie doprecyzowano)
    * możliwość cofnięcia ostatniego dodanego zdarzenia
    * możliwość wykasowania wszystkich wprowadzonych informacji
* Tworzenie dla profilu zawodnika raportów meczowych "po meczu"
    * dodanie oceny opisowej w trzech kategoriach
      * Inteligencja boiskowa
      * Mentalność
      * Podsumowanie
    * Wybranie końcowej oceny występu zawodnika, w skali 1-5 
    * pobranie informacji z raportu tworzonego "na żywo", oraz ich prezentacja na wykresach wraz ze statystykami
      * możliwość dodania komentarzy przy poszczególnych statystykach
      * możliwość dodania własnych notatek na temat zagrań/zdarzeń niekonwencjonalnych, nieujętych w statystykach.

### Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?

Aplikacja wygląda dobrze, natomiast uważam, że można by popracować nad jej wizualnym aspektem, ponieważ wygląda dość prosto.

### Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu). 

Pojawiają się pewne elementy, które są niezbyt intuicyjne i na pierwszy rzut oka umieściłabym je na liście "do ulepszenia". 
Sa to np.:
 * Na stronie głównej zabrakło mi wyszukiwarki zawodników
 * Brak responsywności Logo ScoutPanel
 * Po kliknięciu w profil zawodnika powinniśmy otwierać profil zawodnika z informacjami i 3 opcjami  w lewym menu: edycja profilu, mecze, raporty. Natomiast kliknięcie w profil zawodnika, przenosi nas od razu do edycji jego danych

### Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)

Tak zauważyłam błędy w sekcji Dodawanie/Edycja danych zawodnika:
  *  Formularz akceptuje zbyt wiele znaków w poszczególnych polach, powodując późniejsze problemy z wyświetlaniem. 
  *  Formularz akceptuje ujemny i zbyt wysoki wzrost oraz ujemną wagę (przy wadze również brak informacji o jednostce)
  *  Formularz akceptuje przyszłą datę urodzenia, oraz zbyt odległe daty urodzenia z przeszłości
  *  Formularz akceptuje niepoprawne linki
  
# TASK 2

## Subtask 1 - Pisanie przypadków testowych na podstawie User Story.

  * Link do folderu na dysku: https://drive.google.com/drive/u/0/folders/1CwSIM1bH1gYjMafQJfCCrvNTOJXZ55c1
  * Bezpośredni link do pliku: https://docs.google.com/spreadsheets/d/1W2ljHweillQ2y2ijniIaCDaWBj7WO0SBsj6qa5o1cQ0/edit#gid=0

## Subtask 2 - Pisanie przypadków testowych na podstawie “własnych doświadczeń".

  * Link do folderu na dysku: https://drive.google.com/drive/u/0/folders/1CwSIM1bH1gYjMafQJfCCrvNTOJXZ55c1
  * Bezpośredni link do pliku: https://docs.google.com/spreadsheets/d/1WevHtE3Q_qSD1ozrcVm9zbQMIpP_ne9Ay0cYApuUqqA/edit#gid=0

## Subtask 3 - Po co piszemy test case’y?

Przypadki testowe piszemy, aby udokumentować w przejrzysty sposób różne możliwości obsłużenia modułów w ramach danej aplikacji. Dobre pokrycie przypadkami testowymi oprogramowania daje nam pewność podczas testów, że nie pominęliśmy żadnej ważnej funkcjonalności. Po zakończeniu testów, na podstawie przypadków testowych możemy budować nasze raporty z wykonanych testów. 

# TASK 3

## Subtask 3 - Raport z wykonanych testów
  
  * Link do folderu na dysku: https://drive.google.com/drive/u/0/folders/1kKj5Jg0lR5Rf8NZOv2dzTFuQTll0wD7q

# TASK 4

## Subtask 2 - Testowanie eksploracyjne i raportowanie błędów
  
  * Link do folderu na dysku: https://drive.google.com/drive/u/0/folders/1i_w9w6Mjixeui0Ol84I0NOQWcpDKIQCz

## Subtask 3 - Do czego służy ta aplikacja?

Aplikacja mobilna OLX
1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji? - Głównym celem aplikacji jest łączenie małych firm lub prywatnych sprzedawców z kupującymi, ale również jest tablicą ogłoszeń, dużą rolę odgrywają ogłoszenia o pracę i usługi reklamowe. 
3. Kto ma być użytkownikiem końcowym aplikacji? - Przy tak szerokim zakresie zastosowań istnieje wiele różnych typów użytkowników końcowych, aplikacja jest przeznaczona głównie dla przeciętnych użytkowników, dlatego musi być prosta w obsłudze.
4. Czy według Ciebie aplikacja jest user friendly? - Uważam, że aplikacja jest przyjazna dla użytkownika. Większość funkcji jest intuicyjna i prosta w obłudze.
5. Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność? - Przesuwając palcem w lewo po galerii zdjęć oferty, użytkownik dociera do końca galerii i ponownie przesuwa w lewo, otwiera się inna oferta (np. następna z wyników wyszukiwania). O ile przeglądanie ofert jest wygodne, o tyle szybkie przeglądanie galerii w celu znalezienia konkretnego zdjęcia, a przypadkowe przełączenie się na inną ofertę może być irytujące dla użytkownika.
6. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej? - Z punktu widzenia telefonu z systemem Android wygląda tp bardzo podobnie. Jedyne różnice jakie dostrzegam to że w aplikacji natywnej przy logowaniu się otwiera się dodatkowe okno w aplikacji, które łączy się z przeglądarką w celu zalogowania i weryfikacji danych. Przy aplikacji internetowej dzieje się to bezpośrednio.

# TASK 5

## Subtask 3 - Poniżej znajduje się kilka zadań związanych z SQLem. Chciałabym, żebyś w pliku readme file wypisał_a/ wkleił_a treść zadania, a poniżej wpisał_a zapytanie jakie użyłe_aś, aby uzyskać odpowiedź. Pod zapytaniem wklej prt screena z wynikiem zapytania

1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
SELECT * FROM actors ORDER BY surname ASC

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/c7dcde83-b146-4fae-9136-e5b2185bc6ee)

2. Wyświetl film, który powstał w 2019 roku.
SELECT * FROM movies WHERE year_of_production = '2019'

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/8fdd1048-947f-4c20-9558-e779d8e94404)

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.
SELECT * FROM movies WHERE year_of_production BETWEEN '1900' AND '1999'

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/0c051429-b6a5-4971-ab31-1cce0c59aec9)

4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$
SELECT title, price FROM movies WHERE price< '7$'

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/3945c468-3890-4f67-ae68-3599b58bee2b)

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
SELECT * FROM actors WHERE actor_id >= '4' AND actor_id <= '7'

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/934dcfc1-a3c1-4815-8d3d-2bfd823ecaad)

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.
SELECT * FROM customers WHERE customer_id = '2' OR customer_id = '4' OR customer_id = '6'

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/89222634-1075-4b3c-a80a-4adbc7ceb225)

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.
SELECT * FROM customers WHERE customer_id IN ( 1, 3, 5)

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/f2193390-4b6b-47a2-a5de-68f585e641d8)

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
SELECT * FROM actors WHERE name LIKE 'An%'

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/456d1787-2ce1-41e6-a1ba-1247fe1d603b)

9. Wyświetl dane klienta, który nie ma podanego adresu email.
SELECT * FROM customers WHERE email IS NULL

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/d00fd688-5779-43b2-836c-38d928d98699)

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.
SELECT * FROM movies WHERE price > 9 AND movie_id BETWEEN 2 AND 8

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/6b584661-2885-412b-9cba-84a4236b3f15)

# TASK 6

## Subtask 1 - Krótki kurs podstaw SQL

11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd.
UPDATE customers SET surname = 'Miler' WHERE customer_id = 3

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/5f897807-525c-4df7-9f96-ef3b3a1852c4)

12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.
SELECT * FROM sale JOIN customers ON customers.customer_id WHERE movie_id = 4

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/9363825e-b82b-49fb-922c-f5c0fc7059a1)

13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com
UPDATE customers SET email = 'pati@mail.com' WHERE customer_id = 4

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/a2d796ba-49d2-442b-ac86-a9faff039404)

14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).

SELECT sale_date, name, surname, title FROM sale INNER JOIN customers ON sale.customer_id = customers.customer_id INNER JOIN movies ON movies.movie_id = sale.movie_id

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/3e4a169a-2739-4361-a6d4-bc0d788d774b)

15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag
ALTER TABLE customers ADD pseudonym char (3) not null

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/4cdd743c-3a79-4fbe-b831-bc2185a82a21)

16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.
SELECT DISTINCT title FROM sale INNER JOIN movies ON sale.movie_id = movies.movie_id

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/8f0de880-6909-4d0d-9ef3-d140f420d4c0)

17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)
SELECT name FROM actors UNION SELECT name FROM customers ORDER BY name ASC

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/d71305d1-5e3e-49fe-86db-d889d4fc6ebb)

18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).
UPDATE movies SET price = price + 2.5;

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/c1f3a0ad-020d-421a-91ea-6f36e9550c95)

19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał
SELECT name, surname,title FROM actors INNER JOIN movies WHERE actor_id = 4

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/a7e2e518-d7aa-486c-a2b8-3f6917191912)

20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa
INSERT INTO customers VALUES (7, 'Honia', ' Stuczka-Kucharska', ' honia@mail.com', 'Hoa')

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/9ba37f33-ee73-485c-9dfa-f9ff327240d0)

## Subtask 2 - Test

![image](https://github.com/patt204/challenge_portfolio_patrycja/assets/60150219/15a034cd-3057-45b0-9de3-0b1b5c89e7fd)

## Subtask 3 - Tworzymy portfolio

https://github.com/patt204/Portfolio
