# Analiza Wymagań

## 1. Interesariusze

| L.p. | Interesariusz      | Symbol |
|------|------------------|--------|
| 1.   | Opiekun           | O      |
| 2.   | Kierownik projektu| KP     |
| 3.   | Lider zespołu     | LZ     |
| 4.   | Członek zespołu   | CP     |
| 5.   | Księgowa          | K      |

## 2. Wymagania funkcjonalne 


| L.p. | Symbol interesariusza | Moduł         | Oznaczenie | Opis                                                                             | Priorytet | Status        |
|------|-----------------------|---------------|------------|----------------------------------------------------------------------------------|-----------|---------------|
| 1    | KP                 | Zarządzanie zadaniami | ZAD1 | Dodawanie, edycja i usuwanie zadań                                               | Wymagane  | Do realizacji |
| 2    | KP                 | Harmonogram       | H1   | Tworzenie i edycja harmonogramu projektu                                         | Wymagane  | Do realizacji |
| 3    | KP, LZ             | Zamówienia        | ZAM1 | Dodawanie zapotrzebowania na sprzęt i materiały                                  | Wymagane  | Do realizacji |
| 4    | KP, K              | Zamówienia        | ZAM2 | Weryfikacja i akceptacja zamówień                                                | Wymagane  | Do realizacji |
| 5    | KP                 | Zespoły           | ZES1 | Tworzenie zespołów i dodawanie pracowników                                       | Wymagane  | Do realizacji |
| 6    | KP                 | Zespoły           | ZES2 | Przydzielanie zadań do zespołów                                                  | Wymagane  | Do realizacji |
| 7    | LZ                 | Zespoły           | ZES3 | Przydzielanie zadań członkom zespołu                                             | Wymagane  | Do realizacji |
| 8    | CP                 | Zespoły           | ZES4 | Dostarczanie/raportowanie wyników pracy                                          | Wymagane  | Do realizacji |
| 9    | CP                 | Profil użytkownika| PRO1 | Edycja danych osobowych                                                          | Średni    | Do realizacji |
| 10   | CP                 | Profil użytkownika| PRO2 | Dodawanie kwalifikacji i umiejętności                                            | Średni    | Do realizacji |
| 11   | KP, LZ             | Zespoły           | ZES5 | Podgląd statusu realizowanych zadań                                              | Wymagane  | Do realizacji |
| 12   | KP, K              | Finanse           | FIN1 | Wprowadzanie budżetu projektu i podział środków na kategorie (np. zakup sprzętu) | Wymagane  | Do realizacji |
| 13   | KP, K              | Finanse           | FIN2 | Zarządzanie fakturami i przypisywanie ich do projektów                           | Wymagane  | Do realizacji |
| 14   | K                  | Finanse           | FIN3 | Kontrola stanu budżetu projektu                                                  | Wymagane  | Do realizacji |
| 15   | K                  | Finanse           | FIN4 | Rozliczanie i opłacanie faktur                                                   | Wymagane  | Do realizacji |
| 16   | KP, K, O           | Raporty           | RAP1 | Generowanie raportów kosztów projektu                                            | Wymagane  | Do realizacji |
| 17   | O                  | Raporty           | RAP2 | Nadzór nad realizowanymi projektami                                              | Wymagane  | Do realizacji |
| 18   | CP, LZ, KP         | Komunikacja       | KOM1 | Wysyłanie powiadomień i przypomnień o zadaniach i zmianach statusu               | Wymagane  | Do realizacji |
| 19   | CP, LZ, KP         | Komunikacja       | KOM2 | Umożliwienie sprawnej komunikacji między członkami projektu                      | Wymagane  | Do realizacji |
| 20   | CP, LZ, KP, K, O   | Autoryzacja       | AUT1 | Logowanie do systemu i zmiana hasła                                              | Wymagane  | Do realizacji |

## 3. Wymagania niefunkcjonalne 


| L.p. | Opis                                                                                   |
|------|----------------------------------------------------------------------------------------|
| 1    | **Dostępność i niezawodność** – System powinien działać 24/7                            |
| 2    | **Wydajność** – Czas odpowiedzi systemu powinien być poniżej 1 sekundy                  |
| 3    | **Bezpieczeństwo** – Dane muszą być szyfrowane i chronione przed nieautoryzowanym dostępem |
| 4    | **Skalowalność** – System powinien umożliwiać łatwe rozszerzanie funkcjonalności i zasobów |
| 5    | **Zgodność z przepisami** – System powinien spełniać wymagania RODO i prawa finansowego |
| 6    | **Dostępność interfejsu** – UI powinno być zgodne z wytycznymi WCAG dla osób niepełnosprawnych |
| 7    | **Łatwość utrzymania** – Kod i struktura systemu powinny ułatwiać rozwój i konserwację  |

## 3. Specyfikacja i przypadki użycia

**Weryfikacji i akceptacji zamówień:**
- **Aktorzy:** kieorwnik projektu, lider zespołu, księgowa 
- **Warunki początkowe:** 

  - Użytkownik zalogowany do systemu
  - Użytkownik posiada uprawnienia do weryfikacji zamówień
  - Zamówienie oczekujące na akceptacje
- **Scenariusz główny:**

  - Użytkownik wybiera moduł „Zamówienia”
  - Użytkownik wyszukuje i wybiera projekt
  - System wyświetla listę oczekujących zamówień
  - Użytkownik przegląda szczegóły zamówienia
  - Weryfikacja środków potrzebnych do realizacji zamówienia
  - Użytkownik zatwierdza lub odrzuca zamówienie
  - System aktualizuje status zamówienia i powiadamia zainteresowane osoby
- **Scenariusze alternatywne:**

  - A1: Zamówienie zawiera błędne dane → system wyświetla komunikat o błędzie i nie pozwala na akceptację
  - A2: Problem z połączeniem do bazy → system informuje o błędzie i pozwala na ponowną próbę

![weryfikacjaIAkcpetacjaZamowienia](diagramy%2FweryfikacjaIAkcpetacjaZamowienia.png)

**Kontrola stanu budżetu projektu:**
- **Aktorzy:** Księgowa
- **Warunki początkowe:**
  - Użytkownik zalogowany do systemu
  - Użytkownik posiada uprawnienia do podglądu budżetu
  - Projekt posiada przypisany budżet
- **Scenariusz główny:**
  - Księgowa wybiera moduł „Finanse”
  - Użytkownik wyszukuje i wybiera projekt
  - System wyświetla aktualny stan budżetu projektu
  - Księgowa przegląda przydział środków i wykorzystanie budżetu
  - Księgowa przegląda zrealizowane zamówienia i faktury
  - System generuje raport z aktualnym stanem budżetu
- **Scenariusze alternatywne:**
  - A1: Dane finansowe są niekompletne → system informuje o brakujących informacjach
  - A2: Problem z dostępem do danych → system wyświetla komunikat o błędzie  

![kontrolaStanuBudzetu](diagramy%2kontrolaStanuBudzetu.png)


**Dodawanie zapotrzebowania na sprzęt i materiały:**
- **Aktorzy:** Kierownik projektu, Lider zespołu
- **Warunki początkowe:**
  - Użytkownik zalogowany do systemu
  - Użytkownik posiada uprawnienia do dodawania zapotrzebowań
  - Projekt wymaga zakupu materiałów lub sprzętu
- **Scenariusz główny:**
  - Użytkownik wybiera moduł „Zamówienia”
  - Użytkownik wyszukuje i wybiera projekt
  - Kliknięcie przycisku „Dodaj zapotrzebowanie”
  - System wyświetla formularz zapotrzebowania
  - Użytkownik wprowadza szczegóły (rodzaj materiału, ilość, termin)
  - Użytkownik zatwierdza formularz
  - System zapisuje zapotrzebowanie i wysyła powiadomienie do odpowiedzialnych osób
- **Scenariusze alternatywne:**
  - A1: Nie wypełniono wymaganych pól → system wyświetla komunikat o błędzie
  - A2: Problem z zapisem do bazy → system proponuje ponowienie operacji  

**Generowanie raportów kosztów projektu:**
- **Aktorzy:** Kierownik projektu, Księgowa, Opiekun
- **Warunki początkowe:**
  - Użytkownik zalogowany do systemu
  - Użytkownik posiada uprawnienia do generowania raportów
  - Projekt posiada wprowadzone dane finansowe
- **Scenariusz główny:**
  - Użytkownik wybiera moduł „Raporty”
  - System wyświetla opcje raportów kosztów
  - Użytkownik wybiera zakres danych i typ raportu
  - System generuje raport i wyświetla podgląd
  - Użytkownik może pobrać raport w formacie PDF lub CSV
- **Scenariusze alternatywne:**
  - A1: Brak danych w wybranym zakresie → system wyświetla komunikat i pozwala wybrać inny zakres
  - A2: Problem z generowaniem raportu → system proponuje ponowienie operacji  
