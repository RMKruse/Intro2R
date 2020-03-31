# Einführung in R Grundlagen

Dieses Skript ist als Teil der Bachelorveranstaltung Statistik der Wirtschaftswissenschaftlichen Fakultät an der Universität Göttingen entstanden und soll Studenten helfen auf eine einfache und direkte Art und Weise die wichtigsten Funktion der Statischen Programmiersprache **R** zu verstehen und anwenden zu können. Der Inhalt soll des Weiteren allen Studierenden helfen welche Interesse oder Fragen hinsichtlich **R**-Programmierung haben.

Die aktuellste Version des Skriptes sowie die unterliegenden Source-Files sind im Github-Repository ["intro2r"](https://github.com/RMKruse/intro2r) zu finden.

Dieses Buch wurde in [Rmarkdown](https://rmarkdown.rstudio.com/), [bookdown](https://bookdown.org/) sowie im [learnr](https://rstudio.github.io/learnr/index.html)-Package geschrieben und erstellt. Es handelt sich hierbei um einen Work-in-Progress und wird ständig durch Mitarbeiter des Lehrstuhl Statistik der Universität Göttingen erweitert und verbessert. Daher würden die Autoren sich sehr über Verbesserungsvorschläge, neue Ideen oder Fehlermeldungen freuen. Hierfür einfach eine E-Mail an folgende Adresse: 

  &emsp;&emsp;&emsp; gitlab+kruse44-intro2r-10509-issue-@gwdg.de 

Das folgende Lehrmaterial ist und wird immer frei sein und kann unter einer [CC-BY-SA 4.0 Lizenz](https://creativecommons.org/licenses/by-sa/4.0/deed.de) verwendet, verbreitet und modifiziert werden.  Der Hauptautor der originalen Version ist [René-Marcel Kruse](https://www.uni-goettingen.de/en/610058.html)  (<a href="https://github.com/RMKruse/">Github@RMKruse</a>, <a href="https://gitlab.gwdg.de/kruse44">gitlab.gwdg@kruse44</a>) unter Mitwirkung von:
  * Jasmin Wiebke Schilling
  * [Dr. Alexander Silbersdorff](https://www.uni-goettingen.de/de/411195.html) vom Zentrum für Statistik
  * [Sina Ike](https://www.uni-goettingen.de/de/618417.html) vom Mathematischen Institut und Lehrstuhl für Ökonometrie  

# Installation des R-Packages

Installiere zu erst das learnr-Package über den Befehl `install.packages("learnr")`.

Darauf hin installiere einfach das R-Package intro2r vom GWDG internen Gitlab. Nutze hierfür einfach den folgenden Befehl:
`remotes::install_gitlab(repo = "kruse44/intro2r", host = "gitlab.gwdg.de")`

## Probleme bei der Installation

Sollte der Befehl `remotes::install_gitlab(repo = "kruse44/intro2r", host = "gitlab.gwdg.de")` nicht funktionieren, fehlt dir auf deinem Rechner das Package remotes. Hierfür einfach über den `install.packages()`-Befehl remotes nach installieren.

Nutzer von Unix-like Systemen (Linux, BSD, MacOS) müssen unter Umständen etwaige Dependencies von genutzen Packages nach installieren. Da dies allerdings eine triviale Aufgabe ist, sollte dies kein großes Problem darstellen und relativ einfach durch eine schnelle Suche im Internet zu lösen sein.

# Ausführen des Skriptes

Um das angebotene Skript auszufürehn einfach die folgende Befehle ausführen:
`learnr::run_tutorial("skript", "intro2r")`

Nach dem ersten Ausführen des Befehls dauert es vielleicht einige Sekunden bis sich im Standard-Browsers deines Systems sich ein Tab öffnet in dem das interaktive **R** Skript ausgeführt wird.

## Bekannte Probleme beim Ausführen

tba.

# Verweise 

Das Skript bezieht sich auf verschiedene Quellen, deren inhaltliche Aufarbeitung und Darstellung der Thematik, als Grundlage und Bezugspunkt beim Erstellen dieses Skriptes dienten. Hierbei sei vor allem auf folgende Quellen verwiesen, wobei es sich bei allen Quellen um Free-and-Open-Source Lehrinhalte der jeweiligen Autoren handelt:

  * [Advanced R](http://adv-r.had.co.nz/) von [Hadley Wickham](http://hadley.nz/)
  * [Merely Useful: Novice R](https://merely-useful.github.io/r/index.html) von [Madeleine Bonsma-Fisher et al.]()
  * [R for Data Science](#https://r4ds.had.co.nz/) von [Hadley Wickham](http://hadley.nz/) und [Garrett Grolemund](https://twitter.com/statgarrett?lang=de)
  * [Hands-On Programming with R](#https://rstudio-education.github.io/hopr/) von [Garrett Grolemund](https://twitter.com/statgarrett?lang=de)
  * [Fundamentals of Data Visualization](#https://serialmentor.com/dataviz/) von [Claus O. Wilke](https://github.com/clauswilke)
  * [YaRrr! The Pirate’s Guide to R](#https://bookdown.org/ndphillips/YaRrr/) von [Nathaniel D. Phillips](https://ndphillips.github.io/index.html)
  
Des Weiteren diente als Grundlage die Vorlesungsfolien des Statistik-Master Kurses "Introduction to Statistical Programming" von [Paul Wiemann](https://www.uni-goettingen.de/de/525900.html).
