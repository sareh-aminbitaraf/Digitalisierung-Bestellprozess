# Testdokumentation – Digitalisierung eines Bestellprozesses

## TC-001 – Prüfung einer ungültigen Bestellmenge

**Testziel:**
Überprüfen, ob das System negative Bestellmengen ablehnt.

**Zugehörige Anforderung:** FR-001

**Zugehörige User Story:** US-001

**Vorbedingung:**
Das Bestellformular ist geöffnet.

**Testdaten:**
- Artikelnummer: ART-1001 (angenommene gültige Artikelnummer)
- Bestellmenge: -5

**Testschritte:**
1. Eine gültige Artikelnummer eingeben.
2. Die Bestellmenge -5 eingeben.
3. Auf „Speichern“ klicken.

**Erwartetes Ergebnis:**
Das System zeigt eine Fehlermeldung an und verhindert das Speichern der Bestellung.

**Tatsächliches Ergebnis:** Noch nicht ermittelt.

**Teststatus:** Nicht ausgeführt

**Hinweis:** Dieser Testfall wurde für ein fiktives Portfolio-Projekt erstellt. Es wurde noch kein realer Softwaretest durchgeführt.

## TC-002 – Prüfung gültiger Bestelldaten

**Zugehörige Anforderung:** FR-001

**Zugehörige User Story:** US-001

**Akzeptanzkriterium:** AK-001

**Testdaten:** Artikelnummer ART-1001 (angenommen gültig), Bestellmenge 5

**Testschritte:**
1. Bestellformular öffnen.
2. Gültige Artikelnummer eingeben.
3. Bestellmenge 5 eingeben.
4. Auf „Speichern“ klicken.

**Erwartetes Ergebnis:** Die Eingaben werden als gültig erkannt und nicht aufgrund der Eingabevalidierung abgelehnt.

**Status:** Nicht ausgeführt

---

## TC-003 – Prüfung einer unbekannten Artikelnummer

**Zugehörige Anforderung:** FR-001

**Zugehörige User Story:** US-001

**Akzeptanzkriterium:** AK-002

**Testdaten:** Artikelnummer INVALID-999, Bestellmenge 5

**Testschritte:**
1. Bestellformular öffnen.
2. Unbekannte Artikelnummer eingeben.
3. Bestellmenge 5 eingeben.
4. Auf „Speichern“ klicken.

**Erwartetes Ergebnis:** Das System zeigt eine Fehlermeldung an und verhindert das Speichern der Bestellung.

**Status:** Nicht ausgeführt

---

## TC-004 – Prüfung einer Bestellmenge von null

**Zugehörige Anforderung:** FR-001

**Zugehörige User Story:** US-001

**Akzeptanzkriterium:** AK-003

**Testdaten:** Artikelnummer ART-1001 (angenommen gültig), Bestellmenge 0

**Testschritte:**
1. Bestellformular öffnen.
2. Gültige Artikelnummer eingeben.
3. Bestellmenge 0 eingeben.
4. Auf „Speichern“ klicken.

**Erwartetes Ergebnis:** Das System zeigt eine Fehlermeldung an und verhindert das Speichern der Bestellung.

**Status:** Nicht ausgeführt


## TC-005 – Prüfung der Antwortzeit bei der Bestellvalidierung

**Zugehörige Anforderung:** NFR-001

**Testart:** Performance-Test

**Testziel:** Überprüfung, ob mindestens 95 % der Validierungsanfragen innerhalb von maximal 2 Sekunden beantwortet werden.

**Testvoraussetzung:** Eine funktionsfähige Testumgebung mit implementierter Bestellvalidierung ist verfügbar.

**Testdaten:** 200 Validierungsanfragen mit definierten Eingabedaten.

**Testschritte:**
1. Testumgebung vorbereiten.
2. 200 Validierungsanfragen ausführen.
3. Antwortzeit jeder Anfrage messen.
4. Anzahl der Anfragen mit einer Antwortzeit von maximal 2 Sekunden ermitteln.
5. Anteil der rechtzeitig beantworteten Anfragen berechnen.
6. Ergebnis mit dem Grenzwert von 95 % vergleichen.

**Erwartetes Ergebnis:** Mindestens 190 von 200 Anfragen werden innerhalb von maximal 2 Sekunden beantwortet.

**Bestanden-Kriterium:** Anteil rechtzeitig beantworteter Anfragen >= 95 %.

**Status:** Nicht ausgeführt

**Hinweis:** Dieser Testfall wurde im Rahmen eines fiktiven Praxisprojekts konzipiert. Eine tatsächliche Testdurchführung hat nicht stattgefunden.


## TC-006 – Automatischer Versand einer Bestellbestätigung

**Zugehöriger Change Request:** CR-001

**Zugehörige Anforderung:** FR-002

**Zugehörige User Story:** US-002

**Akzeptanzkriterien:** AK-004, AK-005 (vorläufig)

**Testart:** Funktionaler Test

**Status:** Entwurf – Nicht ausgeführt, noch nicht freigegeben

### Testziel

Überprüfen, ob nach erfolgreicher Speicherung einer Bestellung automatisch eine Bestellbestätigung an die hinterlegte E-Mail-Adresse versendet wird.

### Testvoraussetzungen

- Eine funktionsfähige Testumgebung ist verfügbar.
- Der automatische E-Mail-Versand ist implementiert.
- Eine gültige Test-E-Mail-Adresse ist hinterlegt.

### Testdaten

- Artikelnummer: ART-1001 (angenommen gültig)
- Bestellmenge: 5
- E-Mail-Adresse: kunde@example.com

### Testschritte

1. Bestellformular öffnen.
2. Gültige Bestelldaten eingeben.
3. Test-E-Mail-Adresse hinterlegen.
4. Bestellung erfolgreich speichern.
5. Prüfen, ob der automatische E-Mail-Versand ausgelöst wird.
6. Prüfen, ob die Bestellbestätigung an die hinterlegte E-Mail-Adresse adressiert ist.

### Erwartetes Ergebnis

- Nach erfolgreicher Speicherung wird der E-Mail-Versand automatisch ausgelöst.
- Die Bestellbestätigung wird an die hinterlegte E-Mail-Adresse adressiert.

### Offene Punkte

- Der Inhalt der Bestellbestätigung muss noch abgestimmt werden.
- Der Umgang mit Versandfehlern wird in diesem Testfall nicht geprüft.
- Die Akzeptanzkriterien müssen vor einer verbindlichen Testdurchführung freigegeben werden.

**Hinweis:** Dieser Testfall wurde für einen fiktiven, noch nicht freigegebenen Change Request konzipiert. Eine tatsächliche Testdurchführung hat nicht stattgefunden.

## TC-007 – Fehler beim Versand der Bestellbestätigung

**Zugehöriger Change Request:** CR-001

**Zugehörige Anforderung:** FR-002

**Zugehörige User Story:** US-002

**Akzeptanzkriterium:** AK-006 (vorläufig)

**Testart:** Negativer funktionaler Test

**Status:** Entwurf – Nicht ausgeführt, noch nicht freigegeben

### Testziel

Überprüfen, ob ein fehlgeschlagener Versand der Bestellbestätigung im System als Fehler erfasst wird.

### Testvoraussetzungen

- Eine funktionsfähige Testumgebung ist verfügbar.
- Die Bestellung kann erfolgreich gespeichert werden.
- Der automatische E-Mail-Versand ist implementiert.
- Ein Versandfehler kann in der Testumgebung gezielt simuliert werden.

### Testdaten

- Artikelnummer: ART-1001 (angenommen gültig)
- Bestellmenge: 5
- E-Mail-Adresse: kunde@example.com
- Simulierter Fehler: E-Mail-Dienst nicht erreichbar

### Testschritte

1. Testumgebung vorbereiten.
2. Einen Ausfall des E-Mail-Dienstes simulieren.
3. Eine Bestellung mit gültigen Daten erfassen.
4. Bestellung erfolgreich speichern.
5. Den automatischen E-Mail-Versand auslösen lassen.
6. Prüfen, ob der Versandfehler im System erfasst wird.

### Erwartetes Ergebnis

- Der E-Mail-Versand schlägt aufgrund des simulierten Dienstausfalls fehl.
- Der Versandfehler wird im System erfasst.

### Offene Punkte

- Soll das System den Versand automatisch wiederholen?
- Soll ein Administrator über den Fehler informiert werden?
- Wie soll der Kunde bei dauerhaft fehlgeschlagenem Versand informiert werden?
- Welche Auswirkungen hat der Versandfehler auf den Bestellstatus?

**Hinweis:** Der Testfall basiert auf dem vorläufigen Akzeptanzkriterium AK-006. Das weitere Fehlerbehandlungsverhalten ist noch mit dem Auftraggeber abzustimmen. Der Test wurde nicht ausgeführt.
