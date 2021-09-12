# 1. Textbasierte Anyalyse von Bundestagsreden
Dies ist ein Studierendenprojekt, welches im Rahmen des Moduls 'Text Analytics' von Prof. Dr. Albrecht an der TH Nürnberg entstanden ist. 
Die Notebooks sind aufgebaut wie eine Zusammenfassung für einen Kunden (hier die Bundeszentrale für politische Bildung). 

# 2. Bewertung des Projekts
Das Projekt ist zwar abgeschlossen, jedoch nicht perfekt beendet. Um in Zukunft daran zu arbeiten bzw. um für Offenheit zu sorgen, folgt hier die Bewertung des Projekts. Um es abzukürzen, werden nur die Probleme aufgelistet (Stand Sept. 2021).

## 2.1 Code- & Notebook-Qualität
- Notebook 'Textaufbereitung': Händische Bereinigung fehlt teilweise.
- Es fehlt allgemein teilweise der Ausarbeitungscharakter, d.h. ein paar mehr Erläuterungen über die Ziele, Interpretationen und Auswertungen der einzelnen Analysen.

## 2.2 Extraktion & Datenaufbereitung
- siehe Klassifikation.

## 2.3 Klassifikation
- Es fehlt die Interpretation, warum etwas falsch klassifiziert wird oder was man aus den Texten ablesen kann.
- Es gibt einen schwerwiegenden Bug in der Datenaufbereitung. Beim 'Splitten' der Reden wurde vergessen, die Kommentare (z.B. "Und als Nächstes, der Redner von der SPD") zu entfernen, so konnte das Modell ziemlich gut die einzelnen Reden den Parteien zuordnen (Reihenfolge der Reden). Das müsste noch gefixt werden.

## 2.4 Benotung
Das Projekt wurde insgesamt mit einer 1,7 benotet. 
