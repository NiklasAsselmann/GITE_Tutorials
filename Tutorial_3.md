# Einführung in JavaScript
**Autors**: Niklas Aßelmann, Mohammed Abdelal und Sulaxan Somaskantharajan

---

## Übersicht

- [1 Was ist JavaScript?](#1-Was-ist-Leaflet)
- [2 Das erste Script](#2-Das-erste-Script)
- [3 Fortgeschrittende JavaScript Operationen](#3-Fortgeschrittende-JavaScript-Operationen)
  * [3.1 Datentypen](#31-Datentypen)
  * [3.2 Funktionen](#32-Funktionen)




---

## 1 Was ist JavaScript?

JavaScript ist die Programmiersprache von HTML und des Internets. Sie gehört neben HTML und CSS zu den drei Must-Haves für jeden Webentwickler. JavaScript wird benutzt um  das Verhaltens von Webseiten zu programmieren. Ein Vorteil von JavaScript ist, dass man es nicht herunterladen muss. Es wird bereits überall automatisch ausgeführt.

Was genau kann JavaScript?
  - JavaScript kann HTML-Inhalte ändern
  - JavaScript kann HTML-Attributwerte ändern
  - JavaScript kann HTML-Stile (CSS) ändern
  - JavaScript kann HTML-Elemente ausblenden
  - JavaScript kann HTML-Elemente anzeigen

---

## 2 Das erste Script

### Platzierung
Um mit dem Programmieren von JavaScript anzufangen muss man als erstes wissen, wo man das Script einfügt.
Zum Einfügen eines Scripts gibt es zwei Möglichkeiten:
  1. Zwischen den Script-Tags, also zwischen  **_<script>_** und **_</script>_**
  2. Als einzelnde JavaScript Datei **_.js_**, welche im HTML-Code aufgerufen wird. <br>

Zur Vereinfachung der Tutorial wird im folgenden anhand der ersten Möglichkeit erklärt. <br>
Der Beste Ort zum Platzieren eines JavaScripts in einem HTML-Dokument ist das Ende des Bodys.

### Syntax

Jetzt wissen wir wo ein JavaScript platziert werden muss. Nun schauen wir uns die Syntax von JavaScript an.
Ein wichtiges Element in JavaScript sind Variablen. Mit diesen Variable kann man hauptsächlich zwei Dinge tun
  1. Sie deklarieren: Eine Variable wird deklariert durch den einfachen Zusatz **_var_** vor ihrem Namen.
    Danach kann man ihr Werte zuweisen oder sie einen neuen Wert errechen lassen <br>
  2. Ihnen Werte zuweisen: Hat man eine Variable deklariert, kann man ihr mit einem einfachen **_=_** einen Wert zuweisen. 
    Hier dient das Gleichzeichen als Zuweisungsoperator, um Variablen Werte zuzuweisen. 
    Abgesehen von der einfachen Zuweisung einer Zahl kann eine Variable auch das Ergebniss einer JavaScript Operation sein.
    Diese kann die Summe zweier Zahlen sein aber auch das Produkt zweier anderen Variablen.
    Man kann Variablen aber nicht nur Zahlen zuweisen, dazu aber später mehr.
  
### Java-Script Anweisungen
Jetzt wo du weißt wie die Syntax von JavaScript funktioniert zeigen wir dir wie eine JavaScript Anweisung funktioniert und welche Typen von Anweisungen es gibt. JavaScript-Anweisungen können aus folgenden Dingen bestehen:
  - Werten, 
  - Operatoren 
  - Ausdrücke
  - Schlüsselwörter 
  - Kommentare

Ein JavaScript-Programm besteht meist aus mehreren JavaScript-Anweisungen, die nacheinander ausgeführt werden.
JavaScript-Anweisungen werden durch Semikolons getrennt.
Leerstellen sowie Zeilenumbrüche in den Anweisungen sind erlaubt.

#### Zugriff auf HTML- Elemente
Damit man mit JavaScript Element eines HTML-Dokuments verändern kann, bedarf es der wohl wichtigsten JavaScript-Anweisung.
Mit der **_document.getElementById(id)_** Methode kann man HTML Dokumente ansprechen. Die ID eines HTML-Elemts ist im HTML-Dokument definiert worden.

#### Anzeigemöglichkeiten in JavaScript
Mit JavaScript kann man Daten auf 4 unterschiedliche Weisen anzeigen lassen. 
  - Die erste Anweisung **_innerHTML=_** kann den Inhalt des HTML-Elements ändern. Die komplette Anweisung würde dann *document.getElementById("deine Variable").innerHTML=x* heißen.
  - Die zweite Anweisung **_document.write()_** kann den Inhalt des Dokumentes ändern. Löscht aber alle vorher geladenen HTML-Elements. Deshalb wir es nur für Testzwecke genutzt. [Ein gutes Beispiel warum man es nur zum Testen benutzen sollte. Einfach auf "RUN" drücken](https://www.w3schools.com/code/tryit.asp?filename=GGY8JU3O6CW9)
  - Die dritte Anweisung **_window.alert ()_** öffnet ein Warnfeld, das den Inhalt der Methode anzeigt.
  - Die vierte Anweisung **_console.log()_** schreibt den Inhalt der Methode in den Logger des Browsers. Diese Methode wird häufig zum Debugging benutz, ist aber für das Einführungstutorial erstmal irrelevant.

### Erste Übung
In der ersten praktischen Übung sollst du deine eigene erste Variable deklarieren, zuweisen und als HTML-Inhalt anzeigen lassen sowie als Warnfeld ausgeben lassen.
- [Link zur ersten praktischen Übung](https://www.w3schools.com/code/tryit.asp?filename=GGY8Q98QGDTG)
- Bei richtiger Deklarierung und Zuweisung sollte es wie folgt aussehen:
  - [Lösung HTML-Element](https://www.w3schools.com/code/tryit.asp?filename=GGY8TS2GC9K2)
  - [Lösung Warnfeld](https://www.w3schools.com/code/tryit.asp?filename=GGY8UBVGSEZY)

---

## 3 Fortgeschrittende JavaScript Operationen
### 3.1 Datentypen
Um bessere Scripts in JavaScript zu programmieren sollte man als erstes die benutzen Datentypen in JavaScript kennelernen. Das besondere der Datentypen in JavaScript ist das sie dynamisch sind. Dies bedeutet, dass dieselbe Variable für verschiedene Datentypen verwendet werden kann. In JavaScript können Variablen eine Vielzahl von Datentypen enthalten. Im folgenden werden die meistbenutzen Datentypen vorgestellt:
  - Zahl
  - Zeichenfolge
  - Arrays
  - Objekt
#### Zahl
Dieser Datentyp ist relativ selbsterklärend und wird zum Beispiel durch die Anweisung **_var x = 10_;** erreicht.
#### Zeichenfolge
Der nächste Datentyp ist die zeichenfolge. Sie besteht aus der Aneinandererreihung mehrere Zeichen (aber auch Zahlen) zwischen Anführungszeichen und würde beispielsweise so aussehen: **_var x ="123XYZ";_**
#### Arrays
Arrays sind eine Art Liste in der jeder Stelle ein bestimmter Wert zugewiesen ist. Diese Liste wird durch eckige Klammern erstellt. Ein Bespiel hierfür wäre **_var x = [10,11]_;**. Hier wäre die Nummer 10 an der stelle 0 und die 11 an Stelle 1.
#### Objekt
Eine Weiterentwicklung des Arrays ist das Object. Ein Objekt wird durch geschweifte Klammern erstellt. Hier gibt es keine Indizes sondern die gespeicherten Variablen werden als sogenannte *Name:Wert*-Paare gespeichert. Ein Beispiel hierfür wäre **_var x = {Vorname:"Max" , Alter:18}_;**. Wie im Beispiel gesehen können in einem Objekt sowohl Zeichenketten als auch Zahlen gespeichert werden.

#### Datentyp-Übung
Um besseres Verständnis für die Datentypen zu bekommen sollst du in der folgenen Übung der Variable erst eine Zahl zuweisen, danach eine Zeichenkette zu guter letzt ein Objekt. Die **_typof_** Operation gibt immer den Typ der Variable aus (In JavaScript ist jedes Array vom Typ _Objekt_). In diesem Fall 1) _number_, 2) _string_ 3) _object_
- [Link zur zweiten praktischen Übung](https://www.w3schools.com/code/tryit.asp?filename=GGY07JYIBZ4J)
- Bei richtiger Deklarierung sowie dem richtigen Benutzen der "type-of"-Operation sollte es wie folgt aussehen:
  - [Zahl](https://www.w3schools.com/code/tryit.asp?filename=GGY08YQG054J)
  - [Zeichenkette](https://www.w3schools.com/code/tryit.asp?filename=GGY004XVBHHF)
  - [Objekt](https://www.w3schools.com/code/tryit.asp?filename=GGY0CS85X6QL)


### 3.2 Funktionen

Funktionen werden in JavaScript dafür benutzt um Code wiederzuverwenden. Hier kann der einmalig definierte Code mehrmals mit unterschiedlichen Variablen ausgeführt werden. Funktionen werden ausgeführt wenn "etwas" sie aufruft. Das kann durch 3 Ereignisse geschehen:
  1. Sie werden in einem JavaScript-Block aufgerufen.
  2. Sie rufen sich selbst auf.
  3. Sie werden durch ein Ereigniss aufgerufen (z.B Klicken des Benutzers auf Bildschirm). <br>

Mit dem Schlüsselwort **_function_** gefolgt vom Namen und den Parameter in Klammern wird eine Funktion definiert. <br>
Ein Beispiel für eine Funktion sieht so aus: <br>
**_function name(paramter1,parameter2) {<br> code <br>}_** <br>
Der von der Funktion auszuführende Code wird in geschweifte Klammern gesetzt.

#### Rückgabefunktionen
Der Zweck vieler Funktionen ist das Verändern von Variablen bzw. Berechnen von Variablen. Dabei ist es von Vorteil wenn die gewünschte Funktion den errechneten Wert direkt ausgibt, damit man ihn einer Variable zuweisen kann. Diese Rückgabe erfolgt durch ein **_return_** innerhalb der geschweiften Klammern.

#### Lokale Variablen
Eine Besonderheit von Funktionen sind lokale Variablen. Diese Variablen heißen lokal da auf sie nur innerhalb der Funktion zugegriffen werden kann und nicht im ganzen JavaScript Dokument.

#### Funktionen-Übung
Um das soeben erlernte Wissen über Funktionen zu vertiefen, ist das Ziel der dritten Übung das Erstellen der ersten eigenen Funktion.
Die erstellte Funktion soll zwei Zahlen miteinander multiplizieren.
- [Link zur dritten Übung](https://www.w3schools.com/code/tryit.asp?filename=GH8ITOTRV10B)
- Bei richtiger Deklarierung und Aufrufen der Funktions sollte es wie folgt aussehen:
  - [Beispiellösung der dritten Übung](https://www.w3schools.com/code/tryit.asp?filename=GH8IWVLGCM14)

### 3.3 Schleifen
Falls man in JavaScript denselben Code mit unterschiedlichen Variablen aufrufen will, eigenen sich Schleifen am besten. In JavaScript gibt es 2 unterschiedliche Typen von Schleifen:
  1. for-Schleifen
  2. while-Schleifen

#### For-Schleifen
In einer for-Schleife wird der Code-Block eine bestimme Anzahl von malen durchlaufen. Die Syntax einer For-Schleife ist die folgende: <br>
**_for (statement 1; statement 2; statement 3) {<br> code <br>}_** <br>
Statement 1 wird (einmalig) vor der Ausführung des Codeblocks ausgeführt. Hier wird eine Variable festgelegt. <br>
Statement 2 definiert die Bedingung für die Ausführung des Codeblocks. <br>
Statement 3 wird (jedes Mal) ausgeführt, nachdem der Codeblock ausgeführt wurde. Hier wird ein Wert erhöht, der die Schleife (beim erneuten Aufrufen) zum Abbrechen bringen kann.
Ausgehend von dieser Struktur gibt es zwei Variationen der for-Schleife
  1. For/In-Schleife
  2. For/Of-Schleife

##### For/In Schleife
Die For/In-Schleife durchläuft die Eigenschaften eines Objekts. Ein Beispiel dafür wäre folgendes: <br>
[For/In-Schleife Beispiel](https://www.w3schools.com/code/tryit.asp?filename=GHDY8FICJEE1)

#### For/Of-Schleife
Die For/Of-Schleife  durchläuft die Werte eines iterierbaren Objekts. Ein Beispiel dafür wäre folgendes: <br>
[For/Of-Schleife Beispiel](https://www.w3schools.com/code/tryit.asp?filename=GHDYD92GU9HQ)

#### While-Schleifen
Die While-Schleife durchläuft einen Codeblock, solange eine bestimmte Bedingung erfüllt ist. Die Syntax einer While-Schleife ist die folgende: <br>
**_while (condition) {<br> code <br>}_** <br>
Die Kondition welche die Schleife zum Abbrechen führt muss im Code verändert werden , dami die SChleife nicht unendlich weiterläuft und so den Browser zum Absturz bringt. Dies geschieht häufig durch eine vorher deklarierte Variable, welche im Schleifen-Code erhöht wird.

##### While/Do-Schleife
Eine Variation der While-Schleife ist die While/Do-Schleife. Diese Schleife führt den Codeblock einmal aus, bevor sie überprüft, ob die Bedingung erfüllt ist, und wiederholt die Schleife, solange die Bedingung erfüllt ist. Ein Beispiel dafür wäre folgendes: <br>
[While/Do Schleife Beispiel](https://www.w3schools.com/code/tryit.asp?filename=GHDYMHFLZ7YZ)

#### Schleifen-Übung
Um das Erstellen von Schleifen zu lernen soll in dieser Übung die erste eigene For-Schleife sowie While Schleife erstellt werden.
Die Schleife soll nacheinander die Zahlen 1 bis 25 ausgeben. Benutzt **_ text +=i+",";_** im Code.
- [Link zur Schleifen-Übung](https://www.w3schools.com/code/tryit.asp?filename=GHDYYKX6C2BE)
- Lösungen: [While-Schleife](https://www.w3schools.com/code/tryit.asp?filename=GHDZ4TCB99X2), [For-Schleife](https://www.w3schools.com/code/tryit.asp?filename=GHDZ83JPBAFH)
