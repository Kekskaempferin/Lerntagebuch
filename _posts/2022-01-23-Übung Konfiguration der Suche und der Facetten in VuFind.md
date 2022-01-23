---

titel: "Übung: Konfiguration der Suche und der Facetten in VuFind"

date: 2022-01-23

---

**Übung Konfiguration Facetten VuFind** <br>
Gleich zu Beginn der Übung stosse ich auf das erste Hindernis. Ich kann die Datei searches.ini nicht finden. Eine Mail an die Dozierenden und eine sehr hilfreiche und schnelle Antwort hat zum Glück Klarheit gebracht. Ich habe im falschen Verzeichnis gesucht. Dabei dachte ich, ich hätte alles doppelt und dreifach kontrolliert. Allerdings gab es da neben /usr/local/vufind/local/config/vufind auch noch das Verzeichnis /usr/local/vufind/local/config/vufind, wo alle Dateien drin gewesen wären und woraus ich sie nur ins erste Verzeichnis hätte kopieren müssen. Hab ich dann nach erhalt der Antowortsmail auch verstanden und geschafft. Endlich kann ich loslegen!
<br><br>
Der Herr im Video scheint enorm kompetent und die Art und Weise, wie er erklärt passt mir ganz gut. Ich habe gleich zu Beginn in der Datei searches.ini einige Dinge mit ausprobiert z.B. die Anpassung der Reihenfolge und Bezeichnungen des Drop Downs in der einfachen Suche oder die Anzahl angezeigter Ergebnisse sowie das Dropdown, um diese Zahl individuell zu ändern. In searches.ini werden die Konfigurationen rund um die Suche und die Ergebnisliste gemacht. Dann hat das Video in die Datei facets.ini gewechselt. Auch hier habe ich einige Dinge gemäss dem Video ausprobiert. Ich habe zum Beispiel die Themen Facetten, die über der Ergebnisliste angezeigt wurde, zu den anderen Facetten an den rechten Rand verschoben und die Anzahl angezeigten Facetten verändert. In der Datei searchspecs.yaml habe ich nichts verändert, weil mir das dann doch etwas zu kompliziert wurde. Man könnte dort aber anpassen, wie VuFind die Relevanz der Suchtreffer bewertet, in dem man den Komponenten Zahlenwerte gibt bzw. diese verändert. Selbst der Herr im Video sagt zu dieser Funktion aber «there’s as much art as science in that process», weshalb ich lieber ihm zugesehen habe. 
<br><br>
Die Übung fand ich sehr spannend. Ich fand es interessant mal von der «anderen» Seite her zu sehen, wie die Fonfiguration eines Discovery Systems funktioniert. Ich muss zugeben, ich bin auch etwas überrascht, wie einfach es ist. Ich hätte sehr viel mehr Coding erwartet, schlussendlich war es aber vor allem Semikolon löschen und einfügen, Zeilen verschieben und Nummern und Strings ändern. Aber er sagte im Video ja auch, dass es Möglichkeiten für eigene Codes gibt, beispielsweise wenn eine Suche keine Resultate ausspuckt.  
