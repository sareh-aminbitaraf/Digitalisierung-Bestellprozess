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
