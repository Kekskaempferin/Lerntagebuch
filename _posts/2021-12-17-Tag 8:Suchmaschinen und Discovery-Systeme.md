---

titel: "Tag 8: Suchmaschinen und Discovery-Systeme"

date: 2021-12-17

---
**Installation VuFind**
Als Auftrag für die heutige Sitzung sollten wir das Discovery System VuFind auf unserer VM installieren. Das hat, glaube ich, ganz gut geklappt. Irgendwann gegen Ende hatte ich ein Problem, habe den Fehler aber nicht gefunden bzw. wusste nicht, was zu tun ist, um es zu finden und zu korrigieren. Stattdessen habe ich alles gelöscht und von vorne begonnen. Jetzt sieht es gut aus. Ich hoffe das passt jetzt also … Für die Übung zu den Facetten bin ich leider nicht mehr gekommen, das Problem mit der Installation hat eine Menge Zeit in Anspruch genommen. Ich werde diese später nachholen. 

**Solr**
Solr ist ein Industriestandart was Suchmaschinen angeht. Auf ihm basiert das Discovery System VuFind oder auch Primo von Ex Libris. Ich war überrascht zu hören, dass auch die Suche von Netflix auf Solr basiert. Die Netflix-Suche scheint mir so anders zu sein als die Discovery-Systeme aus dem bibliothekarischen Bereich. Andererseits ist Solr ja lediglich die Basis also wer weiss wie ähnlich sie sich wirklich sind.  Solr ist ein sogeannter Suchindex, was nicht verwechselt werden darf mit Datenbanken wie z.B. MySQL. Suchindexe wie Solr eignen sich für flache Dokumente und lexikalische Suchen mit weitgehend statischen Daten. Es findet keine Konsistenzprüfung statt. Suchindexe sind auf Retrieval ausgelegt. Hingegen die Suche in einer Datenbank läuft alleine über das Abgleichen der einzelnen Glyphen mit den Datensätzen. Dafür sind Datenbanken in der Lage mit relationalen Daten, die sich auch oft verändern umzugehen. Das müssen sie auch denn das Verändern gehört zu ihrem Hauptzweck dazu. Datenbanken sind ausgelegt Daten zu speichern aber auch sie zu erstellen, zu lesen, upzudaten und zu löschen. 

**Übung Suche VuFind vs Solr**
Logischerweise liefern beide Suche das gleiche Resultat, schliesslich basiert VuFind auf Solr und demnach sind die gleichen Daten verfügbar. Solr sucht aber nur genau das, was der Benutzer als Suche eingeben hat. VuFind schmückt die Anfrage des Nutzers weiter aus, um die Ergebnisse möglichst komfortabel zu gestalten. Die Query wird dadurch länger als bei Solr, obwohl der Benutzer das gleiche eingegeben hat. So ist eine Sortierung nach Relevanz in VuFind Standard. Dazu kommt die Markierung der Suchbegriffe in der Trefferliste oder die praktische Autocomplete-Funktion bei der Sucheingabe. Auch die Präsentation der Ergebnisse ist in VuFind angenehmer als in Solr. Neben der Sortierung nach Relevanz und der Markierung der Suchbegriffe liefert VuFind eine gelayoutete Version der Treffer. Solr schickt ganz einfach die Datensätze im JSON Format zurück. Das ist zwar nicht so schön und etwas unübersichtlich, aber dafür erhält man mehr Angaben zum Datensatz als in VuFind.

** Übung Datenimport**
Weil ich mir unsicher war, ob alle meine eigenen Daten fehlerfrei sind und für die Integration funktionieren, habe ich von Anfang an mit den Beispieldaten gearbeitet. Nach einigen Startschwierigkeiten hat die Integration dann aber funktioniert. Ich hatte zu Beginn Mühe, genau zu erkennen, wo ich was ändern muss, damit der Import klappt, sowohl in der Datei, wie auch im Terminal-Befehl. Schlussendlich hat dann aber alles geklappt, bis auf die Daten von ArchiesSpace und DSpace, was ja aber auch korrekt war so. Warum das aber nicht funktioniert hat, hätte ich nicht erkennen können und verstehe ich auch jetzt noch nicht 100%. 
