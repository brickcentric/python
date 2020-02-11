# Der Weg zum `Coder`
1. Ihr solltet alle ein Account bei [Github](https://www.github.com) erstellen und mir euren Username zusenden.

2. Auf Github könnt ihr ein Repository mit dem Namen `uebung` anlegen, hier werden später euere Programme landen.
Einfach oben in der Ecke da ist ein Plus(+), im Menu klickt ihr auf `New Repository` hier müsst ihr den Namen eintragen und unten auf `Create Repository` drücken.
3. Die Programme unter Software auf euerem Rechner installieren.
4. Das leere Repository auf euren Rechner `clonen` ich zeige euch das.
## Software
* [Python](https://www.python.org/downloads) Damit euer PC Python überhaubt kennt. Einfach installieren und bei allen Fragen weiter drücken 
* [Github Desktop](https://desktop.github.com) Eine Deskop Programm für Github. Einfach installieren und starten. Hier könnt ihr euch mit dem Github Account anmelden
* [Git](https://git-scm.com/downloads) Damit ihr direkt aus PyCharm mit Github interagieren könnt. Installieren indem ihr einfach immer weiter drückt. Bis die installation abgeschossen ist.
* [PyCharm](https://www.jetbrains.com/pycharm-edu/download/index.html) Das ist euere Entwicklungsumgebung für Python. Auch nur runterladen und installieren, immer weiter drücken bis es installiert ist. Beim Einrichten von Python und Git helfe ich euch dann.

## Tutorials und Weiterführendes
### YouTube
* [YouTube Tutorial](https://www.youtube.com/playlist?list=PLNmsVeXQZj7q0ao69AIogD94oBgp3E9Zs)

### Einsteiger Tutorials (DE)
* [Einführung](https://tutorial.djangogirls.org/de/python_introduction/)
* [Tutorial](https://py-tutorial-de.readthedocs.io/de/python-3.3/)

### Offizielles 
* [Offizelle Python Seite (EN)](https://docs.python.org/3/)

### Bücher
* [Sehr gutes und interessantes Buch für den Einstieg](https://www.amazon.de/dp/3836265141/ref=cm_sw_em_r_mt_dp_U_OtBqEbCGVCZHA)
* [Mit Python Mindcraft programmieren](https://www.amazon.de/dp/3864905184/ref=cm_sw_em_r_mt_dp_U_nEBqEb50FG1V3)
* [Eigene einfache Spiele entwickeln mit Python](https://www.amazon.de/dp/3864904927/ref=cm_sw_em_r_mt_dp_U_tEBqEbWXC3D26)

### Python und Roboter
* [MitCozmo programmieren](https://github.com/anki/cozmo-python-sdk)
* [Mindstorm EV3 - Python API](https://education.lego.com/de-de/support/mindstorms-ev3/python-for-ev3)

### Minstorm mit Python
* [Getting started with MindecraftPi](https://projects.raspberrypi.org/en/projects/getting-started-with-minecraft-pi)

## Git
Eine kurze Einführung in die Begrifflichkeiten von Git/Github. `Git` ist eine Versionsverwaltung für Programme, sie dient der Speicherung und der Zusammenarbeit mit anderen Entwicklern, Jeder Versionsstand eines Programmes ist hiermit einsehbar. Github ist weltweit das größte Portal für `Git` indem Softwareentwickler gemeinsam an Software arbeiten und sich austauschen. 
### clone
Ein `clone` ist der Kopiervorgang eines Repository von Github auf den eigenen Rechner.  
### commit
Wenn ihr euere Änderungen speichert macht ihr ein `commit` mit einer Commit-Bemerkung, die Änderungen werden aber nur auf euerem lokalen Rechner gespeichert
### push
Mit einem `push` landen euere Commits auf dem Repository bei Github, diese sind dann für andere einsehbar und nutzbar.
### pull
Mit `pull` holt ihr euch alle Änderungen die es in dem Repository gab von Github auf euren Rechner 
### branch
Ein Branch ist ein neuer Zeig in euerem Repository, in einem Branch entwickelt man neue Features bis sie fertig sind und von einer weiteren Person über ein Pull Request freigegeben wurden.
### merge
Ein Merge fügt 2 Branches wieder zu Einem zusammen, falls es zwischenzeitlich Änderungen an der selben Stelle gegeben hat muss man die Mergekonflikte erst auflösen.
### pull request
Ein Pull Request eine eine Anfrage einen Branch wieder mit dem Ursprungsbranch zusammen zu führen. Hier fragt man einen anderen Entwicker in dem man ein PR(Pull Request) an ihn stellt. Dieser begutachtet die Arbeit, gibt ggf. seine Anmerkungen oder er sagt "alles gut kannste mergen" ;)
## Aufgaben
### Aufgabe 1: Schreibe ein Hello World Programm
Das Programm soll eine Funktion `def hello():` haben und über die Main Bedinung `if __name__ == "__main__":` aufgrufen werden. Die Funtion soll den `String` "Hello World" auf der Konsole ausgeben.
### Aufgabe 2: Taschenrechner (Bedingungen)
0. **git:** Erstelle einen Branch mit dem Namen `uebung2` (ich zeige euch wie das geht)
1. Schreibe eine Konsolenprogram das dein Alter als Eingabe erwartet und ausgibt ob die Minderjähig oder Volljährig bist.
    1. Erweitere die Aufteilung mit den Ausgaben: *Baby*, *Kleinkind*, *Kind*, *Teenie*
    2. **git:** Commite deine Änderungen mit eine passenden commit Nachricht. Pushe es dann nach Github*
2. Schreibe ein Taschenrechner der 2 Zahlen als Eingabe verlangt diese addiert und das Ergebnis dem Benutzer ausgibt. **git: commite jede Teilaufgabe mit einer entsprechenden commit Meldung**
    1. Schreibe den Taschenrechner so um das dieser auch subtrahieren, multiplizieren und dividieren kann. **Hinweis:** Achte auf die Nachkommazahlen.
    2. Schreibe für jede Rechenart eine eingene Funktion die 2 Zahlen entgegen nimmt und das Ergebnis zurückliefert.
3. **git:** Commite und pushe deine letzten Änderungen und erstelle auf Github einen Pull Request den du mir als Reviewer zuteilst

  

