# Zuständigkeit je Klasse

Die Klasse bestimmt, **wer** zuständig wird — nicht nur, welche Pflichten gelten. Das ist die Spalte, die in Governance-Modellen fehlt.

Die Einstufung selbst liegt in der [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu).

## Wer je Klasse zuständig wird

| Klasse | Entscheidet | Erfüllt die Pflichten | Hauptaufwand |
|---|---|---|---|
| **Verboten** (Art. 5) | Geschäftsführung | Fachbereich stellt ein | Entscheidung dokumentieren, Alternativen |
| **Hochrisiko, Anbieter** | Geschäftsführung | Entwicklung, Compliance, QM | Projekt über Monate |
| **Hochrisiko, Betreiber** | Geschäftsführung | Fachbereich, Datenschutz | Aufsicht, Protokolle, ggf. Art. 27 |
| **Transparenzpflicht** (Art. 50) | Fachbereichsleitung | Produkt, Entwicklung | Kennzeichnung im Produkt |
| **Minimal** | Fachbereichsleitung | Eigentümer | Eintrag halten, Art. 4, Wiedervorlage |
| **Berührt Anhang III, Klasse offen** | **Geschäftsführung, nach rechtlicher Bewertung** | — | Bewertung, bevor es weiterläuft |

Die letzte Zeile ist die, die ein Governance-Modell braucht und die in Klassenübersichten nicht vorkommt: der Zustand **zwischen** Feststellung und Bewertung. Ohne diese Zeile wird ein Grenzfall vom Fachbereich entschieden.

## Der Zwischenzustand: nicht bewertet

Ein gültiges Ergebnis, mit Zuständigkeit:

| Feld | Inhalt |
|---|---|
| Status | nicht bewertet |
| Verantwortlich für die Bewertung | Person |
| Termin | |
| **Läuft das System in der Zwischenzeit?** | ja / nein, entschieden durch ___ am ___ |

Die letzte Zeile ist die eigentliche Governance-Entscheidung. Sie bleibt in der Praxis unausgesprochen — das System läuft einfach weiter —, und genau das macht sie später zu einem Versäumnis statt zu einer Abwägung.

## Art. 5: wer das prüft und wer entscheidet

Die Prüfung kann Compliance machen. Die Folge nicht.

| Schritt | Wer |
|---|---|
| alle zehn Praktiken durchgehen | Compliance oder Leitung |
| Treffer feststellen | dieselbe Stelle |
| **Betrieb einstellen** | Geschäftsführung — nicht delegierbar |
| Alternativen prüfen | Fachbereich mit Beschaffung |
| Nachweis der Umsetzung | Eigentümer |

Die letzte Zeile wird vergessen. Eine dokumentierte Abschaltentscheidung ohne Nachweis der Umsetzung ist in einer Prüfung die unangenehmste Konstellation überhaupt.

Besonders zu prüfen sind die zwei Praktiken, die in gekaufter Software vorkommen: **Emotionserkennung am Arbeitsplatz und in Bildungseinrichtungen**, und **ungezieltes Auslesen von Gesichtsbildern**. Beide erscheinen als Funktion in Analysewerkzeugen, ohne dass jemand sie bestellt hat.

## Art. 6 Abs. 3: nicht delegierbar

Die Ausnahme wirkt wie eine technische Einschätzung und ist eine Entscheidung mit Haftungsfolge.

| Schritt | Wer |
|---|---|
| die vier Tatbestände prüfen | Compliance mit Fachbereich |
| **Übernahmequote** erheben | Fachbereich oder IT |
| **Profiling-Frage** beantworten | Datenschutz |
| Bewertung dokumentieren und freigeben | Geschäftsführung |

Die Übernahmequote ist der Teil, der die Entscheidung trägt: Wird ein Vorschlag in 98 von 100 Fällen übernommen, ersetzt er die menschliche Bewertung praktisch — unabhängig davon, was im Ablaufdiagramm steht.

Und die Profiling-Frage ist eine eigene Zeile, weil ein Ja die Ausnahme ausschließt, unabhängig von allen vier Tatbeständen.

## Art. 50: Zuständigkeit im Produkt

Die Kennzeichnung muss im **laufenden System** sichtbar sein. Das macht die Zuständigkeit eindeutig:

| Aufgabe | Wer |
|---|---|
| Kennzeichnung umsetzen | Entwicklung |
| je Ansicht prüfen | Entwicklung, am Freigabetor |
| Nachweis mit Produktversion ablegen | Entwicklung |
| bei jedem Release erneut prüfen | Freigebender |

Die letzte Zeile ist entscheidend: Art. 50 wird bei Releases am häufigsten unbemerkt gebrochen, weil eine überarbeitete Oberfläche den Hinweis verliert — am häufigsten in der Mobilansicht.

## Art. 4: die laufende Zuständigkeit

| Aufgabe | Wer | Turnus |
|---|---|---|
| Personenkreis je System führen | Eigentümer | laufend |
| Schulung organisieren | Personalbereich oder Compliance | jährlich und bei Zugang |
| Inhalt systembezogen halten | Fachbereich mit Entwicklung | bei Modellwechsel |

Die letzte Zeile wird übersehen: Eine Schulung, die erklärt, wie das alte Modell irrt, passt nach einem Modellwechsel nicht mehr.

## GPAI: eine Beschaffungszuständigkeit

Die Pflichten treffen den Modellanbieter. Für die eigene Organisation folgt daraus eine Frage an die **Beschaffung**: Erfüllt er sie, und liefert er die Unterlagen, auf die die eigene Dokumentation aufbaut?

Ein Nein ist ein Befund gegen den Anbieter — zu dokumentieren mit Datum der Anfrage, und zuzuweisen an die Beschaffung, nicht an die Compliance.

## Weiter

[Das Betriebsmodell](./governance-operating-model.md) · [Freigabetore](./go-live-gates-and-delegation.md) · [Zuständigkeitstabelle](../../templates/governance-raci-template.md)
