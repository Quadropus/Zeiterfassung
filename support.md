---
title: Support
---

# Support für {{ site.app_name }}

Fragen, Fehler oder Wünsche? Schreib eine E-Mail an **{{ site.kontakt_email }}**. Hilfreich sind dabei: Gerät (iPhone, iPad oder Mac), Systemversion und eine kurze Beschreibung, was du getan hast und was passiert ist.

## Voraussetzungen

- iPhone und iPad ab iOS bzw. iPadOS 18
- Mac ab macOS 14
- Für den Abgleich zwischen Geräten: auf allen Geräten mit derselben Apple-ID bei iCloud angemeldet

## Häufige Fragen

### Wie kommen meine Daten auf meine anderen Geräte?

Automatisch über deine private iCloud, wenn du auf allen Geräten mit derselben Apple-ID bei iCloud angemeldet bist. Der Abgleich kann ein paar Sekunden bis Minuten dauern. Ohne iCloud funktioniert die App genauso, die Daten bleiben dann auf dem jeweiligen Gerät.

### Wie sichere ich meine Daten?

In den Einstellungen unter *Sicherung → Sicherung exportieren …*. Die Datei enthält alle Profile und lässt sich auf jedem Gerät über *Sicherung einlesen …* wieder einspielen. Vor dem Einlesen einer Sicherung, vor einem CSV-Import und vor dem Löschen eines Profils legt die App außerdem selbst eine Sicherung an.

### Kann ich meine Zeiten in Excel oder Numbers weiterverarbeiten?

Ja: In den Einstellungen unter *CSV → CSV exportieren …* (auf dem Mac auch über *Ablage*). Exportiert wird der im Kalender gewählte Zeitraum, eine Zeile je Block, mit Semikolon als Trennzeichen und Dezimalkomma.

### Welches Format braucht der CSV-Import?

Eine Kopfzeile mit den Spalten `Date`, `Start` und `End`, darunter eine Zeile je Block, zum Beispiel:

```
Date;Start;End
2026-10-19;07:30;12:00
2026-10-19;12:30;16:15
```

Als Trennzeichen gehen Semikolon, Komma oder Tabulator. Vor dem Import zeigt die App, wie viele Blöcke hinzukommen; bereits vorhandene Blöcke werden übersprungen.

### Wie wird die Pause berechnet?

In den Einstellungen unter *Pausen* wählst du die Regel: Entweder zählen die Lücken zwischen deinen Blöcken als Pause, oder die App zieht die gesetzliche Mindestpause nach § 4 Arbeitszeitgesetz ab (mehr als 6 Stunden: 30 Minuten, mehr als 9 Stunden: 45 Minuten), soweit du sie nicht schon gemacht hast.

### Stimmen die Feiertage für mein Bundesland?

Wähle in den Einstellungen unter *Kalenderdaten* dein Bundesland. Feiertage, die nur in einem Teil des Landes gelten, lassen sich dort einzeln einschalten. Feiertage senken das Soll, Schulferien werden nur angezeigt.

### Ich arbeite für mehrere Arbeitgeber. Geht das?

Ja, mit Profilen: In den Einstellungen unter *Profil* ein neues Profil anlegen. Jedes Profil hat eigene Zeiten und Einstellungen. Wechseln kannst du über den Titel oben in der App.

## Datenschutz

Siehe [Datenschutzerklärung](datenschutz).
