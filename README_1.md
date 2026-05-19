# MEDICA

System informatyczny obsługi pacjentów Sieć klinik Medica+

Projekt zaliczeniowy realizowany w ramach przedmiotu **Zarządzanie projektami informatycznymi**
Uczelnia Techniczno-Handlowa im. Heleny Chodkowskiej / Wydział Inżynieryjny

Autor: Jakub Molendowski (nr indeksu 35695), III rok Informatyki, grupa 1

## Opis projektu

System Medica+ to zintegrowane rozwiązanie informatyczne obsługi pacjentów dla sieci pięciu klinik medycznych. Projekt obejmuje:

- moduł rejestracji wizyt online (web + aplikacja mobilna),
- centralną dokumentację medyczną dostępną we wszystkich placówkach,
- moduł płatności online (opcjonalny),
- panel administracyjny i recepcji,
- zgodność z RODO oraz wymaganiami bezpieczeństwa danych medycznych.

## Struktura repozytorium

- `/docs` — dokumentacja projektowa (SRS, harmonogram, kosztorys z Ćwiczeń 1 i 2)
- `/db` — model danych ERD i skrypt DDL (`medica_ddl.sql`) z Ćwiczenia 4
- `/ui` — makiety UX/UI z Figmy: formularz logowania pacjenta i karta pacjenta (Ćwiczenie 6)
- `/notebooks` — notatniki Google Colab z kodem analitycznym (Ćwiczenie 7)
- `/src` — kod źródłowy (backend, frontend) — zarezerwowany na kolejne etapy projektu

## Technologie i narzędzia

- **Kontrola wersji:** Git, GitHub
- **Środowisko analityczne:** Google Colab, Python 3.x, Pandas, NumPy, Matplotlib
- **Baza danych:** MySQL 8.0, Visual Paradigm (modelowanie ERD)
- **UX/UI:** Figma
- **Zarządzanie projektem:** podejście hybrydowe (Waterfall + Scrum)

## Open in Colab

Notatnik z analizą danych można uruchomić bezpośrednio w przeglądarce:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jakubmolendowski-hub/MEDICA/blob/main/notebooks/cwiczenie_07_analiza.ipynb)

## Status projektu

Projekt w fazie realizacji etapów ćwiczeniowych. Kolejne moduły dodawane są zgodnie z harmonogramem przedmiotu Zarządzanie projektami informatycznymi (dr inż. Michał Malinowski).
