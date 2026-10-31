# User Stories – Digitalisierung eines Bestellprozesses

## US-001 – Automatische Validierung der Bestelldaten

**User Story:**

Als Sachbearbeiterin möchte ich, dass Artikelnummern und Bestellmengen automatisch überprüft werden, damit ich Eingabefehler bei der Bestellerfassung vermeiden kann.

**Priorität:** Hoch

**Zugehörige Anforderung:** FR-001

### Akzeptanzkriterien

- AK-001: Eine gültige Artikelnummer und eine positive Bestellmenge werden als valide erkannt.
- AK-002: Bei einer unbekannten Artikelnummer zeigt das System eine Fehlermeldung an und verhindert das Speichern der Bestellung.
- AK-003: Bei einer Bestellmenge kleiner oder gleich null zeigt das System eine Fehlermeldung an und verhindert das Speichern der Bestellung.

**Status:** Offen

**Hinweis:** Beispielhafte User Story im Rahmen eines fiktiven Portfolio-Projekts.


## US-002 – Automatische Bestellbestätigung per E-Mail

**Als** Kunde

**möchte ich** nach erfolgreicher Bestellung automatisch eine Bestätigung per E-Mail erhalten,

**damit** ich sicher sein kann, dass meine Bestellung eingegangen ist.

### Zugehörige Dokumente

- **Change Request:** CR-001
- **Funktionale Anforderung:** FR-002
- **Status:** Entwurf – Noch nicht freigegeben

### Vorläufige Akzeptanzkriterien

- **AK-004:** Nach erfolgreicher Speicherung einer Bestellung wird der automatische Versand einer Bestellbestätigung ausgelöst.
- **AK-005:** Die Bestellbestätigung wird an die für die Bestellung hinterlegte E-Mail-Adresse adressiert.
- **AK-006:** Bei einem fehlgeschlagenen E-Mail-Versand wird der Fehler im System erfasst. Das weitere Vorgehen muss mit dem Auftraggeber abgestimmt werden.

### Offene Fragen

- Welche Informationen muss die Bestellbestätigung enthalten?
- Soll bei einem Versandfehler ein automatischer Wiederholungsversuch erfolgen?
- Wie wird der Kunde über einen dauerhaft fehlgeschlagenen Versand informiert?

**Hinweis:** Diese User Story wurde aus einem fiktiven Change Request abgeleitet und ist noch nicht freigegeben.
