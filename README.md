# big_data_lab_cluster
Im Rahmen eines Projektes im Modul Big Data Lab Cluster der Hochschule Luzern wurden Datensätze zu den Luftqualitätsmessungen der Stadt Zürich vom 01.01.2014 bis 30.05.2021 genauer analysiert. Diese Daten wurden wie Big Data behandelt und mit entsprechend passenden Tools und Techniken strukturiert bearbeitet. 

**Technik**

Das Projekt hat zum Ziel verschiedene Auswertungen unter Anwendung des vermittelten Wissens im Unterricht zu erstellen. Dabei sollen mindestens die Techniken Spark DF, Spark SQL und Zeppelin verwendet werden. In diesem 109 MB grossen Projekt zu den Luftqualitätsmessungen wird zusätzlich noch mit shell, curl und JQ gearbeitet. 

Die Daten wurden direkt von der Stadt Zürich bezogen und wurden danach auf einem Cluster, welches mit mehreren Linux Containern realisiert wurde, abgespeichert. Für die Speicherung werden die Daten in acht MB grosse Blöcke unterteilt und auf drei verschiedenen Datanodes in einem Hadoop Cluster gespeichert. Des Weiteren wurde eine Datenbank zur Abfragung der Daten erstellt. 

**Auswertungen** 

Die Auswertungen untersuchten mehrheitlich die Entwicklung des krebserregenden und erbgutschädigenden Schadstoff PM10. Diese Teilchen mit einem Durchmesser von einem hundertstel Millimeter entstehen unteranderem durch Abriebteilchen von Pneus und Strassenbelag. 

Eine Auswertung der Daten zeigt, dass die Stadt Zürich den vorgegebenen durchschnittlichen Grenzwert pro Jahr für die Belastung von PM10 einhält. Jedoch gibt es Mängel bei der Einhaltung des 24h-Mittelwertes. Die Belastung von PM10 darf gemäss Grenzwert diesen Mittelwert nur einmal im Jahr übersteigen. In fast allen untersuchten Jahren, ausser in den Jahren 2019 und 2020, wurde dieser mehr als einmal überschritten. Somit sollten dringend Massnahmen zur Reduktion der PM10-Belastung definiert werden. 

Ferner ist aufgefallen, dass jeweils am Montag die PM10-Werte tief sind und kontinuierlich bis Samstag steigen. Am Sonntag erholt sich die Luft wieder und die Messwerte sinken. Dieser Rückgang am Sonntag könnte mit einem reduzierten Verkehrsaufkommen erklärt werden. Die Auswertung der Daten auf den durchschnittlichen Tagesverlauf zeigt, dass die Belastung um ca. fünf Uhr morgenssteigt und der Höchstwert um neun Uhr vormittags erreicht wird. Um neun Uhr beträgt dieser Wert 22 und sinkt danach langsam ab. 

Konkret sollten Massnahmen zur Reduktion des PM10 Schadstoff getroffen werden, um den Grenzwert des 24h-Mittelwerts langfristig einzuhalten.
