# Der Weg zum `Coder`
## Aufgaben
### Aufgabe 1: Schreibe ein Hello World Programm
Das Programm soll eine Funktion `def hello():` haben und über die Main Bedinung `if __name__ == "__main__":` aufgrufen werden. Die Funtion soll den `String` "Hello World" auf der Konsole ausgeben.
### Aufgabe 2: Taschenrechner (Bedingungen)
**Hilfe**: Erklärungen zu den Lösungen findet ihr [hier](hilfe/uebung_2.md)

**git:** Erstelle einen Branch mit dem Namen `uebung2` (ich zeige euch wie das geht)
1. Schreibe ein Konsolenprogram das dein Alter als Eingabe erwartet und ausgibt ob du Minderjähig oder Volljährig bist.
    1. Erweitere die Aufteilung mit den Ausgaben: *Baby*, *Kleinkind*, *Kind*, *Teenie*
    2. **git:** Commite deine Änderungen mit eine passenden commit Nachricht. Pushe es dann nach Github*
2. Programmiere ein Taschenrechner der 2 Zahlen als Eingabe verlangt, diese addiert und das Ergebnis dem Benutzer ausgibt. **git:** commite jede Teilaufgabe mit einer entsprechenden commit Nachricht
    1. Schreibe den Taschenrechner so um das dieser auch subtrahieren, multiplizieren und dividieren kann. **Hinweis:** Achte auf die Nachkommazahlen.
    2. *(Zusatzaufgabe)* Schreibe für jede Rechenart eine eigene Funktion die 2 Zahlen entgegen nimmt und das Ergebnis zurückliefert.
3. **git:** Commite und pushe deine letzten Änderungen und erstelle auf Github einen Pull Request den du mir/`marbon` als Reviewer zuteilst
### Aufgabe 3: Schnick-Schnack-Schuck
In dieser Aufgabe wollen wir ein kleines und ich hoffe allen bekanntes Spiel programmieren. Dazu werden wir all das erlernte aus den vorherigen Übungen benötigen. 
* Ausgaben: Wir steuern den Spielfluss über verschiendene Konsolenausgaben
* Eingaben: Wir nehmen den Zug des Spielers auf
* Bedinungen: Wir prüfen ob Computer oder Spieler die Runde gewonnen hat.
* Schleife **(Neu)**: Wir wiederholen so lange eine neue Spielrunde bis der Spieler bewusst abbricht.
* Funktion: wir nutzen eine Standartfunktion für Zufallszahlen. Wir benötigen ggf auch eine eigene kleine Funktion.
*Bitte Denkt dabei jeden euerer Zwischenstände zu commiten (git)*

1. Wir beginnen zuerst *nur* mit **Schere** und **Papier**. 
Erstellt eine Endlossschleife (`while True:`), in dieser Schleife fragt ihr nach der Spielereingabe (`1=Schere, 2=Papier`). 
Für die Wahl des Computers benötigt ihr Zufahlszahlen (`random`) hierfür gibt es in der Standardbibliothek verschiedenste Funktionen. Im ersten Schritt benötigt ihr zufällige Ganzzahlen (`int`) und genau 1 oder 2. `randint(1,2)`
Dannach prüft ihr ob der Spieler oder der Computer die Runde gewonnen habt und gibt das Ergebnis aus. 
Der Schleifendurchlauf ist beendet und eine weitere Runde beginnt.
[Weitere Hilfe](hilfe/uebung_3.md)

2. Beendet das Spiel wenn der Spieler anstelle einer Zahl ein `x` eingibt (`exit(0)`).

3. Erweitert das Spiel um Stein (`3`) und Brunnen (`4`).

4. Gebt am Ende so etwas aus: 
`Herzlichen Glückwunsch du hast gewonnen` 
`Spieler: Schere`   
`Computer: Papier`
Hinweis: Eine Funktion die ein `int` entgegennimmt und dann das jeweilige Spielsymbol als `string` zurückgibt kann hier hilfreich sein.

5. Zahlt bei jeder Runde die Ergebnisse und gebt am Ende einer Runde den Zwischenstand aus:
`Spieler: 5  Computer: 3`

6. Gebt mal Zahlen wie `6` , `1000`, `hook` ein und schaut was passiert. Versucht jetzt Programmfehler durch Falscheingaben zu vermeinden und zeigt dem Spieler stattdessen entsprechende Fehlertexte an.
    1. Nur gültige Zahlen `1-4` erlauben.
    2. Nur das Sonderzeichen `x` erlauben 
### Game programming mit pygame
Ich euch anleiten und unterstüthen gemeinsam ein grafisches Jump & Run Game mit pygame zu entwicklen. 
[Dann mal los ;)](pygame.md) 

## Vorbereitung / Einrichtung
1. Ihr solltet alle ein Account bei [Github](https://www.github.com) erstellen und mir euren Username zusenden.
2. Auf Github könnt ihr ein Repository mit dem Namen knackigen Namen anlegen, hier wird später euer Programm landen.
Einfach oben in der Ecke da ist ein Plus(+), im Menu klickt ihr auf `New Repository` hier müsst ihr den Namen eintragen und unten auf `Create Repository` drücken.
3. Die Programme unter Software auf euerem Rechner installieren.
4. Das leere Repository auf euren Rechner `clonen` ich zeige euch das.
## Software
* [Python](https://www.python.org/downloads) Damit euer PC Python überhaubt kennt. Einfach installieren und bei allen Fragen weiter drücken 
* [Git](https://git-scm.com/downloads) Damit ihr direkt aus PyCharm mit Github interagieren könnt. Installieren indem ihr einfach immer weiter drückt. Bis die Installation abgeschossen ist.
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

## Git - das kleine 1*1
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

  

