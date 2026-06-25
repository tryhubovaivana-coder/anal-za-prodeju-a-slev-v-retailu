# Plán projektu a proces analýzy českých retailových dat

Tento dokument slouží jako osnova a plán jednotlivých kroků při zpracování oficiálních statistik českého maloobchodu.

## 📋 Fáze 1: Definice projektu a rešerše zdrojů
* [x] Formulace cílů (analýza tržeb a spotřebního koše v ČR).
* [x] Vytvoření struktury repozitáře na GitHubu.
* [ ] Lokalizace konkrétních sad otevřených dat na portálech ČSÚ a NKOD.

## 📥 Fáze 2: Sběr a import dat
* [ ] Stažení časových řad maloobchodních tržeb a cen potravin (.csv/.xlsx).
* [ ] Prvotní audit dat (kontrola struktury kódovníků ČSÚ, časových období a jednotek).

## 🧹 Fáze 3: Transformace a čištění českých dat
* [ ] Sjednocení formátů dat a ošetření chybějících hodnot v historických řadách.
* [ ] Propojení tabulek s cenami komodit a indexy spotřebitelských cen.
* [ ] Očištění dat od sezónních vlivů (např. vánoční nákupní horečka vs. slabší leden).

## 🔍 Fáze 4: Analytická fáze (ČSÚ Insights)
* [ ] **Analýza tržeb:** Které segmenty maloobchodu v ČR rostou a které stagnují?
* [ ] **Analýza spotřebního koše:** Jak dramaticky se změnily ceny základních potravin (mléko, máslo, pečivo) za poslední roky?
* [ ] **Korelace:** Jak růst inflace ovlivňuje celkový objem prodaného zboží?

## 📊 Fáze 5: Reporty a vizualizace
* [ ] Tvorba interaktivního dashboardu "Vývoj cen potravin v ČR" pro koncové uživatele.
* [ ] Příprava přehledných grafů ukazujících reálnou kupní sílu obyvatel.
* [ ] Shrnutí hlavních zjištění a publikace výsledné analytické zprávy.
