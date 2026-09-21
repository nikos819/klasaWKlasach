Ten projekt to prosty program w języku C++, który służy do zarządzania danymi uczniów oraz klas przy użyciu programowania obiektowego (OOP).

## Główne funkcjonalności programu
Modelowanie obiektowe: Program definiuje dwie klasy: Osoba (reprezentująca pojedynczego ucznia) oraz Klasa (reprezentująca grupę uczniów wraz z wychowawcą).

Wprowadzanie danych: Użytkownik może wybrać, czy chce pobrać dane z pliku tekstowego (a.txt), czy wprowadzić je ręcznie z klawiatury.

Prezentacja danych: Program wyświetla na ekranie informacje o klasie, wychowawcy oraz liście uczniów.

## Opis struktur i metod
Klasa Osoba:

Pola: imie, nazwisko, nr (numer w dzienniku).

Metody: wczytaj_z_klawiatury() (pobiera dane z cin), wczytaj(ifstream &plik) (pobiera dane z pliku), wypisz() (wyświetla dane w konsoli).

Klasa Klasa:

Pola: nazwa (np. nazwa klasy szkolnej), wychowawca, tablica obiektów osoba[30] (przechowująca maksymalnie 30 uczniów).

Metody: Analogicznie jak w klasie Osoba, zarządzają danymi całej klasy oraz iterują po tablicy uczniów w zależności od podanej liczby ile.

Funkcja main:

Inicjalizuje zmienne (w tym liczbę uczniów ile = 2).

Pyta użytkownika o źródło danych (klawiatura lub plik a.txt).

Odpowiednio wywołuje metody wczytywania i wypisywania danych.

## Wymagany format pliku a.txt (dla opcji z pliku)
Aby program poprawnie wczytał dane z pliku, plik a.txt w katalogu projektu powinien zawierać dane w następującej kolejności:

Nazwa klasy (np. 3A)

Imię i nazwisko wychowawcy (np. Jan Kowalski)

Dane pierwszego ucznia: imie, nazwisko, numer (np. Anna Nowak 1)

Dane drugiego ucznia: imie, nazwisko, numer (np. Piotr Wiśniewski 2)
