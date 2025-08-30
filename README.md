# [Nazwa projektu] – [Excel+SQL / Power BI / Python]

## 🎯 Cel
Krótko: co badam i po co (np. „Które produkty są najbardziej rentowne i jak zmienia się sprzedaż m/m?”).

## 🔧 Stos technologiczny
- Excel / SQL (Oracle/MySQL/…)
- Power BI / Python (pandas, numpy, matplotlib)
- (opcjonalnie) DAX / Jupyter

## 🗂️ Dane
- Źródło: [Kaggle / publiczny dataset] (link)
- Próbka w `data/sample.csv` (≤100 wierszy)
- Czyszczenie: usunięcie duplikatów, standaryzacja dat, brakujące wartości → imputacja/filtr

## 📐 Metody
- Agregacje (GROUP BY), KPI (GM%, AOV), segmentacja klientów (RFM), sezonowość
- (BI) Model danych, relacje, measures w DAX
- (Python) EDA, outliers (IQR), walidacja typów

## 📊 Wyniki (TL;DR)
- 3–5 punktów z kluczowymi wnioskami biznesowymi
- 1–2 wykresy/screenshoty (wstaw obrazki z `assets/`)

![dashboard](../assets/projectX_dashboard.png)

## 🧭 Jak uruchomić
- SQL: pliki w `/sql/` – kolejność 01_schema.sql → 02_queries.sql
- Python: `pip install -r requirements.txt` → uruchom notatniki w `/notebooks/`
- Power BI: otwórz `pbix/plik.pbix` lub obejrzyj screeny w `/assets/`

## ✅ Checklista jakości
- [x] Reprodukowalny wynik (kroki w README)
- [x] Opis decyzji analitycznych
- [x] Źródła danych + licencja
