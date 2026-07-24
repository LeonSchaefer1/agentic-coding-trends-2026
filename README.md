# Agentic Coding Trends 2026

Täglich aktualisierter Datensatz zum Open-Source-Ökosystem rund um Coding-Agenten und KI-Coding-Assistenten.

Die [kanonische Studie mit Methodik und Einordnung](https://agentic-coder.de/studien/agentic-coding-trends-2026) wird von Agentic Coder veröffentlicht. Dieses Repository stellt die maschinenlesbaren Daten zusätzlich versioniert bereit.

## Daten

- [`data/agentic-coding-repositories-2026.json`](data/agentic-coding-repositories-2026.json): vollständiger Snapshot mit Methodik und Zusammenfassung
- [`data/agentic-coding-repositories-2026.csv`](data/agentic-coding-repositories-2026.csv): tabellarische Repository-Daten

Der Snapshot umfasst derzeit 40 deduplizierte, aktive Repositories. Er wird regelbasiert aus der GitHub REST API erzeugt und täglich nach dem Datenlauf auf agentic-coder.de synchronisiert.

## Auswahl

Berücksichtigt werden nicht archivierte, eigenständige Repositories mit:

- Coding-, Entwicklungs- oder IDE-Bezug und
- Agenten-, Assistenten-, Copilot- oder Pair-Programming-Bezug.

Listen-Repositories, Forks und archivierte Repositories werden ausgeschlossen. Die genaue Suchabfrage, der Datenstand und bekannte Einschränkungen stehen im JSON-Snapshot und auf der [Methodikseite](https://agentic-coder.de/studien/agentic-coding-trends-2026).

GitHub-Sterne messen Aufmerksamkeit, nicht Qualität. Der Datensatz ist keine Produktempfehlung und kein Ranking der Codequalität.

## Zitieren

Bitte verlinke die [kanonische Studie](https://agentic-coder.de/studien/agentic-coding-trends-2026) und nenne den im Datensatz sichtbaren Datenstand. Eine maschinenlesbare Zitation steht in [`CITATION.cff`](CITATION.cff).

## Lizenz

Die von Agentic Coder erstellte Zusammenstellung und Auswertung steht unter [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Repository-Namen, Beschreibungen und Kennzahlen stammen aus der GitHub API; Marken und Projektinhalte verbleiben bei den jeweiligen Rechteinhabern.
