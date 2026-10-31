# Requirements Traceability Matrix

## 1. Ziel

Diese Matrix dokumentiert die Nachverfolgbarkeit zwischen Anforderungen, User Stories, Akzeptanzkriterien und Testfällen im fiktiven Projekt zur Digitalisierung eines Bestellprozesses.

## 2. Traceability Matrix

| Anforderung | User Story | Akzeptanzkriterium | Testfall | Status |
|---|---|---|---|---|
| FR-001 | US-001 | AK-001 | TC-002 | Dokumentiert, nicht ausgeführt |
| FR-001 | US-001 | AK-002 | TC-003 | Dokumentiert, nicht ausgeführt |
| FR-001 | US-001 | AK-003 | TC-001, TC-004 | Dokumentiert, nicht ausgeführt |
| NFR-001 | Noch nicht definiert | AK-NFR-001 | TC-005 | Dokumentiert, nicht ausgeführt |

## 3. Testabdeckung

Für FR-001 sind alle drei dokumentierten Akzeptanzkriterien durch mindestens einen Testfall abgedeckt.

- AK-001: TC-002 – Gültige Bestelldaten
- AK-002: TC-003 – Unbekannte Artikelnummer
- AK-003: TC-001 – Negative Bestellmenge; TC-004 – Bestellmenge null

Für NFR-001 wurde der Performance-Testfall TC-005 definiert. Die Testdurchführung steht noch aus.

## 4. Hinweis

Die Testabdeckung bezieht sich ausschließlich auf die dokumentierten Testszenarien. Die Testfälle wurden konzipiert, aber nicht ausgeführt. Eine produktive Implementierung wurde nicht durchgeführt.

## 5. Nachverfolgbarkeit des Change Requests CR-001

Die folgende Übersicht zeigt die Beziehungen zwischen dem Change Request, der daraus abgeleiteten funktionalen Anforderung und der zugehörigen User Story.

| Change Request | Anforderung | User Story | Akzeptanzkriterien | Testfälle | Status |
|---|---|---|---|---|---|
| Change Request | Anforderung | User Story | Akzeptanzkriterium | Testfall | Status |
|---|---|---|---|---|---|
| CR-001 | FR-002 | US-002 | AK-004 | TC-006 | Entwurf – Nicht ausgeführt |
| CR-001 | FR-002 | US-002 | AK-005 | TC-006 | Entwurf – Nicht ausgeführt |
| CR-001 | FR-002 | US-002 | AK-006 | TC-007 | Entwurf – Nicht ausgeführt |

### Offene Punkte

- Für alle drei vorläufigen Akzeptanzkriterien wurden Testfälle konzipiert.
- Die Testfälle TC-006 und TC-007 wurden noch nicht ausgeführt.
- Die Akzeptanzkriterien müssen mit dem Auftraggeber abgestimmt werden.
- Das weitere Vorgehen bei fehlgeschlagenem E-Mail-Versand ist noch zu klären.
- Der Change Request CR-001 wurde noch nicht freigegeben.

**Hinweis:** Die Verknüpfungen dokumentieren einen fiktiven Änderungsvorschlag. Eine Freigabe oder Umsetzung ist nicht erfolgt.

