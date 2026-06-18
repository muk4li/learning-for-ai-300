# AI-300 Lernportfolio

## Ziel des Repositorys

Dieses Repository ist ein öffentliches Lernportfolio zur Vorbereitung auf **Microsoft AI-300 / Operationalizing Machine Learning and Generative AI Solutions**.

Der Fokus liegt auf strukturierten Lernnotizen zu Machine Learning, MLOps, GenAIOps, Azure, Microsoft Foundry, CI/CD, Monitoring, Governance und Security.

> Hinweis: Echte Provisionierung, produktionsnahe Infrastruktur, Subscription-spezifische Konfigurationen und sensible Werte gehören nicht in dieses öffentliche Repository. Falls echte Infrastruktur aufgebaut wird, erfolgt dies in einem separaten privaten Infra-Repository.

## Struktur-Review

Die aktuelle Struktur ist bewusst schlank:

```text
.
├── README.md
└── myDocs/
    ├── 00_Anforderungen-Übersicht.md
    ├── 00_Lernplan-Übersicht.md
    └── 01_Grundbegriffe.md
```

Diese Struktur ist für ein öffentliches AI-300-Lernrepo geeignet, weil sie die wichtigsten Inhalte zentral bündelt und leicht auf GitHub lesbar macht.

Minimale mögliche Verbesserungen, die aktuell **nicht automatisch umgesetzt** wurden:

- Optional später einen Ordner `labs/` ergänzen, sobald echte öffentlich dokumentierbare Übungen vorhanden sind.
- Optional später einen Ordner `diagrams/` ergänzen, falls Architekturdiagramme entstehen.
- Optional später eine Fortschrittsübersicht ergänzen, wenn die Lektionen aktiv bearbeitet werden.

## Navigation

- [Anforderungen und Lerninhalte](myDocs/00_Anforderungen-Übersicht.md)
- [12-Wochen-Lernplan](myDocs/00_Lernplan-Übersicht.md)
- [Grundbegriffe: AI, Machine Learning und MLOps](myDocs/01_Grundbegriffe.md)

## Übersicht über den 12-Wochen-Lernplan

| Woche | Thema | Dokument |
| --- | --- | --- |
| 1 | End-to-End-Überblick für ML-Implementierung | [Lektion 1](myDocs/00_Lernplan-Übersicht.md#lektion-1-end-to-end-überblick-für-ml-implementierung) |
| 2 | Python-Basics für ML | [Lektion 2](myDocs/00_Lernplan-Übersicht.md#lektion-2-python-basics-für-ml) |
| 3 | ML-Grundlagen | [Lektion 3](myDocs/00_Lernplan-Übersicht.md#lektion-3-ml-grundlagen) |
| 4 | Evaluation und Metriken | [Lektion 4](myDocs/00_Lernplan-Übersicht.md#lektion-4-evaluation-und-metriken) |
| 5 | ML-Lifecycle und MLOps | [Lektion 5](myDocs/00_Lernplan-Übersicht.md#lektion-5-ml-lifecycle-und-mlops) |
| 6 | Azure-Grundlagen für AI | [Lektion 6](myDocs/00_Lernplan-Übersicht.md#lektion-6-azure-grundlagen-für-ai) |
| 7 | Azure Machine Learning | [Lektion 7](myDocs/00_Lernplan-Übersicht.md#lektion-7-azure-machine-learning) |
| 8 | Deployment und Model Operations | [Lektion 8](myDocs/00_Lernplan-Übersicht.md#lektion-8-deployment-und-model-operations) |
| 9 | Microsoft Foundry und Generative AI | [Lektion 9](myDocs/00_Lernplan-Übersicht.md#lektion-9-microsoft-foundry-und-generative-ai) |
| 10 | Git, GitHub und GitHub Actions | [Lektion 10](myDocs/00_Lernplan-Übersicht.md#lektion-10-git-github-und-github-actions) |
| 11 | CI/CD, Automatisierung und IaC | [Lektion 11](myDocs/00_Lernplan-Übersicht.md#lektion-11-cicd-automatisierung-und-iac) |
| 12 | Monitoring und Governance | [Lektion 12](myDocs/00_Lernplan-Übersicht.md#lektion-12-monitoring-und-governance) |

## Labs und Dokumentation

Labs werden nur dokumentiert, wenn sie ohne private Daten, Secrets oder produktive Zugangsdaten nachvollziehbar beschrieben werden können.

Geplante Dokumentationsarten:

- Lernnotizen und Begriffsdefinitionen.
- Architektur- und Prozessnotizen.
- Pipeline- und MLOps-Konzepte.
- Zusammenfassungen von Übungen und Erkenntnissen.

> TODO: Konkrete Labs ergänzen, sobald sie vorhanden und öffentlich dokumentierbar sind.

## Sicherheit

Dieses Repository enthält keine Secrets oder produktiven Zugangsdaten. Insbesondere sollen nicht enthalten sein:

- Tokens.
- Tenant IDs.
- Subscription IDs.
- Client Secrets.
- Private Hostnamen.
- Private Repository-Links.
- Echte Zugangsdaten.

Falls sensible Werte in Lernnotizen benötigt werden, werden Platzhalter wie `<TODO: value>` verwendet.

## Nächste Schritte

- TODO: Offizielle AI-300-Prüfungsziele regelmäßig mit dem Lernplan abgleichen.
- TODO: Pro Lektion Lernfortschritt und offene Fragen ergänzen.
- TODO: Öffentlich geeignete Labs dokumentieren.
