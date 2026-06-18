# Codex-Vorschläge für weitere Inhalte

Diese Datei enthält Vorschläge, welche Inhalte, Quellen und Übungen das AI-300-Lernportfolio sinnvoll erweitern könnten. Die Punkte sind bewusst als Vorschläge formuliert und sollten vor der Umsetzung manuell geprüft werden.

## 1. Inhalte, die im Lernportfolio noch hilfreich wären

### Prüfungs- und Skill-Mapping

- Eine Tabelle ergänzen, die die offiziellen AI-300-Skills den vorhandenen Lektionen zuordnet.
- Pro Skill markieren:
  - `abgedeckt`
  - `teilweise abgedeckt`
  - `offen`
- Die Datei [humanToDos/Ergänzen.md](../humanToDos/Ergänzen.md) kann dafür als Quellenliste dienen.

### Glossar ausbauen

- Die offenen Definitionen in [myDocs/01_Grundbegriffe.md](../myDocs/01_Grundbegriffe.md) ergänzen:
  - Training
  - Inference
  - Evaluation
  - MLOps
  - GenAIOps
- Zusätzlich sinnvoll wären kurze Begriffe zu:
  - Feature Engineering
  - Data Drift
  - Model Drift
  - Prompt Evaluation
  - Responsible AI
  - RBAC
  - Managed Endpoint
  - Batch Endpoint

### Architektur-Notizen ergänzen

- Eine neutrale Architekturübersicht für ein MLOps-Szenario ergänzen:
  - Datenquelle
  - Training
  - Evaluation
  - Model Registry
  - Deployment
  - Monitoring
  - CI/CD
- Eine zweite Architekturübersicht für ein GenAIOps-Szenario ergänzen:
  - Prompt-Versionierung
  - Modell-/Deployment-Auswahl
  - Evaluation
  - Safety Checks
  - Observability
  - Kosten-/Token-Monitoring

> Wichtig: Architekturbeispiele sollten keine echten Tenant-, Subscription-, Host- oder Projektdaten enthalten.

## 2. Weitere Quellen, die sinnvoll geprüft werden könnten

### Microsoft Learn / Microsoft Docs

- Offizielle AI-300 Study-Guide-Seite regelmäßig gegen den Lernplan prüfen.
- Azure Machine Learning-Dokumentation für Workspaces, Jobs, Pipelines, Environments, Datastores, Data Assets und Managed Endpoints heranziehen.
- Azure AI Foundry-Dokumentation für Generative-AI-Themen, Evaluation, Safety und Observability prüfen.
- GitHub Actions-Dokumentation für CI/CD-Beispiele und Secret-Handling verwenden.

### Python und Machine Learning

- scikit-learn-Dokumentation für kleine, reproduzierbare ML-Beispiele nutzen.
- pandas-Dokumentation für Datenvorbereitung und Exploratory Data Analysis ergänzen.
- Optional MLflow-Grundlagen prüfen, falls Experiment Tracking und Model Registry lokal demonstriert werden sollen.

### Security und Responsible AI

- Microsoft-Dokumentation zu Responsible AI als Quelle für Governance- und Safety-Abschnitte prüfen.
- Azure RBAC- und Managed-Identity-Dokumentation für Sicherheitsabschnitte heranziehen.
- GitHub-Dokumentation zu Secrets, Environments und Dependabot prüfen.

## 3. Übungsideen für das Repository

### Übung 1: Lokales scikit-learn-Miniprojekt

**Ziel:** Ein kleines Modell lokal trainieren, evaluieren und speichern.

Mögliche Schritte:

1. Öffentlichen Beispieldatensatz auswählen.
2. Daten mit pandas laden.
3. Features und Label dokumentieren.
4. Train/Test-Split durchführen.
5. scikit-learn-Modell trainieren.
6. Accuracy, Precision, Recall und F1-Score berechnen.
7. Modellartefakt lokal speichern.
8. Ergebnisse als Markdown zusammenfassen.

**Passende Lektionen:** 2, 3, 4 und 5.

### Übung 2: Lokale MLOps-Struktur simulieren

**Ziel:** MLOps-Konzepte ohne echte Azure-Provisionierung nachvollziehen.

Mögliche Artefakte:

- `experiments/` als lokales Experiment-Tracking-Beispiel.
- `models/` als lokale Modellablage.
- `metrics.json` für Evaluationsergebnisse.
- `model-card.md` als einfache Model Card.
- `README.md` für Reproduzierbarkeit.

**Passende Lektionen:** 5, 10 und 11.

### Übung 3: CI-Check mit GitHub Actions konzipieren

**Ziel:** Einen einfachen CI-Workflow für Dokumentation und Python-Beispiele planen.

Mögliche Checks:

- Markdown-Formatprüfung.
- Python-Linting.
- Unit Tests für kleine Hilfsfunktionen.
- Kein Commit von Secrets oder `.env`-Dateien.

**Passende Lektionen:** 10 und 11.

### Übung 4: Azure-ML-Architektur ohne Provisionierung dokumentieren

**Ziel:** Azure-ML-Komponenten verstehen, ohne echte Ressourcen im öffentlichen Repository anzulegen.

Mögliche Inhalte:

- Workspace.
- Compute.
- Datastores.
- Data Assets.
- Environments.
- Jobs.
- Pipelines.
- Managed Endpoints.

**Passende Lektionen:** 6, 7 und 8.

### Übung 5: GenAIOps-Evaluationskonzept beschreiben

**Ziel:** Ein neutrales Konzept für Prompt-Versionierung, Evaluation, Safety und Observability dokumentieren.

Mögliche Inhalte:

- Prompt-Versionen.
- Testfälle.
- Qualitätsmetriken.
- Safety-Prüfungen.
- Logging- und Monitoring-Signale.
- Kosten- und Tokenverbrauch.

**Passende Lektionen:** 9 und 12.

## 4. Vorschläge für neue Dateien oder Ordner

Diese Strukturänderungen sollten vor der Umsetzung manuell bestätigt werden:

- `labs/` für öffentlich dokumentierbare Übungen.
- `glossar/` oder Ausbau von `myDocs/01_Grundbegriffe.md` für Begriffe.
- `architecture/` für Architektur-Notizen und Diagrammquellen.
- `checks/` oder `.github/workflows/` für spätere CI/CD-Beispiele.

## 5. Priorisierte nächste Schritte

1. [humanToDos/Ergänzen.md](../humanToDos/Ergänzen.md) mit dem 12-Wochenplan abgleichen.
2. Die TODOs aus [humanToDos/zumAusfüllen.md](../humanToDos/zumAusfüllen.md) nach Priorität sortieren.
3. Zuerst Grundbegriffe vervollständigen, weil sie die Basis für spätere Lektionen bilden.
4. Danach ein kleines lokales scikit-learn-Beispiel als erstes öffentliches Lab planen.
5. Anschließend CI/CD und MLOps-Struktur nur konzeptionell ergänzen, solange keine echten Azure-Ressourcen verwendet werden.
