# Karta projektu

Karta projektu to pierwszy oficjalny dokument projektowy, który opisuje jego podstawowe założenia: dlaczego projekt powstaje, co ma osiągnąć, jakie są ograniczenia, kto za co odpowiada i jak będzie mierzony sukces.

## 1. Informacje ogólne

**Tytuł projektu:** System zarządzania projektami badawczymi (Research planning)

**Akronim projektu:** Research planning

**Data utworzenia:** 19.10.2025

**Wersja dokumentu:** 1.0.0

### Zespół projektowy

| Imię i nazwisko                                            |Rola w projekcie| Zakres odpowiedzialności                                              |
|------------------------------------------------------------|---------------|-----------------------------------------------------------------------|
| Piotr Kotarski                                             |Kierownik projektu| Planowanie, koordynacja, raportowanie postępów, kontakt z prowadzącym |
| Jarosław Abramek                                           |Analityk| Analiza wymagań, tworzenie przypadków użycia, diagramów UML           |
| Michał Budzyński                                           |Programista| Implementacja backendu (Django), integracja z bazą danych             |
| Piotr Kotarski <br/> Jarosław Abramek<br/>Michał Budzyński |Dokumentalista| Redakcja dokumentacji projektowej, raporty, prezentacja końcowa       |

**Prowadzący:** mgr Wojciech Moniuszko

**Jednostka dydaktyczna:** Wyższa Szkoła Administracji i Przedsiębiorczości w Lublinie

## 2. Cel projektu

Celem projektu **System zarządzania projektami badawczymi** jest stworzenie aplikacji wspierającej zespoły badawcze w planowaniu, raportowaniu oraz monitorowaniu postępów projektów badawczych, zwiększającej efektywność i transparentność pracy.

## 3. Uzasadnienie biznesowe / edukacyjne

Obecnie zespoły badawcze mają utrudnione zarządzanie projektami z powodu braku zintegrowanego narzędzia, co prowadzi do fragmentacji danych, opóźnień i braku transparentności. Zaprojektowany system:

- Ułatwi koordynację zadań,
- Zcentralizuje dane projektowe,
- Zwiększy przejrzystość oraz efektywność pracy zespołowej.

## 4. Zakres projektu

**W zakresie projektu:**

- Funkcje planowania zadań i tworzenia harmonogramów
- Moduł raportowania postępów
- Monitorowanie statusów i wskaźników KPI
- Autoryzacja i zarządzanie użytkownikami

**Poza zakresem projektu:**

- Integracja z zewnętrznymi systemami zarządzania danymi laboratoryjnymi
- Mobilna wersja natywna

## 5. Główne wymagania

|Typ| Opis                                                                                                                                                                                               |
|---|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Funkcjonalne| Dodawanie etapów, planowanie zadań, definiowanie harmonogramu, <br/>tworzenie zespołów i dodawanie członków, definiowanie ról członkom<br/> zepsołu, modyfikacja statusu zadań, raportowanie wykonanej pracy |
|Niefunkcjonalne| Wydajność: czas odpowiedzi ≤ 3s; dostępność: 99%                                                                                                                                                   |
|Interfejsowe| Webowy interfejs (HTML5/CSS3/TypeScript)                                                                                                                                                           |
|Bezpieczeństwo| Logowanie użytkowników (role), szyfrowanie danych                                                                                                                                                  |

## 6. Zasoby i narzędzia

|Kategoria| Narzędzie / Technologia        |Cel|
|---------|--------------------------------|----|
|Zarządzanie projektem| Jira                           |Planowanie zadań i śledzenie postępów|
|Repozytorium| GitHub                         |Kontrola wersji|
|Backend| Java, Spring Boot              |Implementacja logiki aplikacji|
|Frontend| HTML5, CSS3, React, TypeScript |Interfejs użytkownika|
|Baza danych| PostgreSQL                     |Przechowywanie danych projektowych|
|Dokumentacja| Markdown                       |Tworzenie dokumentów|
|Komunikacja| Teams, Discord, Messenger      |Spotkania i komunikacja zespołowa|

## 7. Harmonogram wstępny

|Etap|Zakres|Czas realizacji|
|----|------|---------------|
|1|Analiza wymagań|Tydzień 1–2|
|2|Projekt systemu (UML)|Tydzień 3–4|
|3|Implementacja backendu|Tydzień 5–7|
|4|Implementacja frontendu|Tydzień 8–9|
|5|Testy i poprawki|Tydzień 10|
|6|Prezentacja i odbiór|Tydzień 11|

## 8. Ryzyka i działania zapobiegawcze

|Nr| Ryzyko                                   |Prawdopodobieństwo|Skutek|Działanie zapobiegawcze|
|--|------------------------------------------|-------------------|------|------------------------|
|1| Opóźnienia w dostarczaniu wymagań        |Średnie|Wysoki|Cotygodniowe przeglądy wymagań|
|2| Brak doświadczenia w React/TypeScript    |Wysokie|Średni|Szkolenia i mentoring|
|3| Niedostępność Kluczowych członków zespołu |Niskie|Wysoki|Zastępstwa i dokumentacja procesów|
|4| Błędy w integracji API                   |Średnie|Średni|Testy automatyczne i przegląd kodu|

## 9. Rezultaty projektu

- Działająca aplikacja webowa do zarządzania projektami badawczymi
- Dokumentacja techniczna i użytkowa
- Raport końcowy
- Prezentacja zespołowa (PowerPoint / PDF).

## 10. Kryteria sukcesu

- Implementacja wszystkich kluczowych funkcji zgodnie z wymaganiami
- Aplikacja uruchamia się lokalnie i działa poprawnie
- Dokumentacja zawiera pełny zestaw diagramów UML
- Testy akceptacyjne zakończone wynikiem pozytywnym.
- Projekt został pozytywnie oceniony przez prowadzącego.

## 11. Akceptacja projektu

|Funkcja| Imię i nazwisko | Data       | Podpis                        |
|-------|-----------------|------------|-------------------------------|
|Kierownik projektu| Piotr Kotarski  | 19.10.2025 | _____________________________ |
|Prowadzący| mgr Wojciech Moniuszko | 19.10.2025 | _____________________________                        |