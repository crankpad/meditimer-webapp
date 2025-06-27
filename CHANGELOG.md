# Changelog – Meditimer v0.184f

🗓 Version: 0.184f  
📅 Datum: 2025-06-26

## 🔐 Fehlerbehandlung verbessert

- ✅ Defekter `localStorage`-Eintrag (`feverData`) wird jetzt automatisch abgefangen
- ✅ Absturz durch `.map` auf `undefined` verhindert (`drawChart`)
- 🧼 Kein manuelles `localStorage.clear()` mehr nötig
- 🔧 Automatische Wiederherstellung bei ungültigem Speicherformat