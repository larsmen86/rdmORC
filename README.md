# rdmORC Vision 🐳

> **Research Data Management. Orchestrated.**

## Die Herausforderung
In der modernen Forschung sind Daten über unzählige Tools verstreut: Laborbücher (ELN), Cloud-Speicher, Datenbanken und lokale Analyse-Skripte. Die manuelle Verknüpfung dieser "Datensilos" kostet Zeit, ist fehleranfällig und verhindert echte Reproduzierbarkeit.

## Die Vision
**rdmORC** bricht diese Silos auf. Wir bauen nicht das nächste monolithische Tool, sondern das **Betriebssystem (OS) für Forschungsdaten**. rdmORC fungiert als smarter Dirigent (Orchestrator), der spezialisierte Open-Source-Lösungen zu einer harmonischen Einheit verbindet.

### Kernprinzipien

1. **Das Puzzle-Prinzip (Modularität)**
   Forschung ist individuell. rdmORC ist modular aufgebaut. Ob eLabFTW, MinIO, n8n oder eigene Python-Skripte – jedes Tool ist ein Puzzleteil, das über standardisierte Konnektoren in den Stack integriert wird.

2. **Infrastructure as a Service (Dokku-Powered)**
   Komplexität darf kein Hindernis sein. Durch die Nutzung von Dokku wird das Deployment eines kompletten RDM-Stacks so einfach wie ein `git push`. 

3. **Zentrale Intelligenz & Identität**
   Mit **authentik** als Herzstück für das Identity Management und einer zentralen **Flask-Middleware** schaffen wir eine Single-Sign-On-Umgebung, in der Daten fließen und Berechtigungen systemübergreifend gelten.

4. **Automatisierung als Standard**
   Forschungsdatenmanagement darf keine lästige Pflicht sein. Durch die tiefe Integration von **n8n** automatisieren wir den Datenfluss vom Messgerät über den S3-Speicher bis in das elektronische Laborbuch.

## Das Ziel
**rdmORC** wird die Standard-Distribution für Arbeitsgruppen, die volle Kontrolle über ihre Daten wollen, ohne ein komplettes IT-Team beschäftigen zu müssen. 

**Einfach. Sicher. Skalierbar.**
