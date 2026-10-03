# Governance-Playbook

**Wer entscheidet, wer prüft, wer eskaliert — und wer hat dafür Zeit?**

Die letzte Frage fehlt in den meisten Governance-Modellen und entscheidet darüber, ob sie funktionieren. Eine Zuständigkeit ohne Stundenbudget ist eine Hoffnung, und eine Zuständigkeitstabelle, in der eine Person achtzehnmal steht, ist eine Dokumentation der Überlast.

*Who decides, who reviews, who escalates — and who has the hours. The last question is what makes the difference.*

---

## Die drei Rollen

| Rolle | Wo sie sitzt | Darf nicht |
|---|---|---|
| **Eigentümer** | im Fachbereich | die eigene Arbeit freigeben |
| **Prüfer** | Compliance, Datenschutz oder Leitung | mit dem Eigentümer identisch sein |
| **Freigebender** | nach Risiko gestaffelt | unterschreiben, ohne nachzusehen |

Die rechte Spalte ist die eigentliche Aussage. Von den drei Regeln ist eine nicht verhandelbar: **Eigentümer und Prüfer sind nicht dieselbe Person.** Alles andere lässt sich in kleinen Organisationen zusammenlegen.

Ausführlich: [Das Betriebsmodell](./knowledge-base/eu-ai-act/governance-operating-model.md)

## Warum der Eigentümer im Fachbereich sitzt

Eine zentrale Stelle, die achtzig Einträge pflegt, kann bei keinem sagen, ob er noch stimmt. Sie kann die Felder ausfüllen — aber sie merkt nicht, dass der Vertrieb das Werkzeug seit drei Monaten auch für Angebote benutzt.

Der Fachbereich merkt es. Er braucht nur einen Meldeweg, der weniger Aufwand ist als es zu lassen.

## Das Freigabetor

Der Punkt, an dem Governance tatsächlich wirkt — oder zur Formalie wird.

| Frage am Tor | Formale Antwort | Antwort, die trägt |
|---|---|---|
| Ist die Kennzeichnung umgesetzt? | Haken | „zeig mir den Hinweis im laufenden System" |
| Ist die Aufsicht zugewiesen? | Haken | „bei 300 Fällen am Tag — in welcher Zeit?" |
| Sind die Pflichten verteilt? | Haken | „an welche Person, bis wann?" |
| Ist geschult worden? | Haken | „zu welchem Inhalt, am welchem Datum?" |

Die rechte Spalte ist der Unterschied zwischen einer Freigabe und einer Unterschrift. Ausführlich: [Freigabetore und Delegation](./knowledge-base/eu-ai-act/go-live-gates-and-delegation.md)

## Eskalation, die funktioniert

Die meisten Eskalationswege werden nie benutzt. Nicht, weil nichts passiert, sondern weil nicht festgelegt ist, **was** eskaliert wird und **was dann geschieht**.

Vier Auslöser, bei denen eskaliert werden muss:

| Auslöser | An wen |
|---|---|
| Art.-5-Treffer | Geschäftsführung, sofort — nicht abwägbar |
| Befund zum **dritten Mal** verschoben | Leitungsebene über dem Verantwortlichen |
| System läuft weiter, obwohl ein Befund offen ist | Geschäftsführung, als Entscheidung |
| Aufsichtskennzahl fällt gegen Null | Fachbereichsleitung |

Die zweite Zeile ist die, die kein Modell vorsieht und die am häufigsten gebraucht wird: Ein dreimal verschobener Befund ist keine offene Aufgabe mehr, sondern eine Entscheidung, die niemand ausgesprochen hat.

Ausführlich: [Eskalation und Entscheidungen](./knowledge-base/eu-ai-act/escalation-and-decision-logic.md)

## Turnus ist eine Untergrenze

Ein Jahresturnus als einzige Maßnahme bedeutet: im Mittel ein halbes Jahr lang eine Bewertung, die nicht mehr gilt. Die wirksamen Prüfungen sind **ereignisbezogen** — und drei der sechs Auslöser bemerkt eine Organisation ohne eigene Vorkehrung nicht.

Ausführlich: [Prüfturnus](./knowledge-base/eu-ai-act/review-cadence-logic.md)

## Die drei Kennzahlen, die etwas über Governance sagen

| Kennzahl | Was ein schlechter Wert bedeutet |
|---|---|
| Anteil der Einträge mit **Eigentümer namentlich** | jeder fehlende Name ist eine Lücke mit Adresse |
| Häufigkeit derselben Person in der Zuständigkeitstabelle | Überlast, die sonst erst bei der Kündigung auffällt |
| wie Auslöser **bekannt geworden** sind | steht dort nur Zufall, fehlt ein Verfahren |

Die zweite wird fast nie erhoben und ist die nützlichste Auswertung im ganzen Modell: die Tabelle einmal nach Häufigkeit sortieren.

## Inhalt

| Dokument | Inhalt |
|---|---|
| [Das Betriebsmodell](./knowledge-base/eu-ai-act/governance-operating-model.md) | drei Rollen, Zuschnitt nach Größe, was zentral geht |
| [Freigabetore und Delegation](./knowledge-base/eu-ai-act/go-live-gates-and-delegation.md) | das Tor, Staffelung nach Risiko, was delegierbar ist |
| [Eskalation und Entscheidungen](./knowledge-base/eu-ai-act/escalation-and-decision-logic.md) | vier Auslöser, was eine Entscheidung festhalten muss |
| [Prüfturnus](./knowledge-base/eu-ai-act/review-cadence-logic.md) | ereignisbezogen gegen turnusmäßig, was wann läuft |
| [Was wann gilt](./knowledge-base/eu-ai-act/overview.md) | welche Pflichten heute Zuständigkeit brauchen |
| [Begriffe](./knowledge-base/eu-ai-act/definitions.md) | Aufsicht, Zuständigkeit, Freigabe, Eskalation |
| [Rollen nach der Verordnung](./knowledge-base/eu-ai-act/scope-and-actors.md) | Anbieter, Betreiber, und wer intern antwortet |
| [Zuständigkeit je Klasse](./knowledge-base/eu-ai-act/risk-logic.md) | wer je Risikoklasse zuständig wird |
| [Register und Pflege](./knowledge-base/eu-ai-act/inventory-and-governance.md) | woran Verfall erkennbar ist |

### Vorlagen

| Vorlage | Zweck |
|---|---|
| [Zuständigkeitstabelle](./templates/governance-raci-template.md) | je System und Pflicht, mit Stundenbudget |
| [Prüfturnus](./templates/review-cadence-template.md) | was wann läuft, und wer es anstößt |

Maschinenlesbar: [framework/simpleact-framework.json](./framework/simpleact-framework.json) · [llms.txt](./llms.txt)

## Verwandtes

- [Governance-Rahmenwerk](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework) — der Zusammenhang aller Teile
- [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist) — der Mindeststandard für Prüfpunkte
- [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) — wo die Zuständigkeit eingetragen wird
- [Vorfallmanagement](https://github.com/SimpleAct-Compliance/simpleact-incident-management) — Eskalation im Vorfall

## In Software umsetzen

[SimpleAct](https://simpleact.de) führt Zuweisungen, Freigabetore, Delegationen und wiederkehrende Prüfungen mit Protokoll: **[AI Governance](https://simpleact.de/ai-governance)**

## Stand und Lizenz

Zuletzt aktualisiert: 2026-10-03 · MIT — frei nutzbar, auch kommerziell. Keine Rechtsberatung.
