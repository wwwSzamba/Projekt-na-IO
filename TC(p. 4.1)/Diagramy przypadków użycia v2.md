**4.1. Diagramy przypadków użycia**



**4.1.1. Opisy tekstowe wszystkich aktorów**



* Śmiertelnik: Podstawowy użytkownik systemu. Może wysyłać modlitwy, składać ofiary i monitorować status swoich próśb.



* Heros: Specjalny typ śmiertelnika. Posiada uprawnienia do przyjmowania misji od bogów, raportowania ich wyników oraz odbierania nagród.



* Bóg (Użytkownik Boski): Odpowiada za konkretną domenę świata. Rozpatruje modlitwy, zleca interwencje lokalne oraz przydziela misje herosom.



* Zeus (Administrator Główny): Posiada najwyższe uprawnienia. Zatwierdza interwencje o skali globalnej, zarządza panteonem oraz ma wgląd we wszystkie statystyki systemu.



* Mojry: Aktorki odpowiedzialne za cykl życia. Zarządzają Nićmi Życia i inicjują proces przejścia duszy do Podziemi.



* Hades: Administrator Podziemi. Nadzoruje rejestrację dusz, procesy sądowe oraz zarządza obłożeniem stref (Elizjum, Tartar, Asfodel).



* Wyrocznia: Aktor analityczny. Przegląda raporty, analizuje trendy WRŚ (Wskaźnik Równowagi Świata) i generuje prognozy zagrożeń.



* System (Aktor automatyczny): Odpowiada za obliczanie WRŚ, automatyczne powiadomienia o zgonach oraz wstępną weryfikację ofiar.



**Lista 10 przypadków użycia (do diagramu):**



1. Złożenie modlitwy wraz z ofiarą (Śmiertelnik)



2\. Rozpatrzenie modlitwy (Bóg)



3\. Konfiguracja interwencji lokalnej (Bóg)



4\. Zatwierdzenie interwencji globalnej (Zeus)



5\. Monitorowanie i przycinanie Nici Życia (Mojry)



6\. Przeprowadzenie sądu nad duszą (Hades)



7\. Zlecenie misji strategicznej (Bóg)



8\. Raportowanie wykonania zadania (Heros)



9\. Analiza raportów równowagi świata (Wyrocznia)



10\. Generowanie ostrzeżeń o destabilizacji (System)



**4.1.2. Opisy tekstowe wybranych przypadków użycia**



**I. Nazwa przypadku: Rozpatrzenie modlitwy**



* **Wykaz aktorów:** Bóg (inicjator), Śmiertelnik (beneficjent), System.



* **Ciąg zdarzeń:**



1. Podstawowy: Bóg otwiera listę oczekujących modlitw -> Wybiera modlitwę do analizy -> System wyświetla dane o ofierze i analizę sentymentu -> Bóg wybiera opcję „Akceptuj” -> Bóg określa typ interwencji (błogosławieństwo) -> System wysyła powiadomienie do śmiertelnika i rejestruje zdarzenie w historii.



2\. Alternatywny (Odrzucenie): Bóg uznaje ofiarę za niewystarczającą -> Wybiera opcję „Odrzuć” -> System zamyka sprawę bez interwencji.



3\. Alternatywny (Kara): Bóg uznaje modlitwę za bezczelną -> Wybiera opcję „Ześlij karę” -> System inicjuje negatywną interwencję punktową.



**Częstotliwość i parametry:**



* Częstotliwość: Ciągła (tysiące modlitw na dobę).



* Przewidywane spiętrzenia: Okresy wojen, susz lub wielkich świąt religijnych.



* Czasy realizacji: Typowy: 5 min; Maksymalny: 3 dni robocze.



**Opis wartości uzyskanych przez aktorów:**



* Bóg: Skonsumowanie ofiary, wzrost statystyk "Boskiego Autorytetu", uporządkowanie kolejki spraw.



* Śmiertelnik: Realna pomoc (interwencja) lub jasna informacja o braku przychylności bóstwa.



* System: Aktualizacja bazy danych Kronik Akaszy i historii interakcji.



**II. Nazwa przypadku: Zatwierdzenie interwencji globalnej**



* **Wykaz aktorów:** Zeus (decydent), Bóg (wnioskodawca), System.



* **Ciąg zdarzeń:**



1. Podstawowy: Bóg konfiguruje interwencję o zasięgu „Kontynent” -> System blokuje automatyczne uruchomienie i przesyła wniosek do Zeusa -> Zeus otrzymuje powiadomienie o pilnej decyzji -> Zeus analizuje prognozowany wpływ na WRŚ -> Zeus klika „Zatwierdź” -> System uruchamia interwencję.



2\. Alternatywny (Odrzucenie): Zeus uznaje, że interwencja zbyt mocno zdestabilizuje świat -> Klika „Odrzuć” i wpisuje uzasadnienie -> Bóg wnioskodawca otrzymuje powiadomienie o odmowie.



**Częstotliwość i parametry:**



* Częstotliwość: Niska (kilka razy w miesiącu).



* Przewidywane spiętrzenia: Globalne konflikty między bogami, próby przewrotów.



* Czasy realizacji: Typowy: 1h; Maksymalny: 12h (wymagana szybka reakcja).



**Opis wartości uzyskanych przez aktorów:**



* Zeus: Utrzymanie stabilności świata, realizacja polityki nadzoru nad panteonem.



* Bóg: Możliwość przeprowadzenia operacji o dużej skali po uzyskaniu legitymizacji najwyższej władzy.



* System: Ochrona przed krytycznym spadkiem WRŚ (Wskaźnika Równowagi Świata).



**III. Nazwa przypadku: Przeprowadzenie sądu nad duszą**



* **Wykaz aktorów:** Hades (sędzia), Wyrocznia (analityk), System.



* **Ciąg zdarzeń:**



1. Podstawowy: System powiadamia o nowej duszy w poczekalni Podziemi -> Hades otwiera kartotekę duszy -> System wyświetla listę czynów chwalebnych i grzechów (z Kronik Akaszy) -> Wyrocznia wyświetla rekomendację (np. 80% Elizjum) -> Hades zatwierdza werdykt -> System przypisuje duszę do strefy i aktualizuje statystyki obłożenia.



2\. Awaryjny (Błąd akt życia): Dane duszy są niekompletne -> Hades zawiesza proces i przesyła zapytanie do Mojr -> Proces zostaje wstrzymany do czasu uzupełnienia danych.



**Częstotliwość i parametry:**



* Częstotliwość: Bardzo wysoka (stały napływ dusz).



* Przewidywane spiętrzenia: Wielkie bitwy, epidemie, katastrofy naturalne.



* Czasy realizacji: Typowy: 2 min; Maksymalny: 24h.



**Opis wartości uzyskanych przez aktorów:**



* Hades: Optymalne zarządzanie logistyką Podziemi, redukcja kolejek na Styksie.



* Dusza (Śmiertelnik): Przejście do ostatecznego miejsca przeznaczenia zgodnie z zasługami.



* System: Archiwizacja cyklu życia śmiertelnika i zwolnienie zasobów w module "Żyjący".

