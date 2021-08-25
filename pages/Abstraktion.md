---
layout: page
title: Abstraktion und Generalisierung
subtitle: Ziele
show-avatar: false
share-img: "/images/AbstraktionFig.JPG"
--- 

<center><img src="/images/AbstraktionFig.jpg" width="50%" height="50%"/></center>

(still in progress)

## Abstraktion und Generalisierung

### Konzept
Bei der Abstraktion werden die relevanten Informationen identifiziert und extrahiert, um die Hauptidee zu definieren, indem die Merkmale herausgefiltert werden, die nicht relevant sind. Damit konzentrieren wir uns auf die Merkmale, die wir benötigen um das Problem zu lösen.

Das Problem wird aus einem gewissen Abstand betrachtet und über Details hinweggeschaut. Dieser Schritt ist beispielsweise nötig, um das Problem in seiner einfachsten möglichen Form zu formulieren, in der nur noch die wirklich relevanten Informationen berücksichtigt werden.

![Figur Abstraktion](https://ctathtw.github.io/images/AbstraktionFig.jpg)

(source of images still missing)

Natürlich hilft die abstraktere Sichtweise auch bei der Dekomposition und Pattern Recognition, denn oftmals zeigt sich, dass zu Beginn verschieden erscheinende (Teil-) Probleme sich auf einen gemeinsamen Kern zurückführen lassen und mit derselben (wiederholten) Strategie zu lösen sind.

Bei komplexen Problemen ist es oft nötig, kontinuierlich mit verschiedenen Ebenen der Abstraktion umzugehen, beispielsweise wenn man eigentlich gerade eine Lösung für ein Teilproblem sucht, dabei aber den Zusammenhang mit dem Gesamtproblem auf der einen und der technischen Umsetzung auf der anderen Seite nicht ganz außer Acht lassen darf.
Abstraktion im Computational Thinking ist eine Technik, bei der wir einzelne Teile des Programms in imaginäre „Black Boxes“ aufteilen, die Operationen ausführen. Es ist uns egal, wie sie sie machen, nur dass sie funktionieren.

Durch Abstraktion können wir Teile eines Systems allgemein darstellen, einschließlich Variablen, Konstanten, Schlüsselprozesse, wiederholte Prozesse, Eingaben und Ausgaben.
Dieser methodische Ansatz gipfelt dann in der schrittweisen Implementierung und Vervollständigung der Problemlösung wie wir es aus dem Scrum-Prozess kennen.

Die Studierenden müssen also ein Gefühl für folgende Dinge entwickeln lernen:

*	Identifizieren von Informationen, die zur Lösung eines Problems benötigt werden. 
*	Herausfiltern von in diesem Kontext nicht benötigten Informationen und Begründung warum diese unwichtig sind um unzulässige Vereinfachungen zu vermeiden
*	„Black Box“ Denken

### Beispiele

Wir verwenden Abstraktion, um Dinge zu organisieren: 
*	 Eine Weltkarte ist eine Abstraktion der Erde in Bezug auf Längen- und Breitengrad und hilft uns, den Ort und die Geographie eines Ortes zu beschreiben. 
*	Pictogramme an einem Gang in einem Geschäft sind eine Abstraktion der in diesem Gang verfügbaren Gegenstände 
*	Wenn wir einen Buchbericht schreiben, fassen wir nur das Thema oder die Schlüsselaspekte des Buches zusammen und diskutieren es. Es ist Abstraktion. 
*	Wenn wir unseren Freunden eine Geschichte erzählen oder einen Film beschreiben, warum beschreiben wir nicht jedes einzelne Detail des Buches, der Geschichte oder des Films?
*	„Big Picture“, damit wir argumentieren können, ohne über die Details nachzudenken

In der Technik bedeutet das in erster Linie, dass wir auf die benötigte Funktion achten und nicht zuerst auf die Implementierungsdetails. Wenn die Funktion klar definiert ist, ist die Art der Implementierung relativ egal. Problemstellungen können mitunter enorm vereinfacht werden, wenn alle zweit- und drittrangigen Details ausgeblendet werden. In Steuerungssystemen fokussiert man sich z.B. erstmal auf die erforderlichen Steuerkommandos und vernachlässigt die Art und Weise wie sie transportiert werden. Bei Konstruktionsaufgaben abstrahiert man erstmal vom Materialtyp, der Farbe, allen Schnickschnacks usw. um sich dem Problem anzunähern.

Das wohl bekannteste Modell für Abstraktion ist das OSI-Referenzmodell für die Kommunikation zwischen Computern, wo jeder Schicht die Implementierung der darunterliegenden Schicht unbekannt ist und die Dienste lediglich über Service Access Points bereitgestellt werden. Damit sind wir auch sehr schnell bei Architekturkonzepten verteilter Systeme, die in der Regel von konkreten Computertypen und Locations abstrahieren.
