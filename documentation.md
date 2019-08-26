# Toolchain
###Objektorientierte Progr. und Entwickl. (3IM-OOP-IM)

## Gliederung:

1. Einleitung, Allgemeines
2. Titel
3. Skizze/Beschreibung
4. Anforderungen (Lastenheft)
5. Team-Mitglieder und Entwicklung
6. Aufgabenverteilung
7. Archiketur
8. Timeline Milestones
9. Bug-Liste (optional)


## 1. Einleitung

Dieses Projekt entstand im Rahmen des Moduls "Objektorientierte Progr. und Entwickl. (3IM-OOP-IM)" des Medieninformatik Studiums im 2. Semester. 
Das Ziel war die Erstellung einer Web-App, mit welcher die Werkzeuge (Tools) eines Unternehmens erfasst werden können. In Folge dessen kann jeder Mitarbeiter alle genutzen Tools auf einen Blick erfassen und nutzen.

Das Main-Git-Repo findet man unter: [renickbuettner/toolchain](https://github.com/renickbuettner/toolchain) 

Ein zweites Git-Repo für Medieninhalte, Coperate Design, Icons und sonstiges findet man unter: [seppel3599/toolchain-media](https://github.com/seppel3599/toolchain-media)

Zum Testen der App kann man die Schrittfolge in der [README](https://github.com/renickbuettner/toolchain/blob/master/readme.md) nachlesen oder die [Testseite](https://renick.io/) nutzen. Für den Fall des lokalen Betriebs bitte die Voraussetzungen in der README beachten. 


## 2. Titel

Der Name **Toolchain** leitet sich aus der Funktion der App ab: Das Verketten bzw. zur Verfügung stellen von Werkzeugen.



## 3. Skizze und Beschreibung

Ein Werkzeug zum Organisieren der in einem Unternehmen genutzten Software, Webseiten und anderer Tools.
Die Objektorietierung findet in PHP statt. Wir nutzen das PHP Framework Laravel und eine simple sqlite-Datenbak. Das Frontend wurde mit JavaScript gebaut.

Mookups zur App, die Mitte Mai 2019 entstanden sind:
![Toolchain_Mookup_1](mookups/Toolchain_Mookup_1.svg)

![Toolchain_Mookup_2](mookups/Toolchain_Mookup_2.svg)

![Toolchain_Mookup_3](mookups/Toolchain_Mookup_3.svg)


## 4. Anforderungen (Lastenheft)

### Mindestumfang

- Web-App mit Laravel:
  - erstellen, editieren und löschen von Einträgen für Werkzeuge mit Titel, Beschreibung, Bildern, Logos die jeder Nutzer selber anlegen kann
  - Globale Übersicht, kategorisiert
  - Exportfunktion


### Mögliche Erweiterungen
  
Weiterhin haben wir ebenfalls mögliche Erweiterungen formuliert die bei frühzeitiger Fertigstellung noch umgesetzt werden sollten:

- Login mit Single Sign-On (Google)
- completly responsive 
- Integration einer personalisierten Suchmachine mit persönlichen Informationen (Cyberduck, Google)


## 5. Team-Mitglieder und Entwicklung

**@Renick @Jonas Bitte ergänzen/korrigieren!**

Das Team setzt sich folgendermaßen mit zusammen: 

- Renick Büttner
  - **Teamleitung**
  - Webdevelopment
  - Backend
- Jonas Wagner
  - Webdevelopment
  - Frontend
  - Testing
  - Bug fixing
- Sebastian Walter
  - Grafiken (Diagramme, Icons, ...)
  - Design (Mini-CD)
  - Präsentation
  - Dokumentation

## 6. Aufgabenverteilung

**@Renick @Jonas Bitte ergänzen/korrigieren!**

Bei der Aufgabenverteilung konnten wir uns im allgemeinen ziemlich schnell einigen. Das Renick die Aufgaben des 
Teamleiters/Projektmanagers übernimmt war aufgrund seiner Erfahrung bei solchen Projekten klar. Weiterhin haben Jonas 
und Renick bereits eingehende Erfahrung mit PHP bzw. direkt mit dem Laravel Framework. Sie fiel die Programmierung zu 
Renick und Jonas. Für ein Projekt dieses Umfanges wollten wir weiterhin ungern die Programmierung auf alle 
Teammitglieder aufteilen, um Absprachen und Rückfragen nicht ins unermessliche laufen zu lassen. So fielen die 
Rahmentätigkeiten zu Sebastian. Der sich im Folgenden um die Gestaltung der App, Design, Dokumentation, Absprachen und 
auch um die Abgabe kümmerte.   

### genaue Aufgabenverteilung:

- Renick Büttner
  - Git-Repo
    - Initialisieren und Verwalten
  - Projektmangament - Webdev
    - Aufgaben Definition und Verteilung
  - Entwurf - Prototyp
  - Projektidee
- Jonas Wagner
  - Frontend
    - CSS und JS
  - Google SSO
  - Writing simple Tests
  - Erweiterung um kleinere Features
- Sebastian Walter
  - Entwurf und Umsetzung der Icons
    - Navigation, Button, Schnelleditierungsmenü
  - Mini-CD
    - Schriftarten festlegeFarbtheme festlegen
    - Logo und Schriftzug entwerfen und umsetzen
  - Erstellen der Dokumentation
    - Schreiben
    - Formatierung und Layouten
  - Erstellen der Präsentation
    - Schreiben
    - Formatierung und Layouten


## 7. Architektur 

@Renick: Bitte **kurz** die Architektur beschreiben!
@Sebastian: unbedingt noch die UML-Diagramme ergänzen



## 8. Timeline, Milestones

Die Timeline lässt sich am besten über die Github Commits verfolgen.

**@Renick @Jonas Bitte ergänzen/korrigieren!**

- Anfang Mai: Projektidee durch Renick 
- Anfang Mai: Projektentwicklung und Definition durch alle
- Anfang Mai: Apsrache mit Professor Hara und Input für die Idee
- Anfang Mai: Github-Repository erstellen und initalisieren durch Renick ⇒ [Toolchain](https://github.com/renickbuettner/toolchain/issues)
- Mitte Mai: Entwurf von Mookups
- Mitte Mai: Definition der Anforderungen -> kleines Lastenheft
- Mitte Mai: Erste Aufgaben werden in Notion definitiert und verteilt
- Mitte Mai: Abgabe der Projektidee an Professor Hara
- Erste Commits durch Renick
  - Erstellen der Login-Maske
- Erstellen eines eigenen Repositories für die Medieninhalte, Dokumentation und Informationen zum Design durch Sebastian ⇒ [Toolchain-Media](https://github.com/seppel3599/toolchain-media)
- Längere Pause: durch Prüfungen
- Juli: Entwurf und Umsetzung der Icons durch Sebastian
- Juli: Fortsetzen der Arbeit an der Web-App durch Renick und Jonas
- Anfang August: Schreiben der Dokumentation
- Ende August: Letzte Abstimmungen mit Professor Hara
- Ende August: Abgabe

erste Lauffähige Version; Laravel-Import; wann, welche Version mit welchen Funktion, 

## 9. Bug-Liste

- RegEx in serviceEditor.js buggy aber erstmal funktionsfähig 
- Die Kategorie auf der detailedView Seite wird immer klein Geschrieben (parsing bug)
- Der eingebaute description Editor übergibt seine eigene Font und unsere wird Überschrieben
- Kein direkter Bug, aber Kategorien müssen gleich geschrieben werden damit die jeweiligen Services in der selben Kategorie landen --> hier wäre ein dropdown Menü in der Editor Seite angebracht, durch welche man einen Service einer bereits bestehenden Kategorie zuordnen kann
