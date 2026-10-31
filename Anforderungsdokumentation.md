<img width="1146" height="1102" alt="image" src="https://github.com/user-attachments/assets/9b4a91f5-cb00-48f1-a075-efccbfec4c9e" /># Anforderungsdokumentation

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
