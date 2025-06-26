# Meditimer – Development Report

## 📌 Versionierung: `v0.1xx`

### ✅ v0.100 – Initialversion
- Medikamentenbuttons (Ibuprofen, Paracetamol)  
- Manuelle Uhrzeiteingabe  
- Einfache Textausgabe ohne Speicher

### ✅ v0.110 – Lokale Speicherung & Darkmode
- `localStorage` für Fieberdaten  
- Darkmode-Toggle (fixiert, rund)  
- Responsives Design für Mobilgeräte

### ✅ v0.120 – Fieberfunktion
- Temperaturerfassung mit Verlauf  
- Warnung bei ≥39,5 °C  
- Grafische Darstellung im Canvas

### ✅ v0.130 – Export/Import
- JSON-basierte Speicherung  
- Datei-Export/-Import (inkl. Drag & Drop)  
- Kompaktes Format `[["timestamp", Temperatur], …]`

### ✅ v0.140 – Einnahmelogik (zeitlich frühere Substanz)
- Anzeige: „Nächste Einnahme = das Medikament mit kürzester Sperrzeit“  
- Nicht substanzabhängig, sondern nur nach Zeitvergleich

### ✅ v0.150 – Wechsellogik: Fokus auf *anderes* Medikament
- Wenn z. B. Paracetamol genommen → zeige: „Ibuprofen ab +3 h“  
- Immer Fokus auf Substanzwechsel, nicht Wiederholung  
- **„Alle Einnahmezeiten“** bleibt als transparente Übersicht erhalten
