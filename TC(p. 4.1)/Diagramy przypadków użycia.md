**4.1. Diagramy przypadków użycia**



**4.1.1. Opisy tekstowe wszystkich aktorów**



\- Śmiertelnik: Podstawowy użytkownik systemu. Może wysyłać modlitwy, składać ofiary i monitorować status swoich próśb.



\- Heros: Specjalny typ śmiertelnika. Posiada uprawnienia do przyjmowania misji od bogów, raportowania ich wyników oraz odbierania nagród.



\- Bóg (Użytkownik Boski): Odpowiada za konkretną domenę świata. Rozpatruje modlitwy, zleca interwencje lokalne oraz przydziela misje herosom.



\- Zeus (Administrator Główny): Posiada najwyższe uprawnienia. Zatwierdza interwencje o skali globalnej, zarządza panteonem oraz ma wgląd we wszystkie statystyki systemu.



\- Mojry: Aktorki odpowiedzialne za cykl życia. Zarządzają Nićmi Życia i inicjują proces przejścia duszy do Podziemi.



\- Hades: Administrator Podziemi. Nadzoruje rejestrację dusz, procesy sądowe oraz zarządza obłożeniem stref (Elizjum, Tartar, Asfodel).



\- Wyrocznia: Aktor analityczny. Przegląda raporty, analizuje trendy WRŚ (Wskaźnik Równowagi Świata) i generuje prognozy zagrożeń.



\- System (Aktor automatyczny): Odpowiada za obliczanie WRŚ, automatyczne powiadomienia o zgonach oraz wstępną weryfikację ofiar.



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



* Wykaz aktorów: Bóg, Śmiertelnik (odbiorca decyzji), System.



* Ciąg zdarzeń:



1. Podstawowy: Bóg otwiera listę oczekujących modlitw -> Wybiera modlitwę do analizy -> System wyświetla dane o ofierze i analizę sentymentu -> Bóg wybiera opcję „Akceptuj” -> Bóg określa typ interwencji (błogosławieństwo) -> System wysyła powiadomienie do śmiertelnika i rejestruje zdarzenie w historii.



2\. Alternatywny (Odrzucenie): Bóg uznaje ofiarę za niewystarczającą -> Wybiera opcję „Odrzuć” -> System zamyka sprawę bez interwencji.



3\. Alternatywny (Kara): Bóg uznaje modlitwę za bezczelną -> Wybiera opcję „Ześlij karę” -> System inicjuje negatywną interwencję punktową.



**Częstotliwość i parametry:**



* Częstotliwość: Ciągła (tysiące modlitw na dobę).



* Spiętrzenia: Okresy wojen, susz lub świąt religijnych.



* Czas realizacji: Typowy: 5 min; Maksymalny: 3 dni robocze.



* Wartość dla aktorów: Śmiertelnik otrzymuje pomoc lub informację zwrotną; Bóg utrzymuje poziom wiary i zarządza swoją domeną.



**II. Nazwa przypadku: Zatwierdzenie interwencji globalnej**



* Wykaz aktorów: Zeus, Bóg (wnioskodawca), System.



* Ciąg zdarzeń:



1. Podstawowy: Bóg konfiguruje interwencję o zasięgu „Kontynent” -> System blokuje automatyczne uruchomienie i przesyła wniosek do Zeusa -> Zeus otrzymuje powiadomienie o pilnej decyzji -> Zeus analizuje prognozowany wpływ na WRŚ -> Zeus klika „Zatwierdź” -> System uruchamia interwencję.



2\. Alternatywny (Odrzucenie): Zeus uznaje, że interwencja zbyt mocno zdestabilizuje świat -> Klika „Odrzuć” i wpisuje uzasadnienie -> Bóg wnioskodawca otrzymuje powiadomienie o odmowie.



**Częstotliwość i parametry:**



* Częstotliwość: Niska (kilka razy w miesiącu).



* Spiętrzenia: Globalne konflikty między bogami.



* Czas realizacji: Typowy: 1h; Maksymalny: 12h (wymagana szybka reakcja Władcy Olimpu).



* Wartość dla aktorów: Zeus sprawuje realną władzę i zapobiega chaosowi; Świat zachowuje stabilność (WRŚ nie spada drastycznie).



**III. Nazwa przypadku: Przeprowadzenie sądu nad duszą**



* Wykaz aktorów: Hades, Wyrocznia (dostawca rekomendacji), System.



* Ciąg zdarzeń:



1. Podstawowy: System powiadamia o nowej duszy w poczekalni Podziemi -> Hades otwiera kartotekę duszy -> System wyświetla listę czynów chwalebnych i grzechów (z Kronik Akaszy) -> Wyrocznia wyświetla rekomendację (np. 80% Elizjum) -> Hades zatwierdza werdykt -> System przypisuje duszę do strefy i aktualizuje statystyki obłożenia.



2\. Awaryjny (Błąd akt życia): Dane duszy są niekompletne -> Hades zawiesza proces i przesyła zapytanie do Mojr -> Proces zostaje wstrzymany do czasu uzupełnienia danych.



**Częstotliwość i parametry:**



* Częstotliwość: Bardzo wysoka (zależna od śmiertelności).



* Spiętrzenia: Wielkie bitwy, epidemie.



* Czas realizacji: Typowy: 2 min (z automatyzacją); Maksymalny: 24h.



* Wartość dla aktorów: Hades zachowuje porządek w Podziemiach; dusza trafia do należnego jej miejsca; system utrzymuje aktualne dane o populacji zmarłych.

