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

Angehender **IT-Administrator**. Das meiste, was ich über den Beruf weiß, kommt
daher, dass ich ihn zuhause betreibe. Mein Homelab läuft rund um die Uhr und
trägt echte Dienste: die Smart-Home-Steuerung, meine Webseiten, meine Daten.
Gebaut und am Laufen gehalten habe ich das selbst. Wenn etwas ausfällt, schreibe
ich hinterher auf, wie es zu beheben war.

Portfolio, Lebenslauf und Kontakt: **[djouhri.de](https://djouhri.de)**

### Was ich betreibe

Ein Verbund aus mehreren Einplatinenrechnern und einem x86-Virtualisierungscluster,
seit 2024 durchgehend in Betrieb.

- **Linux und Docker.** Über 160 containerisierte Dienste auf einem gemeinsamen
  gehärteten Fundament: non-root, read-only Root-Dateisystem, kleine
  Angriffsfläche.
- **Virtualisierung.** Drei Proxmox-Knoten tragen die schweren Lasten, für die
  die kleinen Rechner zu klein geworden sind. Dazu ein Windows-Server- und
  Active-Directory-Lab in eigenen VMs.
- **Netzwerk und Sicherheit.** Getrennte Netzzonen, kein offener Port nach außen,
  Zugang über Reverse-Proxy und VPN. Eine zentrale Überwachung meldet
  TLS-Zertifikate, bevor sie ablaufen.
- **Ressourcen-Planung.** Einer der Knoten ist knapp bei Speicher. Ein eigener
  Regler fragt jede laufende Rolle nach ihrer tatsächlichen Auslastung und
  entscheidet daraus, wer laufen darf.
- **Observability.** Prometheus und Grafana, Health-Checks, Timer-Überwachung,
  CVE-Scans der laufenden Images.
- **Betrieb.** Verschlüsselte Off-Site-Backups, täglich auf Vollständigkeit
  geprüft und regelmäßig zurückgespielt. Runbooks für die Fälle, die ich schon
  einmal hatte. Ein Watchdog außerhalb des Heimnetzes schaut von draußen drauf.

### Ausgewählte Projekte

- **[service-template](https://github.com/sami-djouhri/service-template):** das
  gehärtete Python-Fundament, aus dem bei mir dutzende Dienste entstanden sind.
- **[trivy-scanner](https://github.com/sami-djouhri/trivy-scanner):**
  CVE-Scanning einer ganzen Container-Flotte auf einem Rechner, der dafür
  eigentlich zu wenig RAM hat. Ergebnis geht als Prometheus-Metrik raus.
- **[brain-bus](https://github.com/sami-djouhri/brain-bus):** Ops-Automation, die
  MQTT-Events zu Meldungen verarbeitet. Alles, was etwas verändern würde, braucht
  vorher eine Bestätigung.
- **[minecraft-arbiter](https://github.com/sami-djouhri/minecraft-arbiter):** der
  Regler von oben, ausgeschrieben.
- **[sami-portfolio](https://github.com/sami-djouhri/sami-portfolio):** die
  Codebasis hinter djouhri.de (Next.js, gehärteter Container, selbst gehostet).

### Werkzeugkasten

Was die Badges nicht zeigen: restic für die Backups, nftables an den Rändern,
SQLite als Standard-Datenhaltung der kleinen Dienste, Caddy überall dort, wo
automatisches TLS reicht.

---
<sub>Das meiste läuft privat auf eigener Hardware. Was hier liegt, ist ein
kuratierter, secret-freier Ausschnitt davon.</sub>
