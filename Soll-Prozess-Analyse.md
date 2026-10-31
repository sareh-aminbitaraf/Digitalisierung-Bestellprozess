# Soll-Prozess-Analyse – Digitaler Bestellprozess

## 1. Zielsetzung

Ziel ist die Digitalisierung des manuellen Bestellprozesses, um Bearbeitungszeiten zu reduzieren, Eingabefehler zu vermeiden und die Transparenz zu erhöhen.

## 2. Beschreibung des Soll-Prozesses

1. Der Kunde erfasst seine Bestellung über ein digitales Bestellformular.
2. Das System validiert Artikelnummern und Bestellmengen automatisch.
3. Bei ungültigen Eingaben zeigt das System eine Fehlermeldung an und verhindert das Speichern.
4. Bei gültigen Eingaben wird die Warenverfügbarkeit über eine digitale Bestandsabfrage geprüft.
5. Bei ausreichendem Bestand wird die Bestellung gespeichert und eine automatische Auftragsbestätigung versendet.
6. Der Kunde kann den aktuellen Bestellstatus online einsehen.

## 3. Geplante Verbesserungen

| Schwachstelle | Vorgeschlagene Lösung | Erwarteter Nutzen |
|---|---|---|
| SW-001 – Manuelle Dateneingabe | Digitales Bestellformular mit automatischer Validierung | Weniger Eingabefehler |
| SW-002 – Hoher Zeitaufwand | Automatisierte Erfassung und Bestandsprüfung | Kürzere Bearbeitungszeit |
| SW-003 – Fehlende Statusübersicht | Zentrale digitale Bestellstatusanzeige | Bessere Nachverfolgbarkeit |

## 4. Zielkennzahlen

| Kennzahl | Ist-Wert | Soll-Wert |
|---|---|---|
| Bestellungen pro Tag | 50 | 50 |
| Erfassungszeit pro Bestellung | 5 Minuten | 2 Minuten |
| Tägliche Erfassungszeit | 250 Minuten | 100 Minuten |
| Potenzielle Zeitersparnis pro Tag | – | 150 Minuten (60 %) |

## 5. Zugehörige Anforderungen

- FR-001: Automatische Validierung der Bestelldaten.
- Weitere Anforderungen für Bestandsprüfung, automatische Bestätigung und Statusanzeige müssen noch spezifiziert werden.

## 6. Hinweis

Dieses Dokument beschreibt einen vorgeschlagenen Soll-Prozess für ein fiktives Portfolio-Projekt. Alle Kennzahlen sind beispielhafte Annahmen. Die Lösungen wurden noch nicht implementiert und die Zielwerte noch nicht durch Messungen bestätigt.
