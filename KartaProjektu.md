# Karta projektu
## 1. Informacje ogólne

**Tytuł projektu:** System zarządzania projektami badawczymi (Research planner)

**Akronim projektu** RP

**Data utworzenia:** 19.10.2025

**Wersja dokumentu:** 1.1

### Zespół projektowy

| Imię i nazwisko                                            |Rola w projekcie| Zakres odpowiedzialności                                                                                        |
|------------------------------------------------------------|---------------|-----------------------------------------------------------------------------------------------------------------|
| Piotr Kotarski                                             |Kierownik projektu| Planowanie, koordynacja, nadzór nad realizacją, kontakt z prowadzącym, raportowanie postępów                                         |
| Jarosław Abramek                                           |Analityk| Analiza wymagań, modelowanie procesów, opracowanie przypadków użycia i diagramów UML                                                    |
| Michał Budzyński                                           |Programista| Implementacja backendu (Java, Spring Boot), implementacja fronendu (React, TypScript)|
| Piotr Kotarski <br/> Jarosław Abramek<br/>Michał Budzyński |Dokumentalista| Tworzenie dokumentacji technicznej i użytkowej, przygotowanie raportu i prezentacji końcowej                                                |

**Prowadzący:** mgr Wojciech Moniuszko

**Jednostka dydaktyczna:** Wyższa Szkoła Administracji i Przedsiębiorczości w Lublinie

## 2. Cel projektu

Celem projektu Research Planer jest stworzenie uniwersalnej aplikacji wspierającej zespoły w planowaniu, realizacji, rozliczaniu, raportowaniu oraz monitorowaniu postępów projektów.
System ma na celu zwiększenie efektywności, transparentności i bezpieczeństwa zarządzania projektami niezależnie od ich charakteru – naukowego, komercyjnego, rozwojowego czy edukacyjnego.

Aplikacja umożliwi m.in.:
- Planowanie i definiowanie projektów, ich celów, harmonogramu i budżetu.
- Zarządzanie zadaniami, kamieniami milowymi i odpowiedzialnością członków zespołu.
- Monitorowanie postępów i wizualizację statusów (dashboard, wykresy Ganta, KPI.
- Rozliczanie kosztów i kontrolę budżetu projektu,
- Raportowanie postępów i wyników (okresowych, końcowych, finansowych),
- Zarządzanie użytkownikami i uprawnieniami w systemie,
- Komunikację wewnętrzną (komentarze, wiadomości, przypomnienia),
- Zgodność z wymogami RODO i zapewnienie bezpieczeństwa danych.


## 3. Uzasadnienie biznesowe / edukacyjne

Zespoły projektowe często korzystają z rozproszonych narzędzi (arkusze, komunikatory, maile), co prowadzi do utraty informacji, braku przejrzystości i problemów z terminowością.
Research Planner rozwiązuje te problemy poprzez stworzenie jednego, centralnego systemu do zarządzania wszystkimi aspektami projektu.

Korzyści:
- Usprawnienie koordynacji zadań i komunikacji w zespole,
- Zwiększenie przejrzystości działań i raportowania,
- Ułatwienie rozliczania i kontroli kosztów,
- Poprawa jakości i terminowości realizacji projektów,
- Zapewnienie bezpieczeństwa i zgodności z przepisami RODO,
- Wzrost kompetencji zespołu w zakresie pracy projektowej i technologicznej.

## 4. Zakres projektu

**W zakresie projektu:**

- Moduł planowania zadań i harmonogramów,
- Dashboard postępów i raportowania,
- Moduł budżetowania i rozliczeń,
- Zarządzanie użytkownikami, rolami i uprawnieniami,
- Mechanizmy bezpieczeństwa i zgodności z RODO,
- Generowanie raportów i analiz,
- Integracja z kalendarzem i powiadomieniami e-mail.

**Poza zakresem projektu:**

- Integracja z repozytoriami zewnętrznymi w których przechowywane są dane
- Mobilna wersja natywna

## 5. Główne wymagania

|Typ| Opis                                                                                                                                                                                    |
|---|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Funkcjonalne| Tworzenie i edycja projektów, planowanie zadań i etapów, definiowanie harmonogramu, zarządzanie zespołem i rolami, monitorowanie statusów, raportowanie postępów i finansów.            |
|Niefunkcjonalne| Wydajność: czas odpowiedzi ≤ 3 sekundy; dostępność: 99%; skalowalność: możliwość obsługi wielu projektów i użytkowników jednocześnie.|
|Interfejsowe| Webowy interfejs użytkownika (React, CSS3, TypeScript), kompatybilny z najpopularniejszymi przeglądarkami.                                                                                                                                               |
|Bezpieczeństwo i RODO| Logowanie i autoryzacja użytkowników z kontrolą ról, szyfrowanie danych (SSL/TLS), rejestrowanie zgód na przetwarzanie danych osobowych, anonimizacja danych po okresie retencji, kopie zapasowe i audyt działań użytkowników.                                                                                                                                      |

## 6. Zasoby i narzędzia

|Kategoria| Narzędzie / Technologia        |Cel|
|---------|--------------------------------|----|
|Zarządzanie projektem| Jira                           |Planowanie zadań i śledzenie postępów|
|Repozytorium| GitHub                         |Kontrola wersji|
|Backend| Java, Spring Boot              |Logika aplikacji i API|
|Frontend| CSS3, React, TypeScript |Interfejs użytkownika|
|Baza danych| PostgreSQL                     |Przechowywanie danych projektowych|
|Dokumentacja| Markdown                       |Tworzenie dokumentów technicznych i użytkowych|
|Komunikacja| Teams, Discord, Messenger      |Współpraca i spotkania zespołowe|

## 7. Harmonogram wstępny

|Etap| Zakres                  |Czas realizacji|
|----|-------------------------|---------------|
|1| Analiza wymagań i opracowanie specyfikacji        |Tydzień 1–2|
|2| Projekt systemu (modele danych, UML, architektura)  |Tydzień 3–4|
|3| Implementacja backendu  |Tydzień 5–7|
|4| Implementacja frontendu |Tydzień 8–9|
|5| Testy, integracja i poprawki       |Tydzień 10|
|6| Prezentacja i odbiór projektu    |Tydzień 11|

## 8. Ryzyka i działania zapobiegawcze

| Nr | Ryzyko                                             |Prawdopodobieństwo|Skutek| Działanie zapobiegawcze                                          |
|----|----------------------------------------------------|-------------------|------|------------------------------------------------------------------|
| 1  | Opóźnienia w realizacji funkcjonalności |Średnie|Wysoki| Regularne przeglądy sprintów i raporty postępów                          |
| 2  | Niewystarczająca precyzja wymagań                 |Średnie|Wysoki| Cotygodniowe konsultacje z prowadzącym i klientem|
| 3  | Brak doświadczenia w React/TypeScript             |Wysokie|Średni| Szkolenia i mentoring techniczny                                |
| 4  | Niedostępność kluczowych członków zespołu         |Niskie|Wysoki| Dokumentacja procesów i plan zastępstw                               |
| 5  | Ryzyko naruszenia danych osobowych         |Niskie|Wysoki| Zastosowanie zabezpieczeń RODO, szyfrowania i logowania dostępu        |

## 9. Rezultaty projektu

- W pełni działająca aplikacja webowa do zarządzania projektami,
- Moduły: planowania, monitoringu, raportowania i rozliczania,
- Zaimplementowane zabezpieczenia i zgodność z RODO,
- Dokumentacja techniczna, użytkowa i projektowa,
- Raport końcowy i prezentacja zespołowa (PowerPoint / PDF).

## 10. Kryteria sukcesu

- Implementacja wszystkich kluczowych funkcji zgodnie z wymaganiami,
- Stabilne działanie aplikacji w środowisku lokalnym,
- Zgodność z zasadami bezpieczeństwa i RODO,
- Pełna dokumentacja (techniczna, UML, użytkowa),
- Pozytywna ocena testów akceptacyjnych i odbioru projektu przez prowadzącego.


## 11. Akceptacja projektu

|Funkcja| Imię i nazwisko | Data       | Podpis                        |
|-------|-----------------|------------|-------------------------------|
|Kierownik projektu| Piotr Kotarski  | 19.10.2025 | _____________________________ |
|Prowadzący| mgr Wojciech Moniuszko | 19.10.2025 | _____________________________                        |