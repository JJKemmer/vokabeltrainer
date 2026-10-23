# Vokabeltrainer: Einrichtung

## 1. App auf GitHub (nur das Programm, ohne Vokabeln)
1. Auf github.com ein neues Repository anlegen, z. B. `vokabeltrainer`, Sichtbarkeit „Public“.
2. „uploading an existing file“ → alle Dateien aus diesem Ordner hochladen → „Commit changes“.
3. Settings → Pages → Branch „main“, „/ (root)“ → Save.
4. Nach 1–2 Minuten: https://jjkemmer.github.io/vokabeltrainer/

## 2. Auf dem Handy installieren
- iPhone: Adresse in Safari öffnen → Teilen → „Zum Home-Bildschirm“.
- Android: Adresse in Chrome öffnen → Menü → „App installieren“.

## 3. Vokabeln laden
Die Vokabeldatei (z. B. `glosario-vokabeln.json`) gehört NICHT auf GitHub.
Speichere sie privat (iCloud Drive, Google Drive, Dateien-App) und tippe in der App auf „Vokabeldatei laden“.
Die Vokabeln liegen danach nur auf dem Handy und funktionieren offline.

Eigene Listen gehen auch als CSV (z. B. aus Excel):
Wort;Übersetzung;Beispielsatz;Übersetzung des Beispielsatzes

## 4. Lernstand aus der alten Glosario-App übernehmen
1. Alte App: „Lernstand sichern & übertragen“ → „Code kopieren“.
2. Neue App: erst die Vokabeldatei laden, dann „Lernstand sichern & übertragen“ → Code einfügen → „Code übernehmen“.

## 5. Updates
Geänderte Dateien hochladen und in `sw.js` die VERSION erhöhen (v1 → v2 …).
