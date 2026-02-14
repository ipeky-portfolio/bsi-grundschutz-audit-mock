# Risikoanalyse (BSI-Standard 200-3)

## Anwendung
Eine Risikoanalyse ist erforderlich, wenn:
1.  Der Schutzbedarf **Hoch** oder **Sehr Hoch** ist und keine Bausteine existieren.
2.  Die Anforderungen der Bausteine nicht umgesetzt werden können.

## Risiko-Register (Beispiel mit Tiefgang)

| Risiko-ID | Asset | Bedrohung | Eintritt | Schaden | Risikowert | Maßnahme (Beispiele) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **R-01** | Kunden-DB | SQL-Injection | Mittel | Hoch | **Hoch** | Implementierung Web Application Firewall (WAF) |
| **R-02** | Firewall | Ausfall durch Blitzschlag| Gering | Sehr Hoch| **Hoch** | Installation USV und Überspannungsschutz (Baustein INF.1) |
| **R-03** | Ticketsystem| Cloud-Anbieter Insolvenz| Gering | Hoch | **Hoch** | Regelmäßiges Backup der Daten auf lokalen Storage (Offsite) |
