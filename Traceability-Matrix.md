# Requirements Traceability Matrix

## 1. Ziel

Diese Matrix dokumentiert die Nachverfolgbarkeit zwischen Anforderungen, User Stories, Akzeptanzkriterien und Testfällen im fiktiven Projekt zur Digitalisierung eines Bestellprozesses.

## 2. Traceability Matrix

| Anforderung | User Story | Akzeptanzkriterium | Testfall | Status |
|---|---|---|---|---|
| FR-001 | US-001 | AK-001 | TC-002 | Dokumentiert, nicht ausgeführt |
| FR-001 | US-001 | AK-002 | TC-003 | Dokumentiert, nicht ausgeführt |
| FR-001 | US-001 | AK-003 | TC-001, TC-004 | Dokumentiert, nicht ausgeführt |
| NFR-001 | Noch nicht definiert | AK-NFR-001 | Noch nicht definiert | Testfall offen |

## 3. Testabdeckung

Für FR-001 sind alle drei dokumentierten Akzeptanzkriterien durch mindestens einen Testfall abgedeckt.

- AK-001: TC-002 – Gültige Bestelldaten
- AK-002: TC-003 – Unbekannte Artikelnummer
- AK-003: TC-001 – Negative Bestellmenge; TC-004 – Bestellmenge null

Für NFR-001 muss noch ein Performance-Testfall definiert werden.

## 4. Hinweis

Die Testabdeckung bezieht sich ausschließlich auf die dokumentierten Testszenarien. Die Testfälle wurden konzipiert, aber nicht ausgeführt. Eine produktive Implementierung wurde nicht durchgeführt.
