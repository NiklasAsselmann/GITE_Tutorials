# Html and CSS
**Autors**: Niklas Aßelmann, Mohammed Abdelal und Sulaxan Somaskantharajan


### Was brauchen wir zum Start?

- Einen Webbrowser, einen der folgenden:
    - Google Chrome
    - Mozilla Firefox
    - Safari
    - Edge
- Einen Texteditor, einen der folgenden:
    - Sublime Text
    - Atom.io
    - Visual Studio
    - Brackets
    - Notpad++(Windows)
    - TextMate(Mac)

## Was ist HTML ?

- **Hyper Text Markup Language**
- **Keine** Programmiersprache
- Markup für das ERstellen von Websiten und Dokumenten

### Erstellen einer HTML Datei

- Es wird kein Server benötigt
- Die Daten muss mit .html enden
- Läuft im Webbrowser

**Hinweis:** Index.html ist die *root/ home* Seite der Website, zum Beispiel: *Http://www.example.com* lädt die index.html Datei.
 Während  *[Http://www.example.com/about.html](http://www.example.com/about.html)  * lädt die about.html Datei.


**Tag Syntax**

```html
<tagename>content</tagname>
<h1>About Us</h1>
<p>Das ist ein Absatz</p>
<br/> (sebst schließend)
<br>  (Okay in HTML5)
```

- Elementnamen in spitzen Klammern
- Normalerweise in Paaren vorhanden ("start" und "end" tag)
- Das End-Tag ist normalerweise das gleiche, jedoch mit einem Schrägstrich
- Einige Tags schließen sich selbst

**Die Schritte zum Erstellen einer HTML-Datei**
- Erstellen Sie eine neue Textdatei
- Ändere die Endung zu __.html__
- Öffne sie im Text editor
- Füge die HTML Synatax zu
- Speichern sie und öfffne sie danach im Browser

<p align="center"><img src="https://i.imgur.com/AU9JUdS.gif" height="500" alt="alt text" title="headings demo"></p>
<p align="center"><img src="https://i.imgur.com/ieTqcVI.gif" height="500" alt="alt text" title="basics demo"></p>
<p align="center"><img src="https://i.imgur.com/IHl3e5y.gif" height="500" alt="alt text" title="basics demo"></p>

# HTML Elemente

HTML-Elemente können verschachtelt sein (dies bedeutet, dass Elemente andere Elemente enthalten können).

Alle HTML-Dokumente bestehen aus verschachtelten HTML-Elementen

Das folgende Beispiel ist ein einfaches HTML-Dokument. In seiner einfachsten Form enthält es vier HTML-Elemente (`<html>`, `<body>`, `<h1>` and `<p>`):

```html
<!DOCTYPE html>
<html>
		<head>
				<title>Das hier ist der Titel des Dokuments</title>
		</head>
		<body>
				<h1>Das hier ist eine Überschrift</h1>
				<p>Hier kommt der Inhalt hin.....</p>
				<p>Hier kommt der Inhalt hin.....</p>
		</body>
</html>
```

- Die`<!DOCTYPE html>` Deklaration definiert, dass dieses Dokument ein HTML5-Dokument ist
- Das`<html>` Element ist das Stammelement einer HTML-Seite
- Das`<head>`Element enthält Metadaten zur HTML-Seite
- Das `<title>` Element gibt einen Titel für die HTML-Seite an (der in der Titelleiste des Browsers oder auf der Registerkarte der Seite angezeigt wird).
- Das`<body>` Das Element definiert den Hauptteil des Dokuments und ist ein Container für alle sichtbaren Inhalte wie Überschriften, Absätze, Bilder, Hyperlinks, Tabellen, Listen usw.
- Das`<h1>` Element definiert eine große Überschrift
- Das `<p>` Element definiert einen Absatz

# Die <!DOCTYPE> Deklaration

Die`<!DOCTYPE>` Deklaration stellt den Dokumenttyp dar und hilft Browsern, Webseiten korrekt anzuzeigen.

Es darf nur einmal oben auf der Seite angezeigt werden (vor HTML-Tags).

# HTML Überschriften

HTML Überschriften sind definiert mit den Tags `<h1>`bis`<h6>`.

`<h1>` definiert die wichtigste Überschrift. `<h6>` definiert die am wenigsten wichtige Überschrift:

```html
<h1>Überschrift 1</h1>
<h2>Überschrift 2</h2>
<h3>Überschrift 3</h3>
<h4>Überschrift 4</h4>
<h5>Überschrift 5</h5>
<h6>Überschrift 6</h6>
```
<p align="center"><img src="https://i.imgur.com/gQChqlz.gif" height="500" alt="alt text" title="headings demo"></p>

# HTML Absätze

HTML Absätze sind mit dem Tag `<p>` definiert:

```html
<p>Das ist ein Absatz</p>
<p>Das ist ein weiterer Absatz</p>
```
<p align="center"><img src="https://i.imgur.com/BTcJJGo.gif" height="500" alt="alt text" title="paragraphs demo"></p>

# Übung :
Erstellen Sie eine HTML-Seite, die genauso aussieht wie das, was Sie bisher gelernt haben.

<p align="center"><img src="https://www.dummies.com/wp-content/uploads/280295.image0.jpg" height="500" alt="alt text" title="exercise1"></p>

# HTML Links

HTML links sind mit dem  Tag `<a>` definiert, und das Ziel des Links wird im Attribut `href` angegeben.

```html
<a href="https://www.google.com">google</a>
```


**Hinweis:** Attribute werden verwendet, um zusätzliche Informationen zu HTML-Elementen bereitzustellen.

# HTML Bilder

HTML Bilder sind mit dem Tag `<img>`definiert.

Die Quelldatei (`src`), der alternative Text (` alt`), `width` und` height` werden als Attribute bereitgestellt:

```html
<img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" alt="google" width="104" height="142">

```

<p align="center"><img src="https://i.imgur.com/5IpzvW1.gif" height="500" alt="alt text" title="images demo"></p>

# HTML Attribute

- Alle HTML-Elemente können **Attribute** haben
- Attribute liefern **zusätzliche Informationen** zu Elementen
- Attribute werden immer im **Start-Tag** angegeben
- Attribute kommen normalerweise in Name / Wert-Paaren wie: **name = "value"**

# HTML Formatierungselemente

Formatierungselemente wurden entwickelt, um spezielle Textarten anzuzeigen:

- `<b>` - fett gedruckten Text
- `<strong>` - wichtiger Text
- `<i>` - Italic Text
- `<em>` - Hervorgehobener Text
- `<mark>` - Markierter Text
- `<small>` - Kleinerer Text
- `<del>` - gelöschter Text
- `<ins>` - Eingefügter Text
- `<sub>` - Tiefgestellter Text
- `<sup>` - Hochgestellter Text

# HTML `<b>` and `<strong>` Elemente

Das HTML-Element <b> definiert fett gedruckten Text ohne zusätzliche Bedeutung.

```html
<b>Dieser Text ist fett gedruckt</b>
```

Das HTML <strong> -Element definiert Text mit hoher Bedeutung. Der darin enthaltene Inhalt wird normalerweise fett angezeigt.

```html
<strong>Dieser Texte ist wichtig</strong>
```

<p align="center"><img src="https://i.imgur.com/cPZazIh.gif" height="500" alt="alt text" title="bold demo"></p>

# HTML `<i>` and `<em>` Elemente

Das HTML-Element `<i>` definiert einen Teil des Textes in einer anderen Stimme oder Stimmung. Der Inhalt wird normalerweise kursiv angezeigt.

**Hinweis:** Das `<i>` -Tag wird häufig verwendet, um einen technischen Begriff, eine Phrase aus einer anderen Sprache, einen Gedanken, einen Schiffsnamen usw. anzugeben.

```html
<i>Dieser Texte ist kursiv</i>
```

<p align="center"><img src="https://i.imgur.com/F9lYuo7.gif" height="500" alt="alt text" title="italic demo"></p>

Das HTML-Element `<em>` definiert hervorgehobenen Text. Der Inhalt wird normalerweise kursiv angezeigt.

```html
<em>Dieser Texte ist hervorgehobenen</em>
```

**Hinweis:** Ein Bildschirmleser spricht die Wörter in `<em>` mit einer bestimmten Betonung aus.

<p align="center"><img src="https://i.imgur.com/GdyMJIk.gif" height="500" alt="alt text" title="em demo"></p>

# HTML `<small>` Element

Das HTML-Element `<small>` definiert kleineren Text:

```html
<small>Dieser Text ist klein</small>
```
<p align="center"><img src="https://i.imgur.com/LJG8Dlt.gif" height="500" alt="alt text" title="small demo"></p>

# HTML `<del>` Element

Das HTML-Element `<del>` Element definiert Text, der aus einem Dokument gelöscht wurde. Browser streichen normalerweise eine Zeile durch gelöschten Text:

```html
<p>Meine Lieblinsfarbe <del>Blau</del> Rot.</p>
```
<p align="center"><img src="https://i.imgur.com/vO9EXnV.gif" height="500" alt="alt text" title="delete demo"></p>

## HTML Styles

Das HTML-Stilattribut wird verwendet, um einem Element Stile hinzuzufügen, z. B. Farbe, Schriftart, Größe und mehr.

Das HTML-Stilattribut hat die folgende Syntax:

```html
<tagname style="property:value;">
```

# Hintergrund Farbe

Die CSS-Eigenschaft `background-color` definiert die Hintergrundfarbe für ein HTML-Element.

```html
<body style="background-color:powderblue;">

<h1>Das ist eine Überschrift</h1>
<p>Das ist ein Absatz</p>

</body>
```

<p align="center"><img src="https://i.imgur.com/V27kcGG.gif" height="500" alt="alt text" title="styles demo"></p>

# Text Color

Die CSS-Eigenschaft `color` definiert die Textfarbe für ein HTML-Element:

```html
<h1 style="color:blue;">Das ist eine Überschrift</h1>
<p style="color:red;">Das ist ein Absatz</p>
```

<p align="center"><img src="https://i.imgur.com/B7oszzu.gif" height="500" alt="alt text" title="styles demo"></p>

# Fonts

Die CSS-Eigenschaft `font-family` definiert die Schriftart, die für ein HTML-Element verwendet werden soll:

```html
<h1 style="font-family:verdana;">Das ist eine Überschrift</h1>
<p style="font-family:courier;">Das ist ein Absatz</p>
```

# **Text Ausrichtung**

Die CSS-Eigenschaft `text-align` definiert die horizontale Textausrichtung für ein HTML-Element:

```html
<h1 style="text-align:center;">Zentrierte Überschrift</h1>
<p style="text-align:center;">Zentrierter Absatz</p>
```

<p align="center"><img src="https://i.imgur.com/RN7GVXV.gif" height="500" alt="alt text" title="styles demo"></p>

# Übung :
Erstellen Sie eine HTML-Seite, die im folgenden Beispiel genauso aussieht wie das, was Sie bisher gelernt haben.

<p align="center"><img src="https://i.imgur.com/y5jcJEz.png" height="500" alt="alt text" title="exercise 2"></p>


# Listen

Listen haben drei Typen:

- geordnete Liste `<ol>`: generiert automatisch eine Nummer für jeden Eintrag in der Liste.
- ungeordnete Liste `<ul>`: mit einfachen Aufzählungszeichen anstelle von Zahlen.

```html
<h3> Fruits! </h3>

<ol>
	<li> Apple </li>
	<li> Carrot </li>
	<li> Orange </li>
	<li> Plum </li>
	<li> Watermelon </li>
</ol>

<h3> Dogs! </h3>

<ul>
	<li> Chow Chow </li>
	<li> Dachshund </li>
	<li> German Shepherd </li>
	<li> Pit Bull </li>
	<li> Whippet </li>
</ul>
```

### Fruits!

1. Apple
2. Carrot
3. Orange
4. Plum
5. Watermelon

### Dogs!

- Chow Chow
- Dachshund
- German Shepherd
- Pit Bull
- Whippet

## Tabellen

Das Definieren einer Tabelle besteht aus mehreren Ebenen.

- `<table>` Definiert den Tabellenstart
- `<tr>` Tabellenzeile
- `<th>` Tabellenüberschrift für obere und seitliche Zellen (optional).
- `<td>` Tabellendaten, eine einzelne Zelle.

```html
<table style="text-align:center;" width="200" border="1">
  <tr>
    <td></td>
	<th>A</th>
	<th>a</th>
  </tr>
  <tr>
  	<th>A</th>
    <td>AA</td>
    <td>Aa</td>
  </tr>
  <tr>
    <th>a</th>
    <td>Aa</td></td>
    <td >aa</td>
  </tr>
</table>
```

## **1. What is CSS?**

`Cascading Style Sheets (CSS)`ist eine Stylesheet-Sprache, mit der die Darstellung eines in HTML oder XML geschriebenen Dokuments beschrieben wird. CSS beschreibt, wie Elemente auf dem Bildschirm, auf Papier, in der Sprache oder auf anderen Medien angezeigt werden sollen.

### **Drei Wege CSS zu nutzen**

- Inline: Benutzen von style= attribute for jedes HTML-Element innerhalb des `<body>`

```html
<!DOCTYPE html>
<html>
	<body>
		<h1 style="color:blue;margin-left:30px;">This is a heading</h1>
		<p>Das ist ein Absatz</p>
	</body>
</html>

```

- Internal: Benutzen eines `<style>`Elements innerhalb des HTML `<head>`

```html
 <!DOCTYPE html>
<html>
	<head>
		<style>    
		body {
		    background-color:Blue;
		}
		h1{
		   margin-left:30p
		}
		</style>    
	</head>

	<body>
		<h1>Das ist eine Überschrift</h1>
		<p>Das ist ein Absatz</p>
	</body>
</html>

```

- External: Benutzen einer oder mehrerer CSS Dokumente

Im HTML Dokument

```html
 <!DOCTYPE html>
<html>
	<head>
		<link rel="stylesheet" 	type="text/css" hrel="mystyle.css" >
	</head>
	<body>
		<h1>Das ist eine Überschrift</h1>
		<p>Das ist ein Absatz</p>
	</body>
</html>

```

Mit einem externen CSS Dokument

```css
p {background-color:Blue;}
h1{margin-left:30p;}

```

## **2. Elemente in CSS**

### Element Selector

an *`element selector`* — Dies ist ein Selektor, der direkt mit einem HTML-Elementnamen übereinstimmt. Um alle Absätze im Dokument anzuvisieren, verwenden Sie den Selektor `p`. Um alle Absätze grün zu machen, würden Sie Folgendes verwenden:
```css
p {
  color: green;
}
```

Sie können mehrere Selektoren gleichzeitig ansprechen, indem Sie die Selektoren durch ein Komma trennen. Wenn alle Absätze und Listenelemente grün sein sollen, sieht meine Regel folgendermaßen aus:

```css
p, li {
    color: green;
}
```

### Klassen

Fügen Sie in Ihrem HTML-Dokument dem zweiten Listenelement ein Klassenattribut hinzu. Ihre Liste sieht nun folgendermaßen aus:

```html
<ul>
	<li>Item one</li>
	<li class="special">Item two</li>
	<li>Item <em>three</em></li>
</ul>
```

In Ihrem CSS können Sie die Klasse `special` als Ziel festlegen, indem Sie einen Selektor erstellen, der mit einem Punkt beginnt. Fügen Sie Ihrer CSS-Datei Folgendes hinzu:

```css
.special {
  color: orange;
  font-weight: bold;
}
```

Speichern und aktualisieren, um das Ergebnis zu sehen.

Sie können die Klasse `special` auf jedes Element auf Ihrer Seite anwenden, das genauso aussehen soll wie dieses Listenelement. Beispielsweise möchten Sie möglicherweise, dass das `<span>` im Absatz ebenfalls orange und fett ist. Versuchen Sie, eine `class` von `special` hinzuzufügen, laden Sie dann Ihre Seite neu und sehen Sie, was passiert.

Manchmal sehen Sie Regeln mit einem Selektor, der den HTML-Element-Selektor zusammen mit der Klasse auflistet:

```css
li.special {
  color: orange;
  font-weight: bold;
}
```

Diese Syntax bedeutet, dass wir jedes "li" Element der Klasse "special" ansprechen

## Farbe und Hintergrundfarbe

Farben können mit `color` und `background-color` angewendet werden (beachten Sie, dass dies die amerikanische englische “color” und nicht “colour”sein muss).

Ein blauer Hintergrund und ein gelber Text könnten folgendermaßen aussehen:

```css
h1 {
    color: yellow;   
		background-color: blue;
}

```

Diese Farben sind möglicherweise etwas zu anstrengend, sodass Sie den Code Ihrer CSS-Datei für leicht unterschiedliche Farbtöne ändern können:

```css
body {
    font-size: 14px;
    color: navy;
}

h1 {
    color: #ffc;
    background-color: #009;
}

```

Speichern Sie die CSS-Datei und aktualisieren Sie Ihren Browser. Sie werden sehen, dass sich die Farben der ersten Überschrift (das Element `h1`) in Gelb und Blau geändert haben.

Sie können die Eigenschaften `color` und `background-color` auf die meisten HTML-Elemente anwenden, einschließlich `body`, wodurch die Farben der Seite und alles darin geändert werden.

## Textformatierung mit CSS

### font-family

Dies ist die Schriftart selbst, z. B. Times New Roman, Arial oder Verdana.

### font-style

`font-style` gibt an, ob der Text kursiv ist oder nicht. Es kann `font-style: italic` oder `font-style: normal` sein.

### text-transform

`text-transform` ändert die Groß- und Kleinschreibung des Textes.

- `text-transform: capitalize` wandelt den ersten Buchstaben jedes Wortes in Großbuchstaben um.
- `text-transform: uppercase` verwandelt alles in Großbuchstaben.
- `text-transform: lowercase` verwandelt alles in Kleinbuchstaben.

**Beispiel:**

```css
body {
    font-family: arial, helvetica, sans-serif;    font-size: 14px;}

h1 {
    font-size: 2em;}

h2 {
    font-size: 1.5em;}

a {
    text-decoration: none;}

strong {
    font-style: italic;    text-transform: uppercase;}
```

### Margin and Padding

`margin`und`padding` sind die beiden am häufigsten verwendeten Eigenschaften für Abstandselemente. Ein Rand(Margin) ist der Raum außerhalb von etwas, während Polsterung(Padding) der Raum innerhalb von etwas ist.
![Html%20and%20CSS%20c7204d15b835490a837f2fa7451de01d/Untitled.png](Abbildungen/Html%20and%20CSS%20c7204d15b835490a837f2fa7451de01d/Untitled.png)

Ändern Sie den CSS-Code für `h2` wie folgt:

```css
h2 {
    font-size: 1.5em;
    background-color: #ccc;
		margin: 20px;
		padding: 40px;
}

```

Dadurch bleibt ein Raum mit einer Breite von 20 Pixel um den sekundären Header herum, und der Header selbst ist durch das Auffüllen mit einer Breite von 40 Pixel fett.

# Übung :
Erstellen Sie eine HTML-Seite, die im folgenden Beispiel genauso aussieht wie das, was Sie bisher gelernt haben.

<p align="center"><img src="https://i.imgur.com/xWsiIQP.png" height="500" alt="alt text" title="exercise 3"></p>
