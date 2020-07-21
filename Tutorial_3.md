# Einführung in JavaScript
**Autors**: Niklas Aßelmann, Mohammed Abdelal und Sulaxan Somaskantharajan

---

## Übersicht

- [1 Was ist JavaScript?](#1-Was-ist-Leaflet)
- [2 Das erste Script](#2-Das-erste-Script)
- [3 Fortgeschrittende JavaScript Operationen](#3-Fortgeschrittende-JavaScript-Operationen)




---

## 1 Was ist JavaScript?

JavaScript ist die Programmiersprache von HTML und des Internets. Sie gehört neben HTML und CSS zu den drei Must-Haves für jeden Webentwickler. JavaScript wird benutzt um  das Verhaltens von Webseiten zu programmieren. Ein Vorteil von JavaScript ist, dass man es nicht herunterladen muss. Es wird bereits überall automatisch ausgeführt.

Was genau kann JavaScript?
  - JavaScript kann HTML-Inhalte ändern
  - JavaScript kann HTML-Attributwerte ändern
  - JavaScript kann HTML-Stile (CSS) ändern
  - JavaScript kann HTML-Elemente ausblenden
  - JavaScript kann HTML-Elemente anzeigen

## 2 Das erste Script

### Platzierung

Um mit dem Programmieren von JavaScript anzufangen muss man als erstes wissen wo man das Script einfügt.
Zum Einfügen eies Scripts gibt es zwei Möglichkeiten:
  1. zwischen den Script-Tags, also zwischen  <script> und </script>
  2. als einzelnde JavaScript Datei (.js), welche im HTML-Code aufgerufen wird. <br>

Zur Vereinfachung der Tutorial wird im folgenden anhand der ersten Möglichkeit erklärt. <br>
Der Beste Ort zum platzieren eines JavaScripts in einem HTML-Dokument ist das Ende des Bodys.

### Syntax

Jetzt wo wir wissen wo ein JavaScript platziert werden muss, schauen wir uns die Syntax von JavaScript an.
Ein wichtiges Element in JavaScript sind Variablen. Mit diesen Variable kann man hauptsächlich drei Dinge tun
  1. Sie deklarieren
  2. Ihnen werte zuweisen 

Eine Variable deklarieren
  - Eine Variable wird deklariert durch den einfachen Zusatz "var" vor ihrem Namen.
    Danach kann man ihr Werte zuweisen oder sie einen neuen Wert errechen lassen <br>

Einer Variable einen Wert zuweisen
  - Hat man eine Variable deklariert, kann man ihr mit einem einfachen "=" einen Wert zuweisen. <br>
    Hier dient das Gleichzeichen als Zuweisungsoperator, um Variablen Werte zuzuweisen. <br>
    Abgesehen von der einfachen zuweisung einer Zahl kann eine Variable auch das Ergebniss einer JavaScript Operation sein. <br>
    Diese kann die Summe zweier Zahlen sein aber auch das Produkt zweier anderen Variablen.
    Man kann Variablen aber nicht nur Zahlen zuweisen, sondern auch Zeichenfolgen. Diese geschieht durch das verwenden von Anführungssrtichen.
    Beispiel für zuweisung von Zeichenfolge

### Java-Script Anweisungen

Jetzt wo du weißt wie die Syntax von JavaScript funktioniert zeigen wi dir wie eine JavaScript Anweisung funktioniert und welche Typen von Anweisungen es gibt. JavaScript-Anweisungen können aus folgenden Dingen bestehen:
  - Werten, 
  - Operatoren 
  - Ausdrücke
  - Schlüsselwörter 
  - Kommentare.
Ein JavaScript-Programm besteht meist aus mehreren JavaScript-Anweisungen, die nacheinander ausgeführt werden.
JavaScript-Anweisungen werden durch Semikolons getrennt.
Leerstellen sowie Zeilenumbrüche in den Anweisungen sind erlaubt.

#### Zugriff auf HTML- Elemente
Damit man mit JavaScript Element eines HTML-Dokuments verändern kann, bedarf es der wohl wichtigsten JavaScript-Anweisung.
Mit der "document.getElementById(id)"- Methode kann man HTML dokumente ansprechen. Die id eines HTML-Elemts ist im HTML-Dokument definiert worden.

#### Anzeigemöglichkeiten in JavaScript

Mit JavaScript kann man Daten auf 4 unterschiedliche Weisen anzeigen lassen. 
  - Die erste Anweisung "innerHTML=" kann man den Inhalt des HTML-Elements ändern. Die komplette Anweisung würde dann "document.getElementById("deine Variable").innerHTML=x" heißen.
  - Die zweite Anweisung "document.write()" kann man den Inhalt des Dokumentes ändern. Löscht aber alle vorher geladenen HTML-Elements. Deshalb wir es nur für Testzwecke genutz. [Ein gutes Beispiel warum man es nur zum Testen benutzen solle](https://www.w3schools.com/code/tryit.asp?filename=GGY8JU3O6CW9)
  - Die dritte Anweisung "window.alert ()" öffnet ein Warnfeld, das den Inhalt der Methode anzeigt.
  - Die vierte Anweisung "console.log()" schreibt den Inhalt der Methode in den Logger des Browsers. Diese Methode wird häufig zum Debugging benutz, ist aber für das Einführungstutorial irrelevant.

### Erste Übung

  - In der ersten praktischen Übung sollst du deine eigene erste Variable deklarieren, zuweisen und einmal als HTML-Inhalt anzeigen lassen und einmal als Warnfeld.
  - [Link zur ersten praktischen Übung](https://www.w3schools.com/code/tryit.asp?filename=GGY8Q98QGDTG)
  - Bei richtiger Deklarierung und Zuweisung sollte es wie folgt aussehen:
    - [Lösung HTML-Element](https://www.w3schools.com/code/tryit.asp?filename=GGY8TS2GC9K2)
    - [Lösung Warnfeld](https://www.w3schools.com/code/tryit.asp?filename=GGY8UBVGSEZY)

## 3 Fortgeschrittende JavaScript Operationen