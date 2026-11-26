# GymTrack – Releases

Dieses Repository enthält **keinen Quellcode**. Hier werden nur die fertigen, signierten Android-APKs
von **GymTrack** veröffentlicht, einem privaten, werbefreien Tracker für Krafttraining, Ernährung,
Schritte und Wasser. Alle Daten bleiben auf dem Handy: kein Konto, keine Cloud, keine Werbung.

Alle Versionen findest du unter [Releases](https://github.com/Warnage/gym-tracker-releases/releases).

**Inhalt:** [Voraussetzungen](#voraussetzungen) ·
[1. Automatische Sperre aus](#1-samsung-automatische-sperre-kurz-ausschalten) ·
[2. Obtainium](#2-obtainium-installieren) ·
[3. GymTrack](#3-gymtrack-über-obtainium-installieren) ·
[4. Automatische Sperre an](#4-automatische-sperre-wieder-einschalten) ·
[Updates](#updates) · [Nach der Installation](#nach-der-installation) ·
[Daten sichern](#daten-sichern) · [Probleme](#probleme)

---

## Voraussetzungen

- Android-Handy mit **Android 8 oder neuer** und **64-Bit-Prozessor** (praktisch alle Handys ab etwa 2017).
  Sehr alte oder sehr günstige Geräte mit 32-Bit-Android werden nicht unterstützt.
- Etwa 10 Minuten für die erste Einrichtung. Updates gehen danach mit wenigen Fingertipps.

Installiert wird mit [Obtainium](https://github.com/ImranR98/Obtainium). Die App holt Updates direkt
aus diesem Repo, ganz ohne Play Store, und meldet sich, sobald es eine neue Version gibt.

> Die Bezeichnungen in den Einstellungen unterscheiden sich je nach Hersteller und Android-Version
> etwas. Die Schritte unten beziehen sich auf Samsung Galaxy (One UI); auf anderen Handys heißen die
> Menüs ähnlich.

## 1. Samsung: Automatische Sperre kurz ausschalten

Neuere Samsung-Handys haben die **Automatische Sperre** (englisch *Auto Blocker*). Sie blockiert alle
Apps, die nicht aus dem Play Store oder dem Galaxy Store kommen, also auch Obtainium und GymTrack.
Für die Installation muss sie kurz aus sein.

1. **Einstellungen** öffnen → **Sicherheit und Datenschutz** → **Automatische Sperre**.
2. Den Schalter **ausschalten**.

Nach der Installation schaltest du sie in [Schritt 4](#4-automatische-sperre-wieder-einschalten)
wieder ein. Ohne Samsung-Handy oder wenn es den Punkt nicht gibt: diesen Schritt überspringen.

## 2. Obtainium installieren

1. Auf dem Handy im Browser die
   [Obtainium-Releases](https://github.com/ImranR98/Obtainium/releases/latest) öffnen.
2. Unter **Assets** die APK für 64-Bit-Handys herunterladen (die Datei mit **`arm64-v8a`** im Namen).
3. Die heruntergeladene Datei öffnen (Benachrichtigung „Download abgeschlossen“ oder die App
   *Eigene Dateien* → *Downloads*).
4. Android meldet, dass der Browser keine Apps installieren darf: **Einstellungen** tippen →
   **„Aus dieser Quelle zulassen“** einschalten → zurück.
5. **Installieren** tippen.
6. Falls **Google Play Protect** warnt („App nicht geprüft“ o. Ä.): **Weitere Details** →
   **Trotzdem installieren**.
7. Obtainium öffnen und **Benachrichtigungen** erlauben, damit es Updates melden kann.

## 3. GymTrack über Obtainium installieren

1. In Obtainium unten auf **„App hinzufügen“** tippen.
2. Ins Feld **App-Quell-URL** diese Adresse eintragen:
   ```
   https://github.com/Warnage/gym-tracker-releases
   ```
3. **Hinzufügen** tippen. Obtainium findet die neueste Version.
4. **Installieren** tippen.
5. Beim ersten Mal fragt Android, ob Obtainium Apps installieren darf: **Einstellungen** →
   **„Aus dieser Quelle zulassen“** einschalten → zurück → **Installieren**.
6. Falls Play Protect warnt: wie oben **Weitere Details** → **Trotzdem installieren**.

GymTrack ist jetzt installiert und erscheint bei deinen Apps.

## 4. Automatische Sperre wieder einschalten

**Einstellungen** → **Sicherheit und Datenschutz** → **Automatische Sperre** → wieder **einschalten**.

Installierte Apps laufen damit ganz normal weiter. Nur für **Updates** musst du die Sperre jeweils kurz
ausschalten (siehe unten).

---

## Updates

Obtainium prüft regelmäßig, ob es eine neue Version gibt, und zeigt dann eine Benachrichtigung.

1. Samsung: **Automatische Sperre ausschalten** (wie in [Schritt 1](#1-samsung-automatische-sperre-kurz-ausschalten)).
   Solange sie an ist, blockiert Android auch Updates von Apps außerhalb der Stores.
2. Obtainium öffnen → bei GymTrack **Aktualisieren** tippen (oder **Alle aktualisieren**) → **Installieren**.
3. Samsung: **Automatische Sperre wieder einschalten**.

Deine Daten bleiben bei Updates erhalten, weil alle Versionen mit demselben Schlüssel signiert sind.
**Die App vor einem Update nie deinstallieren.** Beim Deinstallieren löscht Android alle Daten der App.

Ohne Obtainium geht es auch manuell: die neueste `.apk` unter
[Releases](https://github.com/Warnage/gym-tracker-releases/releases) herunterladen und öffnen
(Automatische Sperre dafür ebenfalls kurz aus).

## Nach der Installation

- **Benachrichtigungen:** Beim ersten abgehakten Satz fragt Android danach. Bitte erlauben, sonst meldet
  der Pausentimer das Ende der Pause nicht. Erinnerungen (z. B. Wasser, Ernährung) brauchen sie ebenfalls.
- **Profil:** Unter *Mehr → Profil* Geschlecht, Geburtsjahr und Größe eintragen und unter
  *Mehr → Körpermaße* dein Gewicht. Daraus berechnet GymTrack deinen Kalorienverbrauch und dein
  Kalorienziel. Ziele stellst du unter *Mehr → Ziele* ein.
- **Schritte (optional):** *Mehr → Einstellungen → Schritte → Schritte aus Health Connect* einschalten und
  den Zugriff erlauben. Die Schritte kommen aus Health Connect (z. B. von Samsung Health); GymTrack liest
  nur die Schrittzahl pro Tag.
- **Mit Gemini schätzen (optional):** Beim Hinzufügen von Essen öffnet das Funkeln-Symbol die Gemini-App
  mit einer fertigen Frage nach den Nährwerten. Die Antwort kopierst du und fügst sie in GymTrack ein.
  GymTrack selbst sendet dabei nichts ins Internet.

## Daten sichern

Alle Daten liegen nur auf deinem Handy. Leg ab und zu ein Backup an, vor allem vor einem Handywechsel:

*Mehr → Einstellungen → Daten & Backup → Backup exportieren* und die Datei z. B. in deiner Cloud oder auf
dem PC ablegen. Auf einem neuen Handy GymTrack installieren und dort *Backup importieren* wählen.

## Probleme

| Meldung / Problem | Lösung |
|---|---|
| Installation oder Update wird blockiert | Samsung: Automatische Sperre kurz ausschalten ([Schritt 1](#1-samsung-automatische-sperre-kurz-ausschalten)). |
| „App nicht installiert“ beim Update | Meist ist eine Version mit anderem Schlüssel installiert. **Nicht einfach deinstallieren**, sonst sind die Daten weg: erst ein Backup exportieren, dann deinstallieren, neu installieren und das Backup importieren. |
| „Das Paket scheint ungültig zu sein“ | Das Handy hat vermutlich ein 32-Bit-Android und wird nicht unterstützt. |
| Obtainium meldet keine Updates | In Obtainium nach unten ziehen, um nach Updates zu suchen. Benachrichtigungen für Obtainium erlauben und den Energiesparmodus für Obtainium ausschalten (*Einstellungen → Apps → Obtainium → Akku → Nicht eingeschränkt*). |
