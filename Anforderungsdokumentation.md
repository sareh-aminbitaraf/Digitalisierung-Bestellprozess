## 1. Funktionale Anforderungen

### FR-001 – Validierung der Bestelldaten

**Beschreibung:**
Bei mindestens 95 % der Validierungsanfragen muss das System innerhalb von 2 Sekunden eine Rückmeldung anzeigen.

**Ziel:**
Reduzierung von Eingabefehlern bei der Bestellerfassung.

**Priorität:** Hoch

**Akzeptanzkriterien:**

- AK-001: Bei gültiger Artikelnummer und positiver Bestellmenge gelten diese Eingaben als valide.
- AK-002: Bei einer unbekannten Artikelnummer zeigt das System eine Fehlermeldung an und verhindert das Speichern der Bestellung.
- AK-003: Bei einer Bestellmenge kleiner oder gleich null zeigt das System eine Fehlermeldung an und verhindert das Speichern der Bestellung.

## 2. Nicht-funktionale Anforderungen

### NFR-001 – Antwortzeit bei der Bestellvalidierung

**Beschreibung:**
Das System muss bei der Validierung der Bestelldaten innerhalb von maximal 2 Sekunden eine Rückmeldung anzeigen.

**Ziel:**
Sicherstellung einer schnellen und effizienten Bestellerfassung.

**Priorität:** Mittel

**Akzeptanzkriterium:**

- AK-NFR-001: Bei 95 % der Validierungsanfragen muss die Rückmeldung innerhalb von 2 Sekunden erfolgen.

**Hinweis:** Die Zeitvorgaben sind beispielhafte Annahmen für dieses Portfolio-Projekt.



## FR-002 – Automatischer Versand einer Bestellbestätigung per E-Mail

**Typ:** Funktionale Anforderung

**Quelle:** Change Request CR-001

**Priorität:** Mittel (Vorschlag)

**Status:** Entwurf – Noch nicht freigegeben

### Beschreibung

Das System soll nach erfolgreicher Speicherung einer Bestellung automatisch eine Bestellbestätigung per E-Mail an den Kunden versenden.

### Vorläufige Akzeptanzkriterien

- **AK-004:** Nach erfolgreicher Speicherung einer Bestellung wird der automatische Versand einer Bestellbestätigung ausgelöst.
- **AK-005:** Die Bestellbestätigung wird an die für die Bestellung hinterlegte E-Mail-Adresse adressiert.
- **AK-006:** Bei einem fehlgeschlagenen E-Mail-Versand wird der Fehler im System erfasst. Das weitere Vorgehen muss mit dem Auftraggeber abgestimmt werden.

### Offene Fragen

1. Welche Informationen muss die Bestellbestätigung enthalten?
2. Soll bei einem Versandfehler automatisch ein erneuter Versand versucht werden?
3. Wie soll der Kunde bei einem dauerhaft fehlgeschlagenen Versand informiert werden?
4. Welche Anforderungen gelten für die Prüfung der E-Mail-Adresse?

### Hinweis

Diese Anforderung wurde aus dem fiktiven Change Request CR-001 abgeleitet. Die Akzeptanzkriterien sind vorläufig und müssen vor einer Umsetzung mit dem Auftraggeber abgestimmt werden.
