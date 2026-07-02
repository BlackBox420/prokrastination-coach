# Fokus

Kleine, installierbare Progressive Web App (PWA) gegen Aufschieberitis. Läuft komplett im Browser, keine Server-Komponente, keine Accounts.

Kein Therapie- oder Diagnose-Anspruch — ein Produktivitäts-/Coaching-Tool, das etablierte Verhaltenstechniken gegen Prokrastination nutzt: Aufgaben in einen winzigen ersten Schritt zerlegen, kurze Fokus-Sessions, sichtbarer Fortschritt.

## Funktionen (MVP)

- Eigene Aufgaben anlegen: Name, optionale Fälligkeit, Wichtigkeit (1–5), Widerstand (1–5 — wie sehr du die Aufgabe vermeidest, bewusst getrennt von reiner Schwierigkeit)
- Priorisierung aus Dringlichkeit, Wichtigkeit, Widerstand und "Staleness" (wie lange eine Aufgabe schon liegen bleibt)
- "Heute"-Ansicht: die aktuell wichtigste Aufgabe, mit Vorschlag für den kleinsten ersten Schritt und einem 5-Minuten-Fokus-Timer
- Tages-Streak für aktiv bearbeitete Aufgaben
- Verwalten-Bereich zum Anlegen/Bearbeiten/Löschen von Aufgaben

Nicht enthalten in dieser ersten Testversion: Stimmungs-Tagebuch, Push-Benachrichtigungen, Cloud-Sync zwischen Geräten.

## Nutzung

`index.html` öffnen oder den Ordner statisch hosten (z.B. GitHub Pages). Als PWA "Zum Home-Bildschirm hinzufügen" für App-Gefühl inkl. Offline-Fähigkeit. Alle Daten bleiben lokal im Browser (`localStorage`).
