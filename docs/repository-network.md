# Das Netz der Repositories

Dieses Repository behandelt eine **Querschnittsfrage**: Wer entscheidet, prüft und eskaliert. Es greift deshalb in jeden Schritt ein, ohne selbst einer zu sein.

## Wo es eingreift

```
  Inventar -> Einstufung -> Prüfung -> Dokumentation -> Audit -> Betrieb
      |            |            |            |            |         |
      +------ Zuständigkeit, Freigabe, Eskalation --------------------+
```

| Schritt | Was dieses Repository beiträgt |
|---|---|
| **Inventar** | wer Eigentümer ist, und dass es eine Person im Fachbereich sein muss |
| **Einstufung** | wer entscheidet, und dass Art. 6 Abs. 3 nicht delegierbar ist |
| **Prüfung** | wer prüft, und dass es nicht der Umsetzende sein darf |
| **Dokumentation** | wer je Abschnitt liefert und wer freigibt |
| **Audit** | wer antwortet, und wer über Weiterbetrieb entscheidet |
| **Betrieb** | wer eskaliert, an wen, mit welchem Entscheidungsvorschlag |

## Die Repositories, mit denen es zusammenarbeitet

| Repository | Verbindung |
|---|---|
| [Governance-Rahmenwerk](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework) | das Dach: wie die fünf Bereiche zusammenhängen. Dieses Repository füllt den Bereich Governance aus |
| [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) | dort steht die Zuständigkeit je Eintrag; das Zuständigkeitsmodell dort und die Tabelle hier beschreiben dasselbe |
| [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist) | der Mindeststandard für Prüfpunkte, und die Rollentrennung bei der Feststellung |
| [Audit-Vorbereitung](https://github.com/SimpleAct-Compliance/simpleact-ai-audit-readiness) | das Lückenprotokoll mit der Spalte Verschiebungen — die Grundlage für einen der vier Eskalationsauslöser |
| [Vorfallmanagement](https://github.com/SimpleAct-Compliance/simpleact-incident-management) | Eskalation im Vorfall, Art. 72 und 73 |
| [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu) | die Klasse, aus der sich die Zuständigkeit ergibt |

Die **Audit-Vorbereitung** ist dabei besonders eng verbunden: Die Spalte „Verschiebungen" im Lückenprotokoll ist die Datenquelle für den Eskalationsauslöser „Befund zum dritten Mal verschoben". Ohne sie bleibt dieser Auslöser eine Absicht.

## Abgrenzung zum Rahmenwerk

Die beiden werden verwechselt:

| | Governance-Rahmenwerk | dieses Repository |
|---|---|---|
| Frage | Welche Bereiche gibt es und wie hängen sie zusammen? | Wer entscheidet, prüft, eskaliert? |
| Umfang | fünf Bereiche, Lebenszyklus | ein Bereich, ausgearbeitet |
| Ergebnis | ein Modell | Zuständigkeitstabelle und Prüfturnus |

Wer den Zusammenhang sucht, liest das Rahmenwerk. Wer Namen in eine Tabelle schreiben will, liest dieses.

## Besondere Lagen

| Lage | Repository |
|---|---|
| Softwareanbieter: Freigabe am Release | [AI Act für SaaS](https://github.com/SimpleAct-Compliance/simpleact-ai-act-for-saas) |
| Art. 4: Schulung und Nachweis | [KI-Kompetenz](https://github.com/SimpleAct-Compliance/elearning) |
| Register, die sich selbst füllen | [Integrationen](https://github.com/SimpleAct-Compliance/simpleact-integrations-apis) |
| Vorlagen für alles Übrige | [Vorlagensammlung](https://github.com/SimpleAct-Compliance/simpleact-ai-act-templates) |

Das SaaS-Repository ergänzt das Freigabetor um die fünf Fragen, die bei einem **Release** zu stellen sind — für Produktanbieter ist das der praktisch wichtigere Tortyp.

## Datenschutzseite

Die Zuweisungen laufen parallel und überschneiden sich stark.

| Repository | Zuweisung |
|---|---|
| [DSGVO-Grundlagen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-compliance-workspace) | Verarbeitungsverzeichnis, Rechtsgrundlagen, Betroffenenrechte |
| [DSFA und FRIA](https://github.com/SimpleAct-Compliance/simpleact-dpia-dsfa-workflow) | Art. 35 DSGVO beim Datenschutz, Art. 27 AI Act beim Betreiber |
| [Datenschutzverletzungen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-data-breach-management) | 72 Stunden ab Kenntnis — und die Festlegung, wer die Kenntnis hat |

Die letzte Zeile ist die, die eine Festlegung im Playbook braucht: Der häufigste Fehler ist, dass der Support eine Meldung als Qualitätsproblem bearbeitet, während die Frist läuft.

## Tarifgenaue Anbieterangaben

Für die Zuweisung an die Beschaffung: ein öffentliches Register mit tarifgenauen Angaben einzelner KI-Werkzeuge, jede mit Quelle und Prüfdatum — **[actcomp.de](https://actcomp.de)**
