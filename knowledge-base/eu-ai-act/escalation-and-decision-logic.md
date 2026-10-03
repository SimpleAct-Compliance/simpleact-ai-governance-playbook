# Eskalation und Entscheidungen

Die meisten Eskalationswege werden nie benutzt. Nicht, weil nichts passiert, sondern weil nicht festgelegt ist, **was** eskaliert wird und **was dann geschieht**.

## Die vier Auslöser

| Auslöser | An wen | Wie schnell |
|---|---|---|
| **Art.-5-Treffer** | Geschäftsführung | sofort — nicht abwägbar |
| **Befund zum dritten Mal verschoben** | Leitungsebene über dem Verantwortlichen | mit der Monatsdurchsicht |
| **System läuft weiter, obwohl ein Befund offen ist** | Geschäftsführung, als Entscheidung | bei Feststellung |
| **Aufsichtskennzahl fällt gegen Null** | Fachbereichsleitung | mit der Monatsdurchsicht |

Zwei davon stehen in keinem gängigen Governance-Modell.

### Der dreimal verschobene Befund

Ein Befund, dessen Termin dreimal verschoben wurde, ist keine offene Aufgabe mehr. Er ist eine **Entscheidung, die niemand ausgesprochen hat** — nämlich die, dass dieser Punkt nicht bearbeitet wird.

Das gehört eskaliert, und zwar nicht als Vorwurf: Meist bedeutet es, dass die zuständige Person die Zeit nicht hat. Die richtige Reaktion ist eine **Ressourcenentscheidung**, nicht eine vierte Terminverschiebung.

Voraussetzung dafür ist eine Spalte **Verschiebungen** im Befundprotokoll. Ohne sie bleibt der Vorgang unsichtbar, weil jeder einzelne Aufschub begründet wirkt.

### Die fallende Aufsichtskennzahl

Wie viele Ausgaben wurden im letzten Monat tatsächlich geändert oder verworfen? Fällt diese Zahl von 40 auf 3, ist die menschliche Aufsicht formal geworden — **ohne dass jemand eine Entscheidung getroffen hätte**.

Das ist kein Vorwurf an den Fachbereich, sondern meist eine Folge von Mengenwachstum. Und es ist ein Befund, der ohne diese Kennzahl niemandem auffällt, bis er in einer Prüfung oder einem Vorfall sichtbar wird.

## Was eine Eskalation enthalten muss

Eine Eskalation ohne Entscheidungsvorschlag erzeugt eine Rückfrage, nicht eine Entscheidung.

| Feld | Inhalt |
|---|---|
| Sachverhalt | in drei Sätzen |
| warum eskaliert | welcher der vier Auslöser |
| **was entschieden werden soll** | konkret, mit Alternativen |
| Risiko bei jeder Alternative | einschließlich der Alternative, nichts zu tun |
| Frist | bis wann die Entscheidung gebraucht wird |
| wer es vorlegt | Person |

Die dritte Zeile ist die, die über die Wirksamkeit entscheidet. „Hier ist ein Problem" erzeugt Nachfragen; „soll das System bis zum 30.11. weiterlaufen, oder wird es ausgesetzt — Risiko A gegen Risiko B" erzeugt eine Entscheidung.

## Was eine Entscheidung festhalten muss

| Feld | Warum |
|---|---|
| Entscheidung | |
| **Person**, nicht Gremium | in einer Prüfung wird nach einer Person gefragt |
| Datum | |
| Grundlage | welche Informationen vorlagen |
| Alternativen, die verworfen wurden | zeigt, dass abgewogen wurde |
| Befristung oder Wiedervorlage | eine unbefristete Entscheidung wird nie überprüft |

Die fünfte Zeile ist der Teil, der eine Entscheidung belastbar macht. Eine festgehaltene Abwägung — auch eine, die sich später als falsch erweist — ist in einer Prüfung wesentlich besser als ein Ergebnis ohne Begründung.

## Die Entscheidungen, die typisch unausgesprochen bleiben

| Entscheidung | Was ohne Festhalten daraus wird |
|---|---|
| System läuft weiter mit offenem Befund | ein Versäumnis |
| Lücke bleibt bewusst offen | eine vergessene Lücke |
| Anbieterlücke wird in Kauf genommen | ein eigener Mangel |
| Aufwand übersteigt den Nutzen | eine nicht erfüllte Pflicht |

In allen vier Fällen ist die Entscheidung selbst zulässig. Was sie zum Mangel macht, ist das Fehlen von Person und Datum.

## Eskalation im Vorfall

Ein eigener Weg, mit zwei Fristen, die nicht vermengt werden dürfen:

| | Art. 73 AI Act | Art. 33 DSGVO |
|---|---|---|
| Gegenstand | schwerwiegender Vorfall bei einem Hochrisikosystem | Verletzung des Schutzes personenbezogener Daten |
| Adressat | Marktüberwachungsbehörde | Datenschutzaufsicht |
| Frist | gestaffelt nach Art des Vorfalls | **72 Stunden ab Kenntnis** |

Ein Ereignis kann beide auslösen. Die 72 Stunden laufen ab **Kenntnis**, nicht ab Aufklärung — eine unvollständige Meldung innerhalb der Frist ist richtig, eine vollständige danach ist verspätet.

**Was im Playbook festgelegt sein muss:** wer die Kenntnis hat, wer sie weitergibt, und an wen. Der häufigste Fehler ist, dass der Support eine Meldung als Qualitätsproblem bearbeitet, während die Frist läuft.

Ausführlich: [Vorfallmanagement](https://github.com/SimpleAct-Compliance/simpleact-incident-management) · [Datenschutzverletzungen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-data-breach-management)

## Warum Eskalationswege nicht benutzt werden

Vier Gründe, alle behebbar:

| Grund | Gegenmittel |
|---|---|
| nicht klar, **was** eskaliert wird | die vier Auslöser benennen |
| nicht klar, **an wen** | Namen, nicht Gremien |
| Sorge, als Überbringer dazustehen | ausdrücklich sagen, dass Eskalation erwartet wird |
| frühere Eskalationen blieben ohne Ergebnis | jede Eskalation bekommt eine Entscheidung, auch ein dokumentiertes Nein |

Die vierte ist die wirksamste Ursache und die am seltensten erkannte: Wer zweimal eskaliert hat und keine Antwort bekam, eskaliert nicht wieder.

## Weiter

[Freigabetore und Delegation](./go-live-gates-and-delegation.md) · [Prüfturnus](./review-cadence-logic.md) · [Das Betriebsmodell](./governance-operating-model.md)
