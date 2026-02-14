# Auditbericht: Zusammenfassung (Final)

**Unternehmen:** SecureData GmbH
**Auditor:** [Dein Name]
**Datum:** 14.02.2026

## 1. Ergebnisse
Das Informationssicherheits-Managementsystem (ISMS) der SecureData GmbH ist **grundsätzlich konform** zu den Anforderungen des BSI IT-Grundschutz.

## 2. Beispiele für Befunde (Findings)

### Befund ID: B-01 (MAJOR)
* **Baustein:** `NET.3.2` (Firewall)
* **Beschreibung:** Es wurden Regeln gefunden, die `ANY` Traffic von der DMZ in das interne Produktionsnetz erlauben.
* **Risiko:** Unkontrollierter Zugriff im Falle einer Kompromittierung eines DMZ-Servers.
* **Empfehlung:** Sofortige Anpassung der Firewall-Regeln auf das **Least-Privilege-Prinzip**.

### Befund ID: B-02 (MINOR)
* **Baustein:** `SYS.1.2.1` (Arbeitsplatz-PC)
* **Beschreibung:** Die Festplattenverschlüsselung (BitLocker) ist auf 3 von 20 Admin-Workstations nicht aktiv.
* **Risiko:** Datenabfluss bei Verlust der Laptops.
* **Empfehlung:** Aktivierung mittels Gruppenrichtlinie (GPO) erzwingen.

## 3. Fazit
Mit Umsetzung der Empfehlungen ist eine Zertifizierung anzustreben.
