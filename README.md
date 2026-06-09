# Guesthouse AI Scheduler – Sierpień

## Opis projektu

Guesthouse AI Scheduler to aplikacja wspierająca tworzenie miesięcznego grafiku pracy dla pensjonatu w sierpniu, czyli w okresie największego obłożenia obiektu.

System wykorzystuje dane o dostępności pracowników, urlopach, kompetencjach oraz podstawowych zasadach prawa pracy, aby wygenerować przejrzysty i możliwie optymalny harmonogram.

## Cel aplikacji

Celem aplikacji jest usprawnienie pracy managera pensjonatu poprzez automatyzację procesu tworzenia grafiku na jeden miesiąc – sierpień.

Aplikacja pomaga ograniczyć błędy ręcznego planowania, zmniejszyć ryzyko przeciążenia pracowników oraz lepiej dopasować obsadę do potrzeb obiektu.

## Główne funkcjonalności

- tworzenie grafiku pracy na sierpień,
- uwzględnianie dostępności pracowników,
- uwzględnianie urlopów i nieobecności,
- przypisywanie pracowników zgodnie z ich kompetencjami,
- kontrola liczby godzin pracy,
- ograniczanie nadgodzin,
- analiza obciążenia pracowników,
- wsparcie managera w planowaniu zmian.

## Technologie

Zastosowane technologie
Frontend (Aplikacja użytkownika)
Google AppSheet
Platforma No-Code
Progressive Web Application (PWA)

Aplikacja użytkownika została zbudowana w Google AppSheet, które umożliwia tworzenie aplikacji biznesowych bez konieczności programowania interfejsu użytkownika.

Baza danych
Google Sheets

Arkusze Google pełnią rolę relacyjnej chmurowej bazy danych przechowującej informacje o pracownikach, grafikach oraz wnioskach urlopowych.

Backend
Python 3
Google Colab

Logika biznesowa systemu została zaimplementowana w języku Python i uruchamiana w środowisku Google Colab.

Wykorzystane biblioteki Python
pandas – przetwarzanie i analiza danych,
gspread – komunikacja z arkuszami Google Sheets,
google-auth – autoryzacja i bezpieczny dostęp do usług Google.
Architektura systemu

Frontend (AppSheet) → Google Sheets → Python (Google Colab)

Użytkownik składa wniosek urlopowy w aplikacji AppSheet. Dane trafiają do arkuszy Google Sheets, które stanowią centralną bazę danych systemu. Następnie aplikacja Python analizuje wniosek zgodnie z regułami biznesowymi i automatycznie aktualizuje status oraz grafik pracy.
## Autorzy

- Anna Bonder
- Aleksandra Grinholc
- Jakub Zabudź

## Zrzuty ekranu

## Zrzuty ekranu aplikacji

### Zapotrzebowanie zmianowe

Widok przedstawiający wymagania dotyczące obsady poszczególnych zmian w sierpniu.

![Zapotrzebowanie zmianowe](Zapotrzebowanie%20zmianowe.PNG)

### Lista pracowników

Baza pracowników wykorzystywana podczas planowania harmonogramu pracy.

![Lista pracowników](Lista%20pracowników.PNG)

### Wnioski urlopowe – Formularz

Formularz umożliwiający pracownikom składanie wniosków urlopowych.

![Wnioski urlopowe Form](Wnioski%20urlopowe%20form.PNG)

### Aktualne wnioski urlopowe

Widok wszystkich złożonych wniosków urlopowych uwzględnianych podczas planowania grafiku.

![Aktualne wnioski urlopowe](Aktualne%20wnioski%20urlopowe.PNG)

### Zgłoszenie urlopu

Przykład procesu zgłaszania urlopu przez pracownika.

![Zgłoszenie urlopu](Zgłoszenie%20urlopu.PNG)


## Podsumowanie

Projekt pokazuje, w jaki sposób sztuczna inteligencja i algorytmy optymalizacyjne mogą wspierać zarządzanie personelem w pensjonacie w okresie wysokiego sezonu.
