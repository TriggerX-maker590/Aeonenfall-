# Äonenfall v1.12.6 – iPhone-Web-App

Dieses Paket ist für einen **Single-Thread-Webexport mit Godot 4.7.1** vorbereitet. Dadurch benötigt Safari keine speziellen COOP/COEP-Serverheader.

## Auf dem Android-Handy veröffentlichen

1. Auf GitHub ein neues leeres Repository erstellen.
2. Dieses ZIP entpacken und **den Inhalt des Ordners** in das Repository hochladen.
3. Unter **Settings → Pages → Build and deployment → Source** den Eintrag **GitHub Actions** auswählen.
4. Den Reiter **Actions** öffnen und den Workflow **Äonenfall iPhone Web-App** starten.
5. Nach erfolgreichem Lauf steht die Internetadresse unter **Settings → Pages**.
6. Den Link an das iPhone senden.
7. Auf dem iPhone den Link in Safari öffnen, das Gerät quer drehen und über **Teilen → Zum Home-Bildschirm** installieren.

## Automatisches Ergebnis

- spielbare Godot-Webfassung mit `index.html`, `.js`, `.wasm` und `.pck`
- iPhone-Symbole, PWA-Manifest und Safe-Area-Anpassung
- Querformat-Hinweis und Touch-Fokus
- veröffentlichte GitHub-Pages-Adresse
- zusätzliches Download-ZIP unter **Actions → Artifacts**

## Hinweise

- Der erste Start kann wegen der großen Spieldatei länger dauern.
- Ton wird auf iPhone erst nach einer Berührung freigeschaltet.
- Spielstände liegen lokal im Browser des jeweiligen iPhones.
