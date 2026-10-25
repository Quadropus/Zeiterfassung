# Webseite für Datenschutz und Support

Zwei Seiten, die App Store Connect als URL verlangt, als GitHub-Pages-Seite.

## Veröffentlichen

1. Platzhalter in `_config.yml` ausfüllen: App-Name, Name des Verantwortlichen, Kontakt-E-Mail, Datum.
2. Auf GitHub ein **neues, öffentliches** Repository anlegen, z. B. `zeiterfassung-app` (das eigentliche Projekt bleibt privat).
3. Die Dateien dieses Ordners hineinlegen (ohne diese README, wenn du sie nicht zeigen willst) und hochladen.
4. Im Repository *Settings → Pages → Build and deployment*: Quelle *Deploy from a branch*, Branch `main`, Ordner `/ (root)` → *Save*.
5. Nach ein bis zwei Minuten sind die Seiten erreichbar:
   - Datenschutz: `https://BENUTZERNAME.github.io/zeiterfassung-app/datenschutz`
   - Support: `https://BENUTZERNAME.github.io/zeiterfassung-app/support`
6. Beide Adressen in App Store Connect eintragen (*App-Informationen → Datenschutzrichtlinie-URL* und *Version → Support-URL*).

## Impressum

Wird die App gewerblich angeboten, braucht die Seite in Deutschland in der Regel ein Impressum (§ 5 Digitale-Dienste-Gesetz: Name, ladungsfähige Anschrift, E-Mail). Dann eine Datei `impressum.md` ergänzen und in `index.md` verlinken. Bei einer rein privaten, kostenlosen App ist das meist nicht nötig; im Zweifel rechtlich prüfen lassen.

## Pflegen

Ändert sich am Umgang mit Daten etwas (z. B. ein neuer Dienst), `datenschutz.md` anpassen und `stand` in `_config.yml` aktualisieren.
