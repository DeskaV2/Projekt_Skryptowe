# Lokalna Sieć Wymiany Książek

## Cel projektu
Aplikacja umożliwia tworzenie lokalnej społeczności wymiany książek między użytkownikami. Główne funkcjonalności:
- Rejestracja użytkowników
- Dodawanie książek do biblioteki
- Wyszukiwanie książek i użytkowników
- Wymiana książek między użytkownikami
- Statystyki i wizualizacja kolekcji

## Autorzy
- Krzysztof Giemza 2ID12A
- Kacper Grabalski 2ID12A

## Wymagania systemowe
- Python 3.8+
- Biblioteki: `matplotlib`, `memory_profiler` (do testów)

## Instalacja
#Uruchomienie Aplikacji:
Pobranie .rar z repozytorium. Wypakowanie zawartości pliku do wybranego przez siebie folderu. Uruchomienie pliku .exe
Uwaga!
Program został podzielony na dwa pliki .rar i żeby aplikacja działała poprawnie należy pobrać oba pliki!
nazwa pliku:Jezyki_Skryptowe_Proj_2ID12A_Kacper_Grabalski_Krzysztof_Giemza_Aplikacja.part1 oraz Jezyki_Skryptowe_Proj_2ID12A_Kacper_Grabalski_Krzysztof_Giemza_Aplikacja.part2

#Uruchomienie Kodu:
Pobranie .rar z repozytorium. Wypakowanie zawartości pliku do wybranego przez siebie folderu. Uruchomienie kompilatora z pythonem (np. PyCharm).
nazwa pliku:
Jezyki_Skryptowe_Proj_2ID12A_Kacper_Grabalski_Krzysztof_Giemza

#Struktura projektu
.
├── main.py              # Główny punkt wejścia
├── storage.py           # Obsługa danych (JSON)
├── user_interface.py    # Interfejs użytkownika
├── user.py              # Model użytkownika
├── book.py              # Model książki
├── utils.py             # Funkcje pomocnicze
├── visualization.py     # Generowanie wykresów
├── test_unit.py        # Testy jednostkowe
├── test_fun.py   # Testy funkcjonalne
├── test_integ.py  # Testy integracyjne
├── test_gran.py     # Testy graniczne
├── test_wyda.py  # Testy wydajności
├── test_pam.py       # Testy pamięci
├── test_jak.py       # Testy jakości
└── library_data.json    # Baza danych (automatycznie tworzona)

#Przykładowe użycie
1. Dodaj użytkownika:
Wybierz opcję: 1
Imię i nazwisko: Jan Kowalski
Utworzono użytkownika: Jan Kowalski (ID: 1)

2. Dodaj książkę:
Wybierz opcję: 2
ID właściciela: 1
Tytuł: Władca Pierścieni
Autor: J.R.R. Tolkien
Gatunek: Fantasy
Dodano książkę: Władca Pierścieni (ID: 101)

3. Wyszukaj książki:
Wybierz opcję: 3
Szukaj (tytuł/autor/gatunek): tolkien

Znalezione książki:
Władca Pierścieni - J.R.R. Tolkien (Fantasy)

4. Wymień książkę:
Wybierz opcję: 4
Podaj ID użytkownika A: 1
Podaj ID książki do oddania: 101
Podaj ID użytkownika B: 2
Podaj ID książki do otrzymania: 201
Wymiana zakończona sukcesem!
