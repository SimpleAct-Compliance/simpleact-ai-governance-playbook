# Das Betriebsmodell

Drei Rollen je System. Die Abgrenzung ist wichtiger als die Namen: Was eine Rolle **nicht** darf, entscheidet, ob das Modell trägt.

## Eigentümer

**Wer:** eine Person im **Fachbereich**, der das System benutzt.

**Aufgabe:** den Eintrag aktuell halten; melden, wenn sich Einsatzzweck, Nutzerkreis oder Datenlage verschieben.

**Darf nicht:** die eigene Arbeit freigeben.

**Warum Fachbereich und nicht Compliance:** Eine zentrale Stelle, die achtzig Einträge pflegt, kann bei keinem sagen, ob er noch stimmt. Sie kann die Felder ausfüllen — aber sie merkt nicht, dass der Vertrieb das Werkzeug seit drei Monaten auch für Angebote benutzt.

**Was die Rolle braucht:** ein **Stundenbudget**, benannt. Und einen Meldeweg, der weniger Aufwand ist als es zu lassen.

## Prüfer

**Wer:** eine Person, die nicht der Eigentümer ist. In kleinen Organisationen Datenschutz, Compliance oder die Leitungsebene — auch extern besetzbar.

**Aufgabe:** nachsehen, ob der Eintrag **stimmt** — nicht, ob er gefüllt ist. Dazu gehört, einmal das System selbst anzusehen.

**Darf nicht:** mit dem Eigentümer identisch sein.

**Die Frage, die die Rolle rechtfertigt:** nicht „ist das Feld gefüllt", sondern „zeig mir, wo das im System steht". Ein Prüfer, der Vollständigkeit prüft, ist ein Formularkontrolleur; der Fehler, den er finden soll, ist eine Angabe, die einmal stimmte.

## Freigebender

**Wer:** die Person, die über die Inbetriebnahme entscheidet — nach Risiko gestaffelt.

**Aufgabe:** vor Inbetriebnahme prüfen, ob die Maßnahmen **wirksam** sind, nicht ob sie geplant sind.

**Darf nicht:** unterschreiben, ohne nachzusehen.

Ausführlich: [Freigabetore und Delegation](./go-live-gates-and-delegation.md)

---

## Zuschnitt nach Größe

| Größe | Praktikabler Zuschnitt |
|---|---|
| unter 20 Beschäftigte | Eigentümer im Fachbereich; Geschäftsführung prüft und gibt frei |
| 20 bis 100 | Eigentümer im Fachbereich; Datenschutz oder Compliance prüft; Leitung gibt frei |
| über 100 | drei getrennte Rollen; Freigabe nach Risikoklasse gestaffelt |

**Nicht verhandelbar ist nur eines:** Eigentümer und Prüfer sind nicht dieselbe Person. Alles andere lässt sich zusammenlegen.

Wo auch das nicht geht — drei Leute, einer macht alles —, gilt die abgeschwächte Form, und zwar **ausdrücklich dokumentiert**: Die Umsetzende prüft, und eine zweite Person sieht die Prüfung nach. Das ist weniger wert als eine echte Trennung und mehr als nichts.

Was nicht geht, ist die Trennung zu **behaupten**. Wenn in einem Prüfprotokoll bei Umsetzung und Prüfung derselbe Name steht, ist das ein nachvollziehbarer Zustand. Wenn dort zwei Namen stehen und tatsächlich eine Person gearbeitet hat, ist das ein anderer Befund.

## Was zentral geht und was nicht

| Aufgabe | Zentral | Warum |
|---|---|---|
| Fristen kennen, Weg planen | ja | einmalige Wissensarbeit |
| Art. 5 einmal durchgehen | ja | einmalig |
| Suche nach Systemen anstoßen | ja | koordinierend |
| Einstufungen durchführen | ja, mit Zuarbeit | braucht Angaben aus dem Fachbereich |
| Schulung organisieren | ja | |
| **Inventareinträge aktuell halten** | **nein** | nur der Fachbereich merkt Veränderungen |
| **Aufsicht ausüben** | **nein** | dort, wo die Ausgabe anfällt |

Die beiden Nein-Zeilen sind der Kern dieses Modells. Wer sie zentralisiert, bekommt ein Register, das nach einem halben Jahr nicht mehr stimmt, und eine Aufsicht, die es nur auf dem Papier gibt.

## Die Zuständigkeitstabelle als Diagnose

Die nützlichste Auswertung des ganzen Modells wird fast nie gemacht: **die Tabelle nach Häufigkeit sortieren.**

| Befund | Bedeutet |
|---|---|
| eine Person steht achtzehnmal als Eigentümer | Überlast, die sonst erst bei der Kündigung auffällt |
| ein Eintrag hat keinen Namen | eine Lücke mit Adresse |
| Prüfer und Eigentümer sind identisch | formale Freigaben |
| ein Freigebender taucht nie in Protokollen auf | das Tor wird nicht begangen |

Die erste Zeile ist der häufigste und der folgenreichste Befund. Die richtige Reaktion ist eine **Ressourcenentscheidung**, nicht eine Umverteilung derselben Last auf dieselbe Person.

## Vertretung

Für jede Rolle eine Vertretung, mit Namen. Die praktische Probe: Wenn der Eigentümer vier Wochen im Urlaub ist und der Anbieter in dieser Zeit das Modell tauscht — wer bemerkt es?

Wenn die Antwort „niemand" lautet, ist die Vertretung nicht benannt, sondern angenommen.

## Was die Geschäftsführung nicht delegieren kann

| Entscheidung | Warum oben |
|---|---|
| wer zuständig ist, mit **Stundenbudget** | Ressourcenentscheidung |
| ob ein System mit offenem Befund weiterläuft | Risikoentscheidung |
| ob ein Werkzeug wegen Art. 5 abgeschaltet wird | nicht abwägbar, aber zu treffen |
| ob externe Unterstützung geholt wird | Ressourcenentscheidung |

Die zweite Zeile bleibt in der Praxis unausgesprochen. Ein System läuft weiter, obwohl ein Befund offen ist — das ist zulässig und gehört als Entscheidung festgehalten, nicht als Versäumnis entstehen gelassen.

## Weiter

[Freigabetore und Delegation](./go-live-gates-and-delegation.md) · [Eskalation](./escalation-and-decision-logic.md) · [Zuständigkeitstabelle](../../templates/governance-raci-template.md)
