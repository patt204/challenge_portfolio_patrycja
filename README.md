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

