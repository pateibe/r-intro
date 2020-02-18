# Praktische Einführung in statistische Berechnungen, Datenvisualisierung und Berichterstellung mit R

Workshop im Rahmen des Forschungskolloqiums vom 20.02.2020  der aF&E Physiotheapie an der Berner Fachhochschule Gesundheit.


Patric Eichelberger - patric.eichelberger@bfh.ch

# Hintergrund

Die freie Sprache [R](http://www.r-project.org) für statistische Berechnungen wird im Fachbereich Physiotherapie der Berner Fachhochschule Gesundheit im BSc Studiengang bereits seit mehreren Jahren und im MSc Studiengang seit dem Herbstsemester 2019 im Statistikunterricht eingesetzt. Nicht zuletzt darum, weil es sich um Open Source Software handelt und diese unentgeltlich verwendet werden kann. Um die Studierenden in ihren Abschlussarbeiten im Bereich der angewandten Statistik optimal unterstützen zu können ist es notwendig, dass die verantwortlichen Betreuungspersonen ebenfalls über das notwendige Wissen in der Anwendung von R verfügen.

R wurde über die letzten Jahre ein de facto Standard im Bereich den Datenwissenschaften und wurde auch in der Wirtschaft und anderen Forschungsgebieten immer wichtiger. Speziell wenn es um die reproduzierbare Analyse von grossen Datensätzen geht. [IEEE](https://spectrum.ieee.org/computing/software/the-top-programming-languages-2019) bewertete im Jahr 2019 R als die 5. wichtigste Programmiersprache für entsprechende Fachpersonen. Durch die grosse Community hinter dem Open Source Projekt besteht eine hervorragende Dokumentation im Netz und es fliessen neueste Methoden entsprechend schnell in die Programmiersprache ein. Diese sind über unzählige Pakete verfügbar. So bietet R auch die wohl besten freien Möglichkeiten für die Datenvisualisierung und die Erstellung von Berichten zu statistischen Analysen. R findet auch an der BFH mittlerweile breite Anwendung und für interessierte Personen ist es sehr empfehlenswert sich der [BFH R User Group](https://lists.bfh.science/listinfo/bfh-r-users) anzuschliessen um sich weiterzubilden und Know-How auszutauschen. Gewöhnungsbedürftig für User aus dem nicht-technischen Umfeld dürfte die Tatsache sein, dass R grundsätzlich eine Kommandozeilenanwendung ist und standardmässig nicht über eine grafische Benutzerschnittstelle verfügt. Dem schafft unter anderem das Open Source Projekt [Jamovi](http://www.jamovi.org) Abhilfe, indem es eine grafische Benutzerschnittstelle in SPSS Manier bereitstellt. Es wird stetig weiter entwickelt und hat den Anspruch einfache Anwendbarkeit mit der Leistungsfähigkeit von R zu kombinieren und damit die Lücke zwischen Forschern und Statistikern zu schliessen. Wir verwenden Jamovi seit dem FS2019 im Unterricht auf Bachelorstufe, wo sich die Applikation sehr bewährt.

# Ziele

Dieser Workshop hat nicht zum Ziel aus den Teilnehmenden Anwendungsexpertinnen und -experten zu machen. Das wäre in der zur Verfügung stehenden Zeit schlicht weg nicht möglich. Vielmehr soll anhand eines konkreten und einfachen Beispiels aufgezeigt werden, welche Vor- und Nachteile R und Jamovi bieten und wie die beiden Tools für die einfache Datenanalyse angewendet werden können. Zudem soll der Workshop Grundlagenwissen vermitteln um den Teilnehmenden den Einstieg in die Nutzung von R in der Lehre und in deren eigenen Forschungsprojekten zu vereinfachen.

# Vorbereitung

Alle Teilnehmenden bringen optimalerweise ihren eigenen Rechner mit, um während des Workshops selbstständig an den Übungen zu arbeiten. Damit wir die Zeit für den Workshop optimal nutzen können bitte ich euch, euren Rechner bereits im Vorfeld entsprechend vorzubereiten. Also die nötigen Softwarepakete zu installieren. Diese umfassen die Anwendungen [Jamovi](https://www.jamovi.org), [R](https://www.r-project.org) und [RStudio](https://rstudio.com), welche wir alle drei nutzen werden. Nicht zwingend aber nützlich, ist es beim Umgang mit Quellcode einen leistungsfähigen Texteditor zu installieren, welcher Syntax-Highlighting für verschiedene Programmiersprachen unterstützt. Standard-Texteditoren, die mit dem Betriebssystem mitinstalliert werden, unterstützen dies in aller Regel nicht. Es gibt sehr gute Editoren unter Open Source Lizenzen. Sehr zu empfehlen ist zum Beispiel [Visual Studio Code](https://code.visualstudio.com/), welcher plattformübergreifend funktioniert (Windows, macOS, Linux).

## Unterlagen

Die gesamten Unterlagen dieses Workshops sind auf dem Github Repository [https://github.com/pateibe/r-intro](https://github.com/pateibe/r-intro) zu finden.

# Nützliche Ressourcen

## Web

- [r-project.org](https://r-project.org) - Offizielle Website R-Projekt
- [rstudio.com](https://rstudio.com) - Website RStudio IDE
- [tutorialspoint.com](https://www.tutorialspoint.com/r/index.htm) - Tutorials für R und viele weitere Programmiersprachen
- [jamovi.org](https://www.jamovi.org) - Website des Jamovi Projekts mit Blog und (Video-) Tutorials (jamovi.org > resources > user guide)
- [statmethods.net](https://www.statmethods.net/)

## Bücher

- A. Field, J. Miles und Z. Field, Discovering Statistics using R. London: SAGE Publications Ltd., 2012.
- I H. Wickham und G. Grolemund, R for Data Science. O’Reilly UK Ltd., 2017. (freies E-Book auf https://r4ds.had.co.nz/)
- I DJ Navarro und DR Foxcroft, learning statistics with jamovi: a tutorial for psychology students and other beginners. Version 0.70). DOI: 10.24384/hgc3-7p15. (E-Book).
