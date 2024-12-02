# Analiza Zdrowia Psychicznego w Zależności od Środowiska Pracy

### Opis Projektu
Projekt przewiduje wpływ środowiska pracy na dobrostan psychiczny pracowników oraz ich poziom satysfakcji zawodowej. Skupi się on na tworzeniu modelu predykcyjnego, który pomoże zrozumieć czynniki wpływające na zdrowie psychiczne oraz podjąć działania mające na celu poprawę dobrostanu pracowników.

### Problemy do Rozwiązania
1. Jak praca zdalna wpływa na poziom stresu i izolacji społecznej?
2. Jakie różnice można zaobserwować między różnymi lokalizacjami pracy (zdalna, hybrydowa, stacjonarna)?
3. Jak różne grupy demograficzne (np. wiek, płeć) odczuwają skutki pracy zdalnej?

### Źródło Danych
Zestaw danych: "Remote Work & Mental Health" 
Link: https://www.kaggle.com/datasets/iramshahzadi9/remote-work-and-mental-health/data

### Dane
Zawierają 5 000 rekordów zebranych od pracowników z całego świata. Kluczowe informacje zawarte w zbiorze danych obejmują:
- Dane demograficzne (ID pracownika, wiek, płeć).
- Informacje o charakterze pracy (rola, branża, lokalizacja pracy).
- Czynniki związane ze zdrowiem psychicznym (poziom stresu, występowanie problemów psychicznych, poziom izolacji społecznej).
- Satysfakcja z pracy zdalnej.

### Charakterystyka Danych

| **Atrybut**                    | **Opis**                                                                                              |
|--------------------------------|-------------------------------------------------------------------------------------------------------|
| `Employee_ID`                  | Unikalny identyfikator dla każdego pracownika.                                                        |
| `Age`                          | Wiek pracownika.                                                                                      |
| `Gender`                       | Płeć pracownika (np. Male, Female, Other).                                                            |
| `Job_Role`                     | Obecne stanowisko pracownika (np. Data Scientist, Manager, Developer).                                |
| `Industry`                     | Branża, w której pracownik pracuje (np. IT, Healthcare, Finance).                                     |
| `Work_Location`                | Rodzaj pracy (np. Remote, Hybrid, Onsite).                                                            |
| `Stress_Level`                 | Poziom stresu zgłoszony przez pracownika (od 1 do 10, gdzie 10 oznacza najwyższy stres).              |
| `Mental_Health_Condition`      | Zgłoszone problemy ze zdrowiem psychicznym (np. Anxiety, Depression, None).                           |
| `Social_Isolation_Rating`      | Samoocena pracownika na temat odczuwanej izolacji (od 1 do 5, gdzie 5 oznacza najwyższą izolację).    |
| `Satisfaction_with_Remote_Work`| Ocena zadowolenia z pracy zdalnej (np. Satisfied, Neutral, Unsatisfied).                              |

### Uzasadnienie Wyboru Zbioru Danych
Wybrano ten zbiór danych ze względu na jego aktualność i praktyczne zastosowanie. Zbiór zawiera kluczowe zmienne oraz różnorodne cechy co pozwala na przeprowadzenie bardziej wnikliwych analiz oraz budowę dobrych modeli predykcji.

### Cel Projektu
Celem projektu jest zbudowanie systemu analitycznego i modelu predykcyjnego, który pozwoli:
1. Zrozumieć wpływ pracy zdalnej na różne aspekty zdrowia psychicznego, takie jak poziom stresu, izolacja społeczna oraz występowanie problemów zdrowotnych.
2. Określić, jakie czynniki najbardziej wpływają na samopoczucie pracowników.
3. Przewidywać poziom zadowolenia i potencjalne problemy zdrowotne pracowników w zależności od ich warunków pracy.

### Struktura Projektu
1. Wstępna Analiza Danych
   - Importowanie i wstępna obróbka danych
   - Analiza statystyczna i wizualizacja istotnych cech (poziom stresu, izolacja, zadowolenie)
2. Przygotowanie danych
   - Usunięcie danych lub ich imputacja
   - Normalizacja danych liczbowych oraz zakodowanie zmiennych kategorycznych
   - Podział danych na zestaw treningowy (70%) i testowy (30%) 
3. Wybór i Budowa Modelu
   - Testowanie różnych algorytmów uczenia maszynowego (np. regresji logistycznej, drzew decyzyjnych, SVM).
4. Uczenie Modelu
   - Trenowanie wybranych algorytmów na zestawie treningowym.
   - Obliczanie podstawowych metryk skuteczności (np. dokładności, precyzji, czułości).
5. Walidacja i Testowanie
   - Walidacja wyników modelu przy użyciu zestawu testowego.
   - Porównanie skuteczności różnych modeli i wybór najlepszego na podstawie metryk jakościowych.
6. Optymalizacja Modelu
   - Dostosowanie hiperparametrów modeli (np. Grid Search lub Random Search).
7. Analiza Wyników i Wnioski
   - Wyciągnięcie kluczowych czynników wpływających na stres, izolację i satysfakcję.
8. Prezentacja i Raport Końcowy
   - Stworzenie raportu z wizualizacjami wyników analizy i predykcji.
