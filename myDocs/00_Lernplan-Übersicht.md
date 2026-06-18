# 12-Wochen-Lernplan für AI-300

## Inhaltsverzeichnis

- [Überblick](#überblick)
- [Lektion 1: End-to-End-Überblick für ML-Implementierung](#lektion-1-end-to-end-überblick-für-ml-implementierung)
- [Lektion 2: Python-Basics für ML](#lektion-2-python-basics-für-ml)
- [Lektion 3: ML-Grundlagen](#lektion-3-ml-grundlagen)
- [Lektion 4: Evaluation und Metriken](#lektion-4-evaluation-und-metriken)
- [Lektion 5: ML-Lifecycle und MLOps](#lektion-5-ml-lifecycle-und-mlops)
- [Lektion 6: Azure-Grundlagen für AI](#lektion-6-azure-grundlagen-für-ai)
- [Lektion 7: Azure Machine Learning](#lektion-7-azure-machine-learning)
- [Lektion 8: Deployment und Model Operations](#lektion-8-deployment-und-model-operations)
- [Lektion 9: Microsoft Foundry und Generative AI](#lektion-9-microsoft-foundry-und-generative-ai)
- [Lektion 10: Git, GitHub und GitHub Actions](#lektion-10-git-github-und-github-actions)
- [Lektion 11: CI/CD, Automatisierung und IaC](#lektion-11-cicd-automatisierung-und-iac)
- [Lektion 12: Monitoring und Governance](#lektion-12-monitoring-und-governance)
- [Offene Fragen](#offene-fragen)

## Überblick

Dieser Lernplan strukturiert die Vorbereitung auf **Microsoft AI-300 / Operationalizing Machine Learning and Generative AI Solutions** in zwölf Lektionen. Die Reihenfolge verbindet Python- und ML-Grundlagen mit Azure, MLOps, GenAIOps, CI/CD, Monitoring und Governance.

## Lektion 1: End-to-End-Überblick für ML-Implementierung

### Ziel der Woche

Einen ersten Gesamtüberblick über eine einfache ML-Implementierung von Daten bis Betrieb gewinnen.

### Themen

- Daten lesen.
- Modell trainieren.
- Modell bewerten.
- Modell speichern.
- Inference ausführen.
- Deployment.
- Monitoring.
- GitHub-Actions-Pipeline.
- IaC-Grundlagen mit Azure CLI und Bicep.

### Praxis/Lab

- TODO: Kleines End-to-End-Beispiel auswählen und dokumentieren.

### Ergebnis/Deliverable

- TODO: Erste Skizze einer ML-Pipeline mit Daten, Training, Evaluation, Deployment und Monitoring.

### Wiederholung oder offene Fragen

- TODO: Welche Bestandteile gehören zwingend zu einer produktionsnahen ML-Lösung?

## Lektion 2: Python-Basics für ML

### Ziel der Woche

Python-Grundlagen für typische ML-Aufgaben wiederholen und festigen.

### Themen

- Python-Basics für Machine Learning.
- pandas.

### Praxis/Lab

- TODO: Kleines pandas-Notebook oder Python-Skript mit Datenimport und einfachen Transformationen.

### Ergebnis/Deliverable

- TODO: Dokumentierte Beispiele für Datenladen, Filtern, Gruppieren und einfache Auswertungen.

### Wiederholung oder offene Fragen

- TODO: Welche pandas-Funktionen sind für ML-Vorbereitung besonders wichtig?

## Lektion 3: ML-Grundlagen

### Ziel der Woche

Zentrale ML-Konzepte verstehen und voneinander abgrenzen.

### Themen

- Supervised Learning.
- Unsupervised Learning.
- Classification.
- Regression.
- Training Data.
- Test Data.
- Overfitting und Underfitting.
- scikit-learn.

### Praxis/Lab

- TODO: Einfaches scikit-learn-Modell trainieren und testen.

### Ergebnis/Deliverable

- TODO: Kurze Dokumentation der verwendeten Daten, Features, Labels und Modellart.

### Wiederholung oder offene Fragen

- TODO: Unterschied zwischen Classification und Regression mit eigenen Worten erklären.

## Lektion 4: Evaluation und Metriken

### Ziel der Woche

Modelle bewerten, erklären und die passenden Metriken einordnen können.

### Themen

- Accuracy.
- Precision.
- Recall.
- F1-Score.
- Confusion Matrix.
- Fehleranalyse.
- Modell bewerten, erklären und evaluieren.

### Praxis/Lab

- TODO: Evaluation eines trainierten Modells mit mehreren Metriken durchführen.

### Ergebnis/Deliverable

- TODO: Kurzer Evaluationsbericht mit Metriken, Interpretation und möglichen Fehlerquellen.

### Wiederholung oder offene Fragen

- TODO: Wann ist Accuracy nicht ausreichend?

## Lektion 5: ML-Lifecycle und MLOps

### Ziel der Woche

Den ML-Lifecycle und typische MLOps-Bausteine verstehen.

### Themen

- Experiment Tracking.
- Model Registry.
- Versionierung.
- Reproduzierbarkeit.
- Pipelines.
- Deployment.
- Monitoring.
- Drift.
- Modell speichern.
- Version notieren.
- Einfache Registry lokal simulieren.

### Praxis/Lab

- TODO: Lokale Modellversionierung oder einfache Registry-Struktur simulieren.

### Ergebnis/Deliverable

- TODO: Dokumentierte Modellversion mit Trainingsparametern, Metriken und Artefaktpfad.

### Wiederholung oder offene Fragen

- TODO: Welche Informationen müssen reproduzierbar gespeichert werden?

## Lektion 6: Azure-Grundlagen für AI

### Ziel der Woche

Azure-Basics für sichere, skalierbare MLOps- und GenAIOps-Infrastruktur verstehen.

### Themen

- Azure Subscription.
- Resource Group.
- Identity und Entra ID.
- RBAC.
- Storage.
- Compute.
- Networking.
- Azure CLI.
- Sichere, skalierbare Infrastruktur für MLOps und GenAIOps über Azure einrichten.
- Bicep.
- GitHub Actions.
- Azure-Cloud-Infrastruktur.

### Praxis/Lab

- TODO: Azure-Grundstruktur konzeptionell skizzieren; echte Provisionierung nur im privaten Infra-Repository.

### Ergebnis/Deliverable

- TODO: Architektur-Notiz zu Resource Groups, Identitäten, Rollen und Netzwerkgrenzen.

### Wiederholung oder offene Fragen

- TODO: Welche Berechtigungen sind minimal notwendig?

## Lektion 7: Azure Machine Learning

### Ziel der Woche

Die wichtigsten Azure-ML-Komponenten kennenlernen und ihren Zweck verstehen.

### Themen

- Workspace.
- Compute.
- Datastores.
- Data Assets.
- Environments.
- Components.
- Jobs.
- Pipelines.
- Managed Endpoints.

### Praxis/Lab

- TODO: Azure-ML-Komponenten anhand einer Beispielarchitektur beschreiben.

### Ergebnis/Deliverable

- TODO: Glossar oder Mapping der Azure-ML-Komponenten zu MLOps-Aufgaben.

### Wiederholung oder offene Fragen

- TODO: Wann wird ein Job, eine Pipeline oder ein Managed Endpoint verwendet?

## Lektion 8: Deployment und Model Operations

### Ziel der Woche

Deployment-Optionen und Betriebsaufgaben für ML-Modelle verstehen.

### Themen

- Real-time Endpoint.
- Batch Endpoint.
- Rollout.
- Rollback.
- Tests.
- Troubleshooting.
- Model Monitoring.
- Inference-API und FastAPI-Konzepte.
- Implementierung einer Inference-API.

### Praxis/Lab

- TODO: Einfache Inference-API konzipieren oder lokal prototypisch umsetzen.

### Ergebnis/Deliverable

- TODO: Dokumentierte Schnittstelle mit Beispielrequest, Beispielresponse und Testidee.

### Wiederholung oder offene Fragen

- TODO: Unterschied zwischen Real-time Endpoint und Batch Endpoint erklären.

## Lektion 9: Microsoft Foundry und Generative AI

### Ziel der Woche

Grundlagen von Microsoft Foundry und GenAIOps verstehen.

### Themen

- Foundation Models.
- Prompts.
- Prompt-Versionierung.
- Agents.
- Evaluations.
- Safety.
- Observability.
- Microsoft Foundry.

### Praxis/Lab

- TODO: Prompt- und Agenten-Beispiele nur als neutrale Lernnotiz dokumentieren, ohne private Daten.

### Ergebnis/Deliverable

- TODO: Struktur für Prompt-Versionierung und Evaluation beschreiben.

### Wiederholung oder offene Fragen

- TODO: Welche Qualitäts- und Sicherheitskontrollen sind für GenAI notwendig?

## Lektion 10: Git, GitHub und GitHub Actions

### Ziel der Woche

Git- und CI-Grundlagen für reproduzierbare ML- und GenAI-Workflows festigen.

### Themen

- Git-Architektur.
- GitHub Actions Workflow.
- Secrets.
- CI.

### Praxis/Lab

- TODO: Einfachen GitHub-Actions-Workflow für Checks oder Tests definieren.

### Ergebnis/Deliverable

- TODO: Dokumentierter Workflow-Entwurf mit Triggern, Jobs und Secret-Regeln.

### Wiederholung oder offene Fragen

- TODO: Welche Daten dürfen in GitHub Actions Secrets liegen und welche nicht im Repository?

## Lektion 11: CI/CD, Automatisierung und IaC

### Ziel der Woche

Automatisierte Pipelines und Infrastructure as Code für ML-/AI-Szenarien strukturieren.

### Themen

- CI/CD.
- Azure CLI und Bicep.
- Infrastructure as Code.
- Automatisierte Provisionierung.
- Umgebungen wie Dev, Test und Prod.
- Pipeline-Struktur: Code prüfen → Modelltraining starten → Modellartefakt speichern → Deployment-Schritt simulieren.

### Praxis/Lab

- TODO: Pipeline-Struktur als YAML- oder Architekturentwurf dokumentieren.

### Ergebnis/Deliverable

- TODO: CI/CD-Plan mit Stages für Prüfung, Training, Artefakt und Deployment-Simulation.

### Wiederholung oder offene Fragen

- TODO: Welche Schritte gehören in CI und welche in CD?

## Lektion 12: Monitoring und Governance

### Ziel der Woche

Betrieb, Überwachung, Sicherheit und Prüfungsreife zusammenführen.

### Themen

- Data Drift.
- Model Drift.
- Performance Metrics.
- Responsible AI.
- Security.
- RBAC.
- Logging.
- Kosten.
- Tokenverbrauch.
- Szenarien.
- Prüfung: Szenariofragen, Multiple Choice, Architekturentscheidungen, Fehlersuche.
- Mini-MLOps-Projekt: Dokumentation, Pipeline, Monitoring, Prüfungsfragen.

### Praxis/Lab

- TODO: Mini-MLOps-Projekt als Abschlussübung planen und dokumentieren.

### Ergebnis/Deliverable

- TODO: Abschlussdokumentation mit Pipeline, Monitoring-Ansatz und Prüfungsfragen.

### Wiederholung oder offene Fragen

- TODO: Welche Monitoring-Signale zeigen Qualitäts-, Kosten- oder Sicherheitsprobleme?

## Offene Fragen

- TODO: Offizielle AI-300-Skill-Outline regelmäßig gegen diesen Plan prüfen.
- TODO: Pro Lektion konkrete Quellen und Übungsaufgaben ergänzen.
- TODO: Entscheiden, welche Lab-Ergebnisse öffentlich dokumentiert werden dürfen.
