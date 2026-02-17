# Power BI KPI Dashboard (Operations/Reporting)

Dieses Repository zeigt ein interaktives **Power-BI-Dashboard** zur KPI-Steuerung im Kontext **Operations/Reporting**.  
Fokus: aus Rohdaten **klare Entscheidungsgrundlagen** machen – über saubere Datenaufbereitung, ein nachvollziehbares Datenmodell und KPI-Logik in DAX.

## Inhalte (Report-Funktionen)
- **KPI Cards**: OTIF Rate, Late Rate, Revenue, Total Orders  
- **Datenschnitt (Slicer)**: Monatsfilter zur zeitlichen Analyse  
- **Visuals**:
  - **Trendanalysen** über Monate (z.B. OTIF / Late Rate)
  - **Breakdowns** nach Customer / Site / Product (z.B. Top-N „Late Customers“)
- **Ad-hoc Analyse** durch Filter/Interaktionen innerhalb des Reports

## Datenmodell (kurz)
- Mehrere Tabellen (z.B. Orders, Inventory, Targets) plus Dimensionen (z.B. Date/Month, Product, Site)  
- Beziehungen im Sinne eines **Fakt-/Dimension-Modells** (Star-Schema-orientiert), damit Filter konsistent wirken.

## KPIs (Kurzdefinitionen)
- **OTIF (On Time In Full)**: Anteil der Bestellungen, die *pünktlich* und *vollständig* geliefert werden  
- **Late Rate**: Anteil verspäteter Bestellungen  
- **Revenue**: Gelieferte Menge × Stückpreis  
- **Total Orders**: Anzahl eindeutiger Bestellungen

## Tech Stack
- **Power BI Desktop**
- **Power Query** (Datenaufbereitung/Transformation)
- **DAX** (KPI-Measures)
- Optional: Excel/CSV als Demo-Datenquelle

## Screenshots
Siehe Ordner: `./screenshots/`  
Empfohlen: `overview.png`, `drilldown.png`, `model.png`

## Hinweis zu Daten
Dieses Projekt nutzt **Demo-/Beispieldaten**. Es werden **keine** vertraulichen oder personenbezogenen Unternehmensdaten veröffentlicht.

---
Wenn du Fragen hast oder ein bestimmtes KPI-Set sehen möchtest, melde dich gern.
