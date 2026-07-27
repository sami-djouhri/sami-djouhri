## Sami Djouhri

Angehender **IT-Administrator**. Ich lerne den Beruf nicht nur, ich betreibe ihn.
Mein selbst gebautes Homelab läuft rund um die Uhr und trägt real meine
Smart-Home-, Web- und Datendienste. Gebaut, gehärtet und am Laufen gehalten von
mir. Aus jedem Ausfall wird das nächste Runbook.

Portfolio, Lebenslauf und Kontakt: **[djouhri.de](https://djouhri.de)**

### Was ich betreibe
Ein Multi-Host-Verbund aus Einplatinenrechnern und einem
x86-Virtualisierungscluster, dauerhaft in Betrieb und nicht nur zum Ausprobieren:

- **Linux und Docker:** dutzende containerisierte Dienste auf einem gemeinsamen,
  gehärteten Fundament (non-root, read-only Root-Dateisystem, minimale
  Angriffsfläche).
- **Netzwerk und Sicherheit:** segmentierte Netzzonen, kein offener Port nach
  außen, Zugang nur über Reverse-Proxy und VPN, zentrales TLS-Ablauf-Monitoring.
- **Observability:** Prometheus und Grafana, Health-Checks, Timer-Überwachung,
  automatisches CVE-Scanning der laufenden Images.
- **Betrieb und Ausfallsicherheit:** verschlüsselte Off-Site-Backups,
  dokumentierte Runbooks, ein Cluster mit Lastverteilung und externem Watchdog.

### Ausgewählte Projekte
- **[service-template](https://github.com/sami-djouhri/service-template):** mein
  gehärtetes Python-Microservice-Fundament, aus dem dutzende Dienste entstehen.
- **[trivy-scanner](https://github.com/sami-djouhri/trivy-scanner):**
  RAM-schonendes CVE-Scanning einer Container-Flotte, exportiert als
  Prometheus-Metrik.
- **[brain-bus](https://github.com/sami-djouhri/brain-bus):** eine
  Ops-Automation-Engine, die MQTT-Events zu Meldungen oder bestätigungspflichtigen
  Aktionen verarbeitet.
- **[sami-portfolio](https://github.com/sami-djouhri/sami-portfolio):** die
  Codebasis hinter djouhri.de (Next.js, gehärteter Container, self-hosted).

### Werkzeugkasten
`Linux` · `Docker` · `Proxmox` · `Bash` · `Python` · `nginx` · `Prometheus` · `Grafana` · `WireGuard` · `systemd` · `restic` · `Git`

---
<sub>Das meiste läuft privat auf eigener Hardware. Hier ein kuratierter,
secret-freier Ausschnitt, genug um zu zeigen, wie ich baue und betreibe.</sub>
