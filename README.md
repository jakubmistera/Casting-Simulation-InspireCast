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

### Model 3D
<img width="379" height="381" alt="image" src="https://github.com/user-attachments/assets/9da45ff5-05cc-412d-a1d9-19560045a475" />

### 140-95otw
<img width="944" height="1336" alt="image" src="https://github.com/user-attachments/assets/febdf00d-0389-433c-8638-573a6b09b39c" />

### Pochylenia odlewnicze
<img width="945" height="1342" alt="image" src="https://github.com/user-attachments/assets/8959fc96-f3e2-4c08-8d34-a20d2d103e38" />

### Układ wlewowy dla iteracji drugiej - 2 od dołu
<img width="935" height="964" alt="image" src="https://github.com/user-attachments/assets/3f382e58-a026-4a1d-bfd9-019da127f388" />

### Układ wlewowy dla iteracji drugiej - 2 od dołu
<img width="934" height="866" alt="image" src="https://github.com/user-attachments/assets/db4925da-9291-4be3-a5ad-99700b0c9e22" />

### Mikroporowatość
<img width="945" height="618" alt="image" src="https://github.com/user-attachments/assets/1aaf4973-ccc3-4e56-9405-ce322f7b4f1a" />

### Rozkład wektorów prędkości
<img width="842" height="673" alt="image" src="https://github.com/user-attachments/assets/7dd95dec-34b7-45b1-b08e-409549ae110f" />

### Wykres punktowy czasu od liczby cykli
<img width="1026" height="525" alt="image" src="https://github.com/user-attachments/assets/f41c6ace-3244-47c7-af4e-72db32a63a8f" />

### Wykres temperatury formy od czasu (odlew pojedynczy z bocznej powierzchni)
<img width="832" height="665" alt="image" src="https://github.com/user-attachments/assets/86856401-8d1a-4743-882b-b429bda4ff2e" />

### Wykres średniej temperatury formy od liczby cykli
<img width="1050" height="527" alt="image" src="https://github.com/user-attachments/assets/551757ec-470d-47c3-9dea-226e56047489" />

---
*Projekt zrealizowany w ramach zajęć "Systemy CAx w odlewnictwie" na Politechnice Warszawskiej (Kierunek: Automatyzacja i Robotyzacja Procesów Produkcyjnych). Projekt zespołowy.*
