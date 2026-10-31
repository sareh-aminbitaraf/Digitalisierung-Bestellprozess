# Anforderungsdokumentation

## 1. Funktionale Anforderungen

### FR-001 – Validierung der Bestelldaten

**Beschreibung:**
Das System muss bei der Erfassung einer Bestellung prüfen, ob die eingegebene Artikelnummer existiert und die Bestellmenge größer als null ist.

**Ziel:**
Reduzierung von Eingabefehlern bei der Bestellerfassung.

**Priorität:** Hoch

**Akzeptanzkriterien:**

- AK-001: Bei gültiger Artikelnummer und positiver Bestellmenge gelten diese Eingaben als valide.
- AK-002: Bei einer unbekannten Artikelnummer zeigt das System eine Fehlermeldung an und verhindert das Speichern der Bestellung.
- AK-003: Bei einer Bestellmenge kleiner oder gleich null zeigt das System eine Fehlermeldung an und verhindert das Speichern der Bestellung.
