## Sami Djouhri

![Linux](https://img.shields.io/badge/Linux-333333?logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?logo=proxmox&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?logo=nginx&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?logo=wireguard&logoColor=white)
![systemd](https://img.shields.io/badge/systemd-30D475?logo=systemd&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

Angehender **IT-Administrator**. Ich lerne den Beruf nicht nur, ich betreibe ihn.
Mein selbst gebautes Homelab läuft rund um die Uhr und trägt real meine
Smart-Home-, Web- und Datendienste. Gebaut, gehärtet und am Laufen gehalten von
mir. Aus jedem Ausfall wird das nächste Runbook.

Portfolio, Lebenslauf und Kontakt: **[djouhri.de](https://djouhri.de)**

### Was ich betreibe
Ein Multi-Host-Verbund aus Einplatinenrechnern und einem
x86-Virtualisierungscluster, dauerhaft in Betrieb und nicht nur zum Ausprobieren:

- **Linux und Docker:** über 160 containerisierte Dienste auf einem gemeinsamen,
  gehärteten Fundament (non-root, read-only Root-Dateisystem, minimale
  Angriffsfläche).
- **Virtualisierung:** ein Proxmox-Cluster aus drei Knoten trägt die schweren
  Lasten, die auf die kleinen Rechner nicht mehr passen, dazu ein
  Windows-Server- und Active-Directory-Lab in eigenen VMs.
- **Ressourcen-Planung:** ein knapper Knoten plant sich selbst, statt
  überbucht zu werden. Ein eigener Regler entscheidet nach echter Auslastung,
  welche schwere Rolle laufen darf, und schaltet Leerlauf wieder ab.
- **Netzwerk und Sicherheit:** segmentierte Netzzonen, kein offener Port nach
  außen, Zugang nur über Reverse-Proxy und VPN, zentrales TLS-Ablauf-Monitoring.
- **Observability:** Prometheus und Grafana, Health-Checks, Timer-Überwachung,
  automatisches CVE-Scanning der laufenden Images.
- **Betrieb und Ausfallsicherheit:** verschlüsselte Off-Site-Backups mit
  täglicher Vollständigkeits-Prüfung und regelmäßigem Restore-Test,
  dokumentierte Runbooks, externer Watchdog außerhalb des Heimnetzes.

### Ausgewählte Projekte
- **[service-template](https://github.com/sami-djouhri/service-template):** mein
  gehärtetes Python-Microservice-Fundament, aus dem dutzende Dienste entstehen.
- **[trivy-scanner](https://github.com/sami-djouhri/trivy-scanner):**
  RAM-schonendes CVE-Scanning einer Container-Flotte, exportiert als
  Prometheus-Metrik.
- **[brain-bus](https://github.com/sami-djouhri/brain-bus):** eine
  Ops-Automation-Engine, die MQTT-Events zu Meldungen oder bestätigungspflichtigen
  Aktionen verarbeitet.
- **[minecraft-arbiter](https://github.com/sami-djouhri/minecraft-arbiter):** ein
  Ressourcen-Regler, der auf einem knappen Virtualisierungs-Knoten immer nur eine
  schwere Rolle laufen lässt, gesteuert nach echter Auslastung.
- **[sami-portfolio](https://github.com/sami-djouhri/sami-portfolio):** die
  Codebasis hinter djouhri.de (Next.js, gehärteter Container, self-hosted).

### Werkzeugkasten
`Linux` · `Docker` · `Proxmox` · `Bash` · `Python` · `nginx` · `Prometheus` · `Grafana` · `WireGuard` · `systemd` · `restic` · `Git`

---
<sub>Das meiste läuft privat auf eigener Hardware. Hier ein kuratierter,
secret-freier Ausschnitt, genug um zu zeigen, wie ich baue und betreibe.</sub>
