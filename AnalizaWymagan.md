# Analiza Wymagań

## 1. Interesariusze

| L.p. | Interesariusz      | Symbol |
|------|--------------------|--------|
| 1.   | Opiekun            | O      |
| 2.   | Kierownik projektu | KP     |
| 3.   | Lider zespołu      | LZ     |
| 4.   | Członek zespołu    | CP     |
| 5.   | Księgowa           | K      |

## 2. Wymagania funkcjonalne 


| L.p. | Symbol interesariusza | Moduł         | Oznaczenie | Opis                                                                                                                       | Priorytet | Status        |
|------|-----------------------|---------------|------------|----------------------------------------------------------------------------------------------------------------------------|-----------|---------------|
| 1.   | KP                    | Planowania    | P1         | Możliwość zarządzania zadaniami (dodawanie, usuwanie, edycja)                                                              | Wymagane  | Do razlizacji |
| 2.   | KP                    | Planowania    | P2         | Zarządzanie harmonogramem realizacji projektu (tworzenie, edycja)                                                          | Wymagane  | Do razlizacji |
| 3.   | KP, LZ                | Zamówień      | Z1         | Możliwość dodawnia zapotrzebowania na sprzęt i materiały                                                                   | Wymagane  | Do razlizacji |
| 4.   | KP, K                 | Zamówień      | Z2         | Możliwość weryfikacji i akceptacji zamówień                                                                                | Wymagane  | Do razlizacji |
| 5.   | KP                    | Administracja | A1         | Zarządzanie zespołami i personelem (tworzenie zepsołów, dodawnaie pracowników)                                             | Wymagane  | Do razlizacji |
| 6.   | KP                    | Administracja | A2         | Przydzielanie zadań do zespołów                                                                                            | Wymagane  | Do razlizacji |
| 7.   | LZ                    | Administracja | A3         | Przydzielanie zadań członkom zespołu                                                                                       | Wymagane  | Do razlizacji |
| 8.   | CP                    | Administracja | A4         | Dostarczanie wyników pracy                                                                                                 | Wymagane  | Do razlizacji |
| 9.   | CP                    | Administracja | A5         | Możliwość edycji swoich danych osobowych                                                                                   | Średni    | Do razlizacji |
| 10.  | CP                    | Administracja | A5         | Dodawanie swoich kwalifikacji/umiejeętności                                                                                | Średni    | Do razlizacji |
| 11.  | KP, LZ                | Administracja | A7         | Podgląd satatusu realizowanych zadań                                                                                       | Wymagane  | Do razlizacji |
| 12.  | KP, K                 | Księgowość    | K1         | Wprowadzania budżetu projektu i podział środków na kateogrie (np zakup sprzętu) i przypisanie od odpowiednich zadań/etapów | Wymagane  | Do razlizacji |
| 13.  | KP, K                 | Księgowość    | K2         | Wprowadzania i zarządzania fakturami, przypisywanie faktur do projektu                                                     | Wymagane  | Do razlizacji |
| 14.  | K                     | Księgowość    | K3         | Kontrola stanu budrzetu projektu                                                                                           | Wymagane  | Do razlizacji |
| 15.  | K                     | Księgowość    | K4         | Rozliczanie i opłacanie faktur                                                                                             | Wymagane  | Do razlizacji |
| 16.  | KP, K, O              | Raportowanie  | R1         | Generowanie raporów kosztów z realizowanego projektu                                                                       | Wymagane  | Do razlizacji |
| 17.  | O                     | Raportowanie  | R2         | Możliwość nadzoru nad realizowanymi projektami                                                                             | Wymagane  | Do razlizacji |
| 18.  | CP, LZ, KP            | Komunikacji   | Ko1        | Wysyłanie przypomnień i powiadomień o przypoisaniu zadań i zmienieniających się statusach                                  | Wymagane  | Do razlizacji |
| 19.  | CP, LZ, KP            | Komunikacji   | Ko2        | Umożliwienie sprawnej komuniakcji pomiędzy osobami zaangarzowanymi w proejkt                                               | Wymagane  | Do razlizacji |
| 20.  | CP, LZ, KP, K, O      | Administracja | A8         | Możliwość, logowania do systemu i zmiany hasła                                                                             | Wymagane  | Do razlizacji |

## 3. Wymagania niefunkcjonalne 


| L.p. | Opis                                                                                   |
|------|----------------------------------------------------------------------------------------|
| 1.   | Dostępność i niezawodność - System powinien być dostępny 24/7                          |
| 2    | System powinien zapewnić czas odpowiedzi poniżej 1s                                    |
| 3.   | Bezpieczeństwo - zapewnienie szyfrowania danych                                        |
| 4.   | Skalowalność                                                                           |
| 5.   | System powinien działać zgodnie z obowiązującymi przepisami (RODO i prawem finansowym) |
| 6.   | Interface użytkownika zgodny z wymaganiami WCAG                                        |

## 3. Specyfikacja i przypadki użycia

**Możliwość weryfikacji i akceptacji zamówień :**
- **Aktorzy:** Kieorwnik projektu, Księgowa 
- **Warunki początkowe:** Zamówienie oczekujące na akceptacje
- **Scenariusz główny:**

  - 
- **Scenariusze alternatywne:**

