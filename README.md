# Fokus

Kleine, installierbare Progressive Web App (PWA) gegen Aufschieberitis. Läuft komplett im Browser, keine Server-Komponente, keine Accounts.

Kein Therapie- oder Diagnose-Anspruch — ein Produktivitäts-/Coaching-Tool, das etablierte Verhaltenstechniken gegen Prokrastination nutzt: Aufgaben in einen winzigen ersten Schritt zerlegen, kurze Fokus-Sessions, sichtbarer Fortschritt. Fachlich orientiert an Rödel/Bathen-Gabriel/Rehfeld (Hrsg.), *Perfektionismus, Imposter-Phänomen und Prokrastination* (Springer Gabler, 2025) — insbesondere dem Rubikon-Modell der Handlungsphasen, der Handlungskontrolltheorie (Kuhl) und dem REVT/ABCDE-Ansatz gegen prokrastinationsfördernde Gedanken.

## Funktionen

- **Schnell-Erfassung**: eine Aufgabe anlegen braucht nur einen Namen — alles andere (Wichtigkeit, Widerstand, Fälligkeit, geplante Startzeit, Ritual, kleinster erster Schritt) ist optional und wird erst bei Bedarf über "Verfeinern" ergänzt. Eine hohe Eintragshürde ist selbst ein Prokrastinations-Trigger, deshalb bewusst kein Pflichtformular.
- **Rubikon-Phasen-Label** (Idee → Geplant → Dabei → Erledigt), automatisch aus vorhandenen Feldern abgeleitet, kein zusätzlicher Pflegeaufwand.
- **Priorisierung** aus Dringlichkeit, Wichtigkeit, "Widerstand" (wie sehr du eine Aufgabe vermeidest, bewusst getrennt von reiner Schwierigkeit) und wie lange eine Aufgabe schon liegen bleibt.
- **Gelegenheitsvorsatz**: geplante Startzeit + Start-Ritual pro Aufgabe (Implementation-Intentions-Prinzip).
- **Reframing-Hinweis** bei hohem Widerstand: kurzer, überspringbarer Denkanstoß nach dem ABCDE-Modell ("Was befürchtest du, wenn du jetzt anfängst? Ist das realistisch?").
- **Arbeitstagebuch**: protokolliert automatisch geplante vs. tatsächliche Startzeit.
- **Lokale Erinnerungen**: optionale Browser-Benachrichtigung, wenn eine geplante Startzeit erreicht ist — funktioniert nur, während die App offen oder kürzlich genutzt wurde (kein Server im Hintergrund, daher keine Erinnerung bei vollständig geschlossener App, v. a. auf iOS eingeschränkt).
- **5-Minuten-Fokus-Timer**, nicht wertende Sprache (kein Schuld-Framing bei unterbrochener Serie).
- **Streak-Sonne**: wächst und strahlt heller, je länger die tägliche Serie läuft (Gamification-Element, angelehnt an Duolingo-Streaks).
- **"Woran hat's gelegen?"**: freiwillige Ein-Tipp-Erfassung von Hindernissen (Zeitmangel, Ablenkung, Unklarheit, Überforderung …), macht eigene Vermeidungsmuster über Zeit im Arbeitstagebuch sichtbar.
- "Alle Aufgaben"-Bereich zum Anlegen/Bearbeiten/Löschen.

Nicht enthalten: echte Push-Benachrichtigungen bei geschlossener App (bräuchte einen Backend-Baustein), Cloud-Sync zwischen Geräten.

## Nutzung

`index.html` öffnen oder den Ordner statisch hosten (z. B. GitHub Pages). Als PWA "Zum Home-Bildschirm hinzufügen" für App-Gefühl inkl. Offline-Fähigkeit. Alle Daten bleiben lokal im Browser (`localStorage`).
