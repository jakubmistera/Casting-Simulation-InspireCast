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
* `images/` - wybrane zrzuty ekranu z programu Altair Inspire Cast i SolidWorks.

## 📷 Wizualizacje Symulacji (Altair Inspire Cast)

*(W tym miejscu podmień linki na odpowiednie zrzuty ekranu w formacie .jpg lub .png wycięte ze sprawozdania)*

### Model 3D
<img width="379" height="381" alt="image" src="https://github.com/user-attachments/assets/9da45ff5-05cc-412d-a1d9-19560045a475" />

### 140-95otw
<img width="944" height="1336" alt="image" src="https://github.com/user-attachments/assets/febdf00d-0389-433c-8638-573a6b09b39c" />

### Pochylenia odlewnicze
<img width="945" height="1342" alt="image" src="https://github.com/user-attachments/assets/8959fc96-f3e2-4c08-8d34-a20d2d103e38" />

### Układ wlewowy dla iteracji pierwszej - 1 od boku
<img width="839" height="835" alt="image" src="https://github.com/user-attachments/assets/3686e578-b10b-45ec-985f-34723bcce6f0" />

### Układ wlewowy dla iteracji pierwszej - 2 od boku
<img width="844" height="789" alt="image" src="https://github.com/user-attachments/assets/b32b94ea-3214-4ec7-8b6f-a118801ed21c" />

### Układ wlewowy dla iteracji pierwszej - 1 od dołu
<img width="861" height="816" alt="image" src="https://github.com/user-attachments/assets/87b4889c-a59b-4289-b39f-80eb6de763e9" />

### Układ wlewowy dla iteracji pierwszej - 2 od dołu
<img width="853" height="879" alt="image" src="https://github.com/user-attachments/assets/ae06cbeb-c81f-4a52-a1f8-ce958b21422b" />

### Układ wlewowy dla iteracji drugiej - 1 od boku
<img width="927" height="922" alt="image" src="https://github.com/user-attachments/assets/36dcfba1-fa98-4de1-adc1-75b7321dab30" />

### Układ wlewowy dla iteracji drugiej - 1 od boku
<img width="930" height="1037" alt="image" src="https://github.com/user-attachments/assets/18804811-00d0-45dd-b63b-81a9d75e30fa" />


---
*Projekt zrealizowany w ramach zajęć "Systemy CAx w odlewnictwie" na Politechnice Warszawskiej (Kierunek: Automatyzacja i Robotyzacja Procesów Produkcyjnych). Projekt zespołowy.*
