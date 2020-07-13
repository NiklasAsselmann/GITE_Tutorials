# Einführung in Leaflet
**Autors**: Niklas Aßelmann, Mohammed Abdelal und Sulaxan Somaskantharajan

---

## Übersicht

- [1 Was ist Leaflet?](#1-Was-ist-Leaflet)
- [2 Die erste Karte mit Leaflet](#2-Die-erste-Karte-mit-Leaflet)
  * [2.1 Politik](#21-Politik)
  * [2.2 Naturwissenschaft](#22-Naturwissenschaft)
  * [2.3 Gesundheitswesen](#23-Gesundheitswesen)
  * [2.4 Finanzen](#24-Finanzen)
  * [2.5 Andere](#25-Andere)
- [3 Vor- und Nachteile](#3-Vor-und-Nachteile)
  * [3.1 Vorteile](#31-Vorteile)
  * [3.2 Nachteile](#32-Nachteile)
- [4 Regeln](#4-Regeln)
  * [4.1 Regeln für gute Datenvisualisierungen](#42-Regeln-für-gute-Datenvisualisierungen)
  * [4.2 Fehler](#42-Fehler)
- [5 Formen](#4-Formen)




---

## 1 Was ist Leaflet?

Leaflet ist eine Open-Source JavaScript-Bibliothek für interaktive, nutzerfreundliche Karten. Leaflet verwendet HTML und CSS und wird von allen gängigen Webbroswern, wie Google Chrome, Firefox oder Safari auf Desktop-, sowie Mobilgeräten unterstützt. 

Eine Karte ist bereits mit wenigen Zeilen Code und ohne großem Vorwissen in der Programmierung erstellbar. Zudem ist Leaflet sehr einfach mit weiteren Plugins erweiterbar. In diesem Tutorial beschränken wir uns jedoch auf das einfache Erstellen von nutzerfreundlichen Karten. Wie man ein zusätzliches Plugin erstellt, welches die bereits große Anzahl an bereitgestellten Funktionen erweitert, wird nicht besprochen.

Wer sich für die gebotenen Möglichkeiten und Funktionen von Leaflet interessiert kann diese in der sehr ausführlichen, aber dennoch gut strukturierten [Dokumentation](https://leafletjs.com/reference-1.6.0.html) nachlesen.

## 2 Die erste Karte mit Leaflet

Nun kommen wir zur Step-by-Step Anleitung zur Erstellung einer einfachen Karte in einem beliebigen Webbrowser.

Für die Programmierung ist ein Texteditor notwendig. Wir empfehlen an dieser Stelle einen HTML-Editor, wie [Brackets](http://brackets.io) oder [Atom](https://atom.io), welche für das Erstellen von Webanwendungen gut geeignet sind. Letzlich funktioniert aber auch ein einfacher Notepad-editor.

Zunächst bereiten wir unser HTML-Dokument vor. Öffne dazu deinen Texteditor und füge den folgenden Code deinem Dokument hinzu, womit die Struktur deiner Webseite definiert wird:
```
<!DOCTYPE html>

<html>

  <head>

    <title>Leaflet Web Map</title>

    <style>

    </style>

  </head>

  <body>

    <script>

    </script>

  </body>

</html>
```

Speicher dieses Dokument als "index.html" ab.

Um die Funktionen von Leaflet zu benutzen ist es nötig die vorprogrammierten CSS- und JavaScript-Dateien in unserem Dokument zu integrieren.

Füge dazu in dem ```<head>``` Teil deines Dokumentes Leaflet CSS hinzu:

```
<link
      rel="stylesheet"
      href="https://unpkg.com/leaflet@1.6.0/dist/leaflet.css"
      integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ=="
      crossorigin=""
    />
```

Anschließend Leaflet JavaScript. Beachte, dass Leaflet JavaScript **nach** Leaflet CSS eingebunden werden muss.

```
<script
      src="https://unpkg.com/leaflet@1.6.0/dist/leaflet.js"
      integrity="sha512-gZwIG9x3wUXg2hdXF6+rVkLF/0Vi9U8D2Ntg4Ga5I5BZpVkVxlJWbSQtXPSiUTtC0TjtGOmxa1AJPuV0CPthew=="
      crossorigin=""
    ></script>
```

Für die Leaflet-Karte erstellen wir ein ```<div>``` Element mit der id "map" im ```<body>``` Teil des Dokumentes, welches die Karte enthalten soll:

```
<div id="map"></div>
```

Stelle sicher, dass das ```<div>``` Element eine definierte Höhe hat, indem du ihn beispielsweise in CSS festlegst. Dazu den folgenden Code zwischen den ```<style>``` Tags im ```<head>``` Teil platzieren:

```
#map { height: 500px; }
```

Nun kannst du deine erste Karte initialisieren.

Wir stellen die Ansicht auf das Zentrum von Stuttgart und bestimmen eine Zoomstufe:

```
var map = L.map('map').setView([48.775, 9.182], 13);
```

**Übung:**
1) Finde heraus wofür die oben stehenden Zahlen stehen?
2) Erstelle eine Karte auf der Münster im Zentrum zu sehen ist und stelle das Zoomlevel so ein, dass die Stadt Dortmund auf der Karte zu sehen ist.

Füge als nächstes deiner Karte einen Tilelayer hinzu. In diesem Fall handelt es sich um den Tilelayer "Mapbox Streets". Das Erstellen eines Tilelayers umfasst normalerweise die Definition der URL-Vorlage für die Layerbilder, des Beschreibungstextes und der maximalen Zoomstufe des Layers.

```
L.tileLayer('https://api.mapbox.com/styles/v1/{id}/tiles/{z}/{x}/{y}?access_token={accessToken}', {
    attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors, <a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="https://www.mapbox.com/">Mapbox</a>',
    maxZoom: 18,
    id: 'mapbox/streets-v11',
    tileSize: 512,
    zoomOffset: -1,
    accessToken: 'your.mapbox.access.token'
}).addTo(mymap);
```
