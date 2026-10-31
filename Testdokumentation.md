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
