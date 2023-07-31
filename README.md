# Forschungsseminar
Dies ist das Projekt von Jan Moormann  und Sophia Bühl im Forschungsseminar NLP.

## Project Description
Dieser Code ist Teil eines Uni-Projektes. Im ersten Schritt werden alle deutschen Wikipedia-Artikel herunterladen und mit einer Klassifikation vorhergesagt, ob es sich bei einem Artikel um einen "exzellenten Artikel“ handelt oder nicht. Die zweite Aufgabe besteht darin, nur die "exzellenten" Artikel“ zu extrahieren und einige relevante Schlüsselwörter aus dem Artikel vorherzusagen. Die Ergebnisse wurden evaluiert und miteinander verglichen.

Das Notebook [data](data.ipynb) beinhaltet das Herunterladen und das Abspeichern aller Wikipedia-Artikel. Es ist das Hauptnotebook und teilt die Artikel in exzellent und nicht exzellent auf. Zudem ist eine erste Datenvorbereitung enthalten.

Für Code-Blöcke, die viel Zeit benötigen, wurde jeweils ein Subset erstellt. Damit sind die Ergebnisse reproduzierbar und der Code zeitlich absehbar ausführbar. Wie damit verfahren wird, ist im jeweiligen Notebook ausgiebig kommentiert.

Die erste Aufgabe (die Klassifikation) befindet sich im Notebook [Klassifikation](classification.ipynb). In diesem wird eine Klassifikation mit einem Decition Tree und einem Bert Classifier zurchgeführt. Beide Ansätze werden nach einer jeweiligen Evaluation miteinander verglichen.

Die zweite Aufagbe (die Schlüsselwörter) befindet sich im Notebook [Schlüsselwörter](keywords.ipynb). Hierbei werden die Daten entsprechend der Aufgabe weiter aufbereitet. Es wird ein statistischer Ansatz mit dem Zählen von Wörtern und YAKE und KeyBert miteinander verglichen und evaluiert.
