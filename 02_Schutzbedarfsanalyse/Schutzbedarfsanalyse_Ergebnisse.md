# Schutzbedarfsanalyse (BSI-Standard 200-2)

## Methodik
Die Ermittlung erfolgt für die Schadensszenarien: **Verfügbarkeit (V), Integrität (I), Vertraulichkeit (Confidentiality - C)**.
Kategorisierung: **Normal**, **Hoch**, **Sehr Hoch**.

## Ergebnisse (Auszug mit Beispielen)

| Asset-ID | Bezeichnung | Schutzbedarf V | Schutzbedarf I | Schutzbedarf C | Begründung |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **A-01** | Kunden-DB | **Hoch** | **Sehr Hoch** | **Sehr Hoch** | PII Daten, Hoher finanzieller Schaden bei Datenverlust / Vertragsstrafen |
| **A-02** | Ticketsystem| **Normal** | **Normal** | **Hoch** | Kommunikation geschäftskritisch, enthält Kundennamen |
| **A-03** | Firewall | **Sehr Hoch** | **Hoch** | **Normal** | Ausfall stoppt kompletten Cloud-Dienst |
| **A-04** | Admin-WS | **Normal** | **Hoch** | **Hoch** | Zugriff auf Zugangsdaten (Passwörter) |
