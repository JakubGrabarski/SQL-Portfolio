# SQL-Portfolio

# SQL Portfolio – Analiza Danych

## Opis projektu
W tym projekcie przeprowadziłem analizę danych sprzedażowych firmy, wykorzystując SQL do zapytań analitycznych. Dane dotyczą klientów, zamówień, produktów oraz płatności, co pozwala na lepsze zrozumienie wyników sprzedażowych i zaangażowania klientów.

## Struktura bazy danych
Baza danych składa się z następujących tabel:
- **Customers** – dane klientów
- **Employees** – informacje o pracownikach
- **Offices** – lokalizacje biur sprzedaży
- **Orders** – informacje o zamówieniach
- **OrderDetails** – szczegóły zamówień
- **Payments** – historia płatności klientów
- **Products** – szczegóły produktów
- **ProductLines** – kategorie produktów

## Analiza i zapytania SQL

### 1. Podstawowe informacje o tabelach
Zapytanie SQL zwracające liczbę kolumn i rekordów w każdej tabeli bazy danych.

### 2. Jakie produkty powinny być zamawiane częściej lub rzadziej?
Analiza stanów magazynowych produktów i ich sprzedaży. Zapytanie pozwala określić, które produkty są najczęściej zamawiane i wymagają częstszego uzupełniania.

### 3. Identyfikacja najlepszych klientów (VIP)
Obliczenie sumarycznego zysku generowanego przez każdego klienta. Wynikiem jest lista 5 klientów, którzy przynoszą firmie największe przychody.

### 4. Znalezienie najmniej zaangażowanych klientów
Podobnie jak w przypadku VIP klientów, analizujemy sumaryczny zysk na klienta, ale tym razem skupiamy się na tych, którzy przynoszą firmie najmniejsze dochody.

### 5. Średnia wartość życiowa klienta (Customer Lifetime Value – LTV)
Obliczenie średniego LTV dla wszystkich klientów – pozwala określić, ile średnio firma zarabia na jednym kliencie w całym okresie jego współpracy.

## Uruchomienie
1. Pobierz repozytorium
2. Załaduj bazę danych do swojego systemu SQL
3. Uruchom zapytania SQL

## Technologie
- **SQL** (np. MySQL, PostgreSQL)
- **CTE** (Common Table Expressions)
- **Funkcje agregujące** (`SUM`, `AVG`, `COUNT`)
- **Zaawansowane operacje na danych** (`JOIN`, `UNION ALL`, `WITH`)
