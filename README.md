 <div align="center">
  <img alt="Application image" src="https://cssh.northeastern.edu/informationethics/wp-content/uploads/sites/44/2020/07/ai@2x.png" width="400" />
</div>
<br>
  <div align="center">
    <img src="https://img.shields.io/badge/-Python-black?style=for-the-badge&logoColor=white&logo=python&color=61DAFB" alt="Python" />

# Közmű APPLICATION v2

Egy Python-alapú, grafikus felületet biztosító program a közműdiktálások kezelésére. A program tkinter könyvtárat használ a vizuális megjelenítéshez, és minden diktálási adatot egy CSV fájlban tárol.

## 🚀AZ ÖTLET - PROMPT

Készíts egy jól működő programot vizuális megjelenítéssel python nyelven CSV fájlba történő mentéssel, ami összesíti a közművek diktálási értékeit m3-ben, kWh-ban, számlák összegeit, két legutolsó diktálási érték közötti különbséget vagyis a fogyasztást, diktálás dátumait, ezekből keletkező számlák összegét forintban és be lehet írni az újabb diktálásokat és számlák összegét. Legyen benne Gáz, Áram, Víz diktálása...

## A Program Funkciói

- 🚀Közműtípusok: Gáz, Áram, Víz.
- 🚀Diktálási Adatok Bevitele: Előző és új diktálási értékek (m³ vagy kWh), számlaösszeg (Ft), és dátum.
- 🚀Diktálási Adatok Megjelenítése és szerkesztése: Előző és új diktálási értékek (m³ vagy kWh), számlaösszeg (Ft), és mentés dátuma.
- 🚀Fogyasztás Számítása: Két egymást követő diktálási érték különbsége.
- 🚀Fájlba Mentés: Az adatokat egy .csv fájlba mentjük.

## A Program Magyarázat

- 1. Kezdő Ablak és Felület: Az ablakban címkék és beviteli mezők jelennek meg, ahol a közmű típusát, előző és új diktálási értéket, valamint a számla összegét lehet megadni.

- 2. Fájlba Mentés: A save_data függvény a megadott adatokat egy fájlba menti. A fájl neve ozmu_diktalasok.csv, és minden új adatot egy új sorba ír.

- 3. Hibakezelés: Ha a felhasználó hibás adatot ad meg (pl. szöveget egy szám mezőben), a program figyelmeztetést jelenít meg.

- 4. Beviteli mezők törlése: Sikeres mentés után a beviteli mezők kiürülnek, hogy új adatokat lehessen megadni.

**Running the Project**

```bash
python main.py

```

**Saved data**
A kozmu_diktalasok.csv fájlba mentett adatok például így fognak kinézni:

```bash
�ram,13463,13643,180,9680,2024-11-09
G�z,13463,13643,180,9680,2024-11-09
```