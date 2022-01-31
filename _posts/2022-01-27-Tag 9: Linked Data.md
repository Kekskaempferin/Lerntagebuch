---

title: "Tag 9: Linked Data"

date: 2022-01-27

---

**BIBFRAME** <br>
BIBFRAME wird seit 2012 vor allem von der Library of Congress basierend auf FRBR und RDA entwickelt. Seit 2016 gibt es die aktuelle Version BIBFRAME 2.0. BIBFRAME wird aber immer noch weiterentwickelt. BIBFRAME besteht aus dem BIBFRAME Model und dem BIBFRAME Vocabulary. Das Model beschreibt was unterschieden wird und das Vocabulary beschreibt wie dieses Objekt beschrieben wird. Wie FRBR unterscheidet BIBFRAME verschiedene Entitäten: Werk, Manifestation und das einzelne Exemplar. Die verschiedenen Entitäten haben wiederum Eigenschaften, wie zum Beispiel für das Werk: Agent für Personen und Körperschaften, Subject für Schlagworte oder Themen und Events wie die Publikation inkl. seiner Eigenschaften. Die Idee hinter Linked Data ist Institutionsübergreifend eine gigantische Wolke mit Daten zu schaffen, in der alles untereinander verknüpft ist. 

Wie die Beschreibungsklassen und die Eigenschaften verwendet und beschrieben werden, beschreibt das BIBFRAME Vocabulary in seiner Ontologie. Die Klassen und Eigenschaften sind hierarchisch aufgebaut und besitzen diverse Unterklassen. Grundsätzlich übernimmt aber BIBFRAME Vocabulary aber viel aus RDA, schliesslich macht es keinen Sinn, alles neu selbst zu erfinden. 

Die Hauptunterscheidung zwischen BIBFRAME und MARC21 ist, das BIBFRAME sehr stark versucht, Redundanz zu vermeiden und wo immer möglich Verknüpfungen zwischen verschiedenen Datensätzen herzustellen. Statt den Fokus auf die einzelnen Datensätze zu legen, achtet BIBFRAME stark auf die Beziehungen zwischen den verschiedenen Ressourcen. Passend dazu haben wir in diesem Semester auch das Fach Semantische Systeme, wo wir selbst einfachere Ontologien erstellen. Dadurch kann ich mir gut vorstellen, wie dieses Prinzip funktionieren soll und was das für einen Bibliothekskatalog bedeuten könnte. Man müsste viel weniger auf exakte Phrasen oder mit Schlagworten achten, sondern es werden auch logische Beziehungen und Abfragen möglich. 

**Records in Context RiC** <br>
Auch RiC basiert auf dem Linked Data Prinzip und wie ich das sehe, ist es wie BIBFRAME als Ontologie gedacht. Zumindest gibt die Instanz Thing aus dem ica-File diesen Eindruck, da sie stark an die Klasse owl:Thing erinnert. Was es vor allem zu BIBFRAME unterscheidet ist die Bedeutung der Provenienz, die natürlich im Archivbereich schon seit langem eine wichtige Bedeutung innehält. 

**Suchanfragen mit SPARQL am Beispiel des Wikidata Query Service** <br>
Schade, dass die Zeit für die SPARQL Abfragen nicht mehr gereicht hat. Durch das Lernen für das Fach Semantische Systeme befasse ich mich gerade sehr stark SPARQL. Ich versuche mich einfach mal selbst an einigen Abfragen. Ich finde es aber schwierig  Abfragen zu formulieren, wenn ich die Ontologie nicht wirklich kenne. Die Autovervollständigung ist dabei schon hilfreich, aber halt auch nur begrenzt. Man muss trotzdem ungefähr wissen, wie ein bestimmtes Property, eine bestimme Klasse oder ein bestimmtes Individuum heisst. Die Geschichte mit den Codes statt Texten gibt dem ganzen noch einen komplizierteren Charakter. Ich habe es aber doch geschaft einige Abfragen zu machen. Beispielsweise habe ich nach Getränken gesucht, die eine Limette beinhalten. Beinhalten war aber nicht ganz das passende Property bzw. ich hätte vermutlich noch mehr Angaben in die Anfrage machen sollen, weil herausgekommen ist auch der Eintrag zum Limetten-Schnitz. Naja … die Richtung stimmte …
