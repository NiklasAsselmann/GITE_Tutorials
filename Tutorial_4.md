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

Öffne dazu einen beliebigen Texteditor. Wir empfehlen an dieser Stelle einen HTML-Editor, wie [Brackets](http://brackets.io) oder [Atom](https://atom.io), welche für das Erstellen von Webanwendungen gut geeignet sind. Letzlich funktioniert aber auch ein einfacher Notepad-editor.

Zunächst bereiten wir unser HTML-Dokument vor:

'''
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
'''
