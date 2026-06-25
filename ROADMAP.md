# Plán projektu a proces analýzy retailových dat

Tento dokument slouží jako osnova a plán jednotlivých kroků při analýze transakčních dat a prodejních výsledků obchodního řetězce.

## 📋 Fáze 1: Definice projektu a obchodní logiky
* [x] Stanovení klíčových retailových metrik (Tržby, Marže, Velikost koše, Podíl slev).
* [x] Vytvoření struktury repozitáře na GitHubu.
* [ ] Vyhledání vhodných veřejných datových sad (např. historie pokladních dokladů).

## 📥 Fáze 2: Import dat a návrh struktury
* [ ] Nahrání historie transakcí, číselníků produktů a dat o prodejnách.
* [ ] Prvotní audit dat (ověření unikátnosti ID účtenek, časových razítek a správnosti cen).

## 🧹 Fáze 3: Čištění retailových dat
* [ ] Ošetření chybějících čísel věrnostních karet a řešení stornovaných nákupů (vratky).
* [ ] Sjednocení a kategorizace produktů (např. Mléčné výrobky, Pečivo, Nápoje).
* [ ] Odstranění systémových chyb a anomálií v nákupních cenách.

## 🔍 Fáze 4: Průzkumná analýza dat (EDA)
* [ ] **Výkonnost prodeje:** Identifikace nejziskovějších prodejen, top produktů a špičkových nákupních hodin.
* [ ] **Analýza nákupního koše:** Zjištění průměrné útraty a hledání produktů, které zákazníci kupují společně.
* [ ] **Vyhodnocení slev:** Porovnání objemu prodejů v akčních týdnech oproti běžným dnům.

## 📊 Fáze 5: Dashboardy a praktická doporučení
* [ ] Tvorba reportu pro vedoucí prodejen se sledováním hlavních výkonnostních ukazatelů (KPIs).
* [ ] Vizualizace sezónních trendů pro lepší plánování zásobování a skladů.
* [ ] Formulace doporučení pro vystavení zboží na regálech a strategii plánování slev.
