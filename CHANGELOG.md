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

### ✅ v0.160 – Finalisierung & Interface-Tuning
- Darkmode-Toggle nach oben rechts verschoben (mobile-friendly)
- Footer mit MIT-Lizenz-Hinweis & rotem medizinischen Haftungsausschluss
- Kompletter Code technisch und rechtlich geprüft

### ✅ v0.170 – Zeitkonsistenz bei Folgeaktionen

- Einheitlicher Zeitstempel für Fiebermessung und direkt folgende Medikamenteneinnahme
- Einführung von `currentTimestamp`, um aufeinanderfolgende Eingaben zeitlich zu koppeln
- Fehlerkorrektur: doppelte Date-Initialisierung in `logFever()` entfernt
- Technischer und visueller Endabgleich durchgeführt
