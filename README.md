# Eykt

Zeiterfassung für Mac, iPhone und Apple Watch: Zeiten per Timer oder von Hand erfassen, nach Kunden,
Projekten und Aufgaben ordnen und als Bericht oder CSV ausgeben.

> *Eykt* ist ein altes isländisches Wort für eine **Tageszeit** – ein Achtel des Tages.

## Download

**[Neueste Version herunterladen](https://github.com/saerdna24/Eykt-releases/releases/latest)**

Laden Sie dort unter **Assets** die ZIP-Datei **`Eykt-…zip`** herunter. Die Einträge
„Source code“ fügt GitHub automatisch hinzu; sie enthalten nicht die App.

## Funktionen

- **Timer und manuelle Einträge** – mit Kunden, Projekten, Aufgaben, Tags und Stundensätzen
- **Schnelleingabe** – „2 h Projekt X gestern Nachmittag“ wird zum Eintrag, auch über Siri und Kurzbefehle
- **Automatische Erfassung** (optional) – Eykt merkt sich, mit welchen Programmen Sie arbeiten, und
  schlägt daraus Einträge zur Bestätigung vor
- **Berichte und Budgets** – gruppiert nach Kunde, Projekt, Tag, Woche oder Monat, mit Diagrammen,
  CSV-Export und vollständiger Sicherung
- **Synchronisierung** zwischen Mac und iPhone über Ihre eigene private iCloud oder einen eigenen
  WebDAV-Server, z. B. ein NAS – laufende Timer erscheinen auf dem anderen Gerät
- **Import aus Clockify**

Alles wird auf dem Gerät verarbeitet. Eykt hat keinen Server und keine Telemetrie.

## Voraussetzungen

- **macOS 26.4** (Tahoe) oder neuer
- Läuft auf **Intel-Macs** und **Macs mit Apple Silicon**
- Apple Intelligence und das eingebaute Llama-Modell für die Schnelleingabe und KI-Vorschläge benötigen
  Apple Silicon; auf Intel-Macs arbeitet die Schnelleingabe regelbasiert
- Ein **Zugangsschlüssel** (siehe unten)

## Installation

1. Die ZIP-Datei herunterladen und öffnen (Doppelklick entpackt sie).
2. **Eykt** in den Ordner **Programme** ziehen. Eine ältere Version dort ersetzen Sie einfach – Ihre
   Daten liegen nicht in der App und bleiben erhalten.
3. Eykt starten.

Die App ist von Apple beglaubigt (notarisiert) und öffnet sich ohne Warnhinweis. Für die automatische
Erfassung fragt Eykt einmal nach der Berechtigung für die Bedienungshilfen.

## Zugangsschlüssel

Eykt wird privat weitergegeben. Ihren Zugangsschlüssel – eine Zeile, die mit `NAU1-` beginnt – haben
Sie per E-Mail erhalten; es ist derselbe Schlüssel wie für Skjal und Minni. Fügen Sie ihn beim ersten
Start ein (die ganze E-Mail geht auch) und wählen Sie **Aktivieren**. Später finden Sie ihn unter
**Einstellungen ▸ Zugangsschlüssel**.

Ohne Schlüssel öffnet sich Eykt nur zum Lesen: Alles Vorhandene bleibt sichtbar, Berichte und Export
funktionieren, nichts geht verloren.

## Updates

Neue Versionen installiert Eykt selbst: **Eykt → Nach Updates suchen …** Die Updates sind signiert und
werden vor der Installation geprüft.

---

Dieses Repository enthält nur die fertigen Programmversionen und den Update-Feed, nicht den Quellcode.
