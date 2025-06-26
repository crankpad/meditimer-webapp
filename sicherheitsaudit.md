# Sicherheits- und Datenschutz-Audit: Meditimer WebApp

## Zweck
Diese Datei dokumentiert die Maßnahmen zur Sicherstellung von Datenschutz, Offline-Fähigkeit und Netzunabhängigkeit der Meditimer WebApp.

---

## 1. Offline-Fähigkeit

- ✅ Die App funktioniert vollständig ohne Internetverbindung.
- ✅ Keine Abhängigkeiten von Servern, APIs oder Cloud-Diensten.
- ✅ Datenhaltung erfolgt ausschließlich im Browser (`localStorage`).
- ✅ Die App kann direkt als `index.html` vom Dateisystem gestartet werden.

---

## 2. Netzverhalten

- ✅ Es finden keine `fetch`- oder `XMLHttpRequest`-Aufrufe statt.
- ✅ Keine eingebundenen externen Skripte, Frameworks oder Fonts.
- ✅ Kein Tracking, keine Werbung, keine Analytics.
- ✅ Keine Datenübertragung an Dritte.

---

## 3. Datenschutz

- ✅ Die App speichert ausschließlich Temperaturverläufe lokal im Browser (`localStorage`).
- ✅ Es werden keine personenbezogenen Daten erfasst, verarbeitet oder übermittelt.
- ✅ Die Daten bleiben auf dem jeweiligen Gerät und sind ausschließlich für die Nutzerin/den Nutzer sichtbar.
- ✅ Export-/Importfunktion geschieht manuell und lokal (kein Upload).

---

## 4. Plattformen

- ✅ Die App funktioniert auf allen modernen Browsern (Chrome, Firefox, Safari, Edge).
- ✅ Mobilgeräte: voll funktionsfähig im Offline-Modus.
- ✅ GitHub Pages-Betrieb ist möglich: Nur der initiale HTML-Abruf erfordert Internet.

---

## 5. Empfehlung

Diese App ist datenschutzfreundlich und kann bedenkenlos:
- lokal auf Endgeräten gespeichert werden
- per USB weitergegeben werden
- im familiären oder pflegerischen Umfeld genutzt werden

---

## Dateiname

`sicherheitsaudit.md`
