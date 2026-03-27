# 🏭 Symulacja Odlewania Kokilowego (Altair Inspire Cast)

Projekt inżynierski z zakresu Systemów CAx w odlewnictwie. Celem projektu było zaprojektowanie technologii odlewania kokilowego dla zadanego detalu ze stopu cynku (Zamak) oraz przeprowadzenie wielowariantowych symulacji numerycznych procesu zalewania i krzepnięcia.

## 🎯 Zakres i Cel Projektu
Projekt obejmował pełną ścieżkę przygotowania procesu odlewniczego:
1. **Analiza geometrii:** Wyznaczenie płaszczyzny podziału formy, dodanie pochyleń odlewniczych oraz obliczenie masy detalu.
2. **Projektowanie układu wlewowego:** Ręczne obliczenia hydrauliczne przekrojów kanałów wlewowych (Fmin, Fd, Fr) w dwóch iteracjach (uwzględniających masę samego układu wlewowego). Zaprojektowano cztery warianty zasilania: pojedynczy i podwójny odlew, zasilany od boku i od dołu.
3. **Symulacje Numeryczne (CAE):** Przeprowadzenie symulacji procesu zalewania i krzepnięcia w środowisku **Altair Inspire Cast**.
4. **Analiza cykli termicznych:** Badanie nagrzewania się formy kokilowej w symulacjach wielocyklowych (5, 10, 15 cykli).

## 🛠 Wykorzystane Narzędzia i Materiały
* **Oprogramowanie CAD:** Dassault Systèmes SolidWorks (modelowanie układów wlewowych, analiza masy).
* **Oprogramowanie CAE:** Altair Inspire Cast (symulacje płynięcia i krzepnięcia, termika formy).
* **Materiał odlewu:** Stop cynku (Zamak 3 / ZnAl4).
* **Metoda odlewania:** Odlewanie kokilowe grawitacyjne.

## ⚙️ Kluczowe Analizy i Wnioski
Przeprowadzono symulacje dla różnych wariantów zasilania, analizując wektory prędkości, rozkład temperatur oraz ryzyko powstawania mikroporowatości skurczowej.

**Najważniejsze wnioski z badań:**
* **Zasilanie dolne vs boczne:** Zasilanie wnęki formy od dołu przebiega znacznie spokojniej (mniejsze turbulencje), minimalizując ryzyko natlenienia stopu, jednak proces ten zajmuje więcej czasu niż zalewanie boczne.
* **Termika formy (Symulacje cykliczne):** Badania (do 15 cykli) wykazały, że punkty pomiarowe zlokalizowane blisko wnęki formy generują szybkie, periodyczne skoki temperatury (szok termiczny), natomiast obszary oddalone nagrzewają się liniowo i powoli.
* **Wydajność formy wielokrotnej:** Średnia temperatura formy przy odlewaniu pojedynczych detali (zwłaszcza przy zasilaniu dolnym) rośnie gwałtowniej niż w przypadku form wielokrotnych (dwa detale), co jest podyktowane korzystniejszym stosunkiem masy formy do masy wlewanego metalu.

## 📁 Zawartość repozytorium
* `README.md` - opis założeń i wniosków z projektu.
* `Dokumentacja_Projektu.pdf` - pełne sprawozdanie z obliczeniami układów wlewowych i wynikami symulacji.
* `images/` - wybrane zrzuty ekranu z programu Altair Inspire Cast i SolidWorks.

## 📷 Wizualizacje Symulacji (Altair Inspire Cast)

*(W tym miejscu podmień linki na odpowiednie zrzuty ekranu w formacie .jpg lub .png wycięte ze sprawozdania)*

### Model z zaprojektowanym układem wlewowym (Zasilanie dolne)
![Układ Wlewowy](images/uklad_wlewowy_dolu.png)

### Symulacja wypełniania - Rozkład prędkości
![Wektory Prędkości](images/predkosc_wypelniania.png)

### Analiza defektów - Mikroporowatość
![Mikroporowatość](images/mikroporowatosc.png)

### Analiza termiczna formy kokilowej w czasie
![Termika Formy](images/wykres_temperatury_cykle.png)

---
*Projekt zrealizowany w ramach zajęć "Systemy CAx w odlewnictwie" na Politechnice Warszawskiej (Kierunek: Automatyzacja i Robotyzacja Procesów Produkcyjnych). Projekt zespołowy.*
