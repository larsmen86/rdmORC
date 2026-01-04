# rdmORC Roadmap 🗺️

Der Weg zum voll orchestrierten Forschungsdaten-Management.

---

## Phase 1: Das Fundament (The Ground Zero) 🏗️
*Ziel: Die Infrastruktur steht und der "Türsteher" regelt den Einlass.*

- [ ] **Dokku Server Setup:** Initialisierung eines frischen Ubuntu-Servers mit Dokku.
- [ ] **Domain & SSL:** Konfiguration von `rdm-orc.de` und Wildcard-Zertifikaten via Let's Encrypt.
- [ ] **Auth-Zentrale:** Deployment von **authentik** (`auth.rdm-orc.de`).
- [ ] **User-Directory:** Einrichten der ersten Forschungsgruppen und LDAP/OIDC-Provider.

## Phase 2: Die Instrumente (Core Components) 🎹
*Ziel: Die wichtigsten Tools sind als Puzzleteile verfügbar.*

- [ ] **Object Storage:** Deployment von **MinIO** (`data.rdm-orc.de`) inkl. Anbindung an authentik.
- [ ] **Electronic Lab Notebook:** Integration von **eLabFTW** (`lab.rdm-orc.de`).
- [ ] **Workflow Engine:** Deployment von **n8n** (`flow.rdm-orc.de`) für die ersten Automatisierungen.
- [ ] **Database Plugin:** Bereitstellen zentraler Postgres-Instanzen für die Puzzlestücke.

## Phase 3: Der Dirigent (The Orchestrator) 🎼
*Ziel: Die rdmORC Plattform verbindet die Tools via Next.js.*

- [ ] **Next.js Core App:** Start der zentralen Plattform (GUI) zur Orchestrierung.
- [ ] **Unified Connector Framework:** Entwicklung der TypeScript-Interfaces für eLab, MinIO & Co.
- [ ] **REST API Layer:** Implementierung von Endpoints für den externen programmatischen Zugriff.
- [ ] **Dashboard:** Zentrale Übersicht über den Status aller Container und Datenflüsse.

## Phase 4: Harmonie & Skalierung (Fine Tuning) 🚀
*Ziel: Headless-Betrieb und Produktivnutzung.*

- [ ] **M2M Authentication:** API-Key Management über authentik für Python-Skripte.
- [ ] **Python SDK:** Entwicklung eines Wrappers (`pip install rdm-orc`) für Forscher.
- [ ] **Backup-Strategie:** Automatisierte Snapshots der Dokku-Volumes auf S3.
- [ ] **One-Click Templates:** Skripte für schnelles Deployment neuer Instanzen.

---

## Legende
- 🏗️ **Infrastructure**: Server, Netzwerke und Security.
- 🎼 **Orchestration**: Der Kleber (Next.js) zwischen den Tools.
- 🧪 **Research**: Features für den direkten Labor- und Analyse-Alltag.
