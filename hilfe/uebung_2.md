### Bedinungen 
Eine Bedingung ist eine Verzweigung in euerem Programmfluss
```
    if note < 3:
        print("Toll gemacht, nur weiter so. ")
    elif note <= 4:
        print("Gut aber vielleicht wird es bei nächsten mal besser. ")
    else:
        print("Ab aufs Zimmer und lernen, das will ich nicht nochmal sehen!")
```
### Datentypen
Es gibt verschiedene Datentypen, den String habt ihr schon kennen gelernt ein String ist eine Zeichenkette die man mit `"Hallo"` in Gänsefüßchen einpackt. Nebein Strings gibt es aber auch Zahlen und Boolean zu unterscheiden:
* `int` (Integer) sind ganze Zahlen wie 1, 9, 20000
* `float` sind Kommazahlen wie 0,122 zu beachten ist aber die amerikanische Schreibweise nämlich man trennt beim Programieren die Nachkomma Zahlen nicht mit einem `,` sondern  mit einem `.` also ist es so richtig `0.122` oder `2333.3333`
* Eine `bool` Variable kann nur `true` oder `false` (wahr/falsch) bedeuten. `istErwachsen=false`

### Benutzer Eingaben
3. Die Funktion etwas auf der Konsole auszugeben habt ihr schon gelernt nämlich mit `print("Hello World")` Die Benutzereingabe von der Komandakonsole könnt ihr mit der Funktion `input()` abfragen. Hierzu könnt ihr die Eingabe direkt in ein Datentyp verwandeln den ihr braucht und erwartet.
* `eingabe = string(input())` Ihr erwartet von Nutzer ein String
* `eingabe = int(input())` Ihr erwartet von Nuter eine Ganzzahl und wollt mit dieser weiter im Programm als Ganzzahl arbeiten
* `eingabe = float(input())` Hier wird die Eingabe in eine Nachkommazahl verwandelt. Eine 2 wäre dann `2.0` ein `"Horst"` wäre aber ein Programfehler da das Programm den String nicht als Zahl erkennt

