# Stundenblog
## Informatikstunde Nr. 1  (14.08.2019)
In der ersten Informatikstunde, habe ich mir Gedanken über mein mögliches Projekt gemacht. Dabei musste ich beachten, dass ich keinerlei Vorkenntnisse bezüglich des Programmierens besitze.
Dennoch wollte ich ein Spiel programmieren, denn sowas wollte ich schon immer mal machen.
 Ich machte mir also Gedanken, was für eine Art von Spiel ich programmieren könnte. Es sollte nicht zu schwer zu programmieren sein und 
 entschied mich schon einmal für eine 2D Welt, in welcher ich mein Spiel zum Leben erwecken möchte. Dazu soll die Spielmechanik einfach 
 und dennoch "fesselnd" strukturiert sein.
 Somit fasste ich zusammen, was mein Spiel folgendes beinhalten soll:
 
 1. Eine 2D-Welt mit einfachen Texturen 
 2. Eine packende Spielmechanik, welche den Spieler zum weiteren Verushen treibt.
 3. In Erinnerung bleibende Effekte, wie Musik, Texturen oder Texte.
 4. Der Spieler kann gerne ans Ende seiner Nerven gelangen.
 
 ## Informatikstunde Nr. 2  (20.08.2019)
 Heute beginne ich mit dem Schreiben meines Stundenblogs, wofür ich mir eine Liste mit Befehlen im Internet raussuche, denn der Blog wird im Code geschrieben. Ich wurde schnell fündig und habe nun, wenn immer ich am Blog schreibe, diese Liste mit Befehlen offen: [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#headers)
 
 Nun suche ich nach Inspirationen für mein Spiel, wofür ich mir Videos zu einfachen, aber "coolen", Spielen auf ["Youtube"](https://www.youtube.com/?gl=DE&hl=de) anschaue.
 Ich stoße bei meiner Suche auf viel verschiedene "Pixelart-games", wobei ich bemerke, dass ich sehr viele Möglichkeiten besitze ein Spiel auf diese Weise zu gestalten.
 
 ## Informatikstunde Nr. 3  (21.08.2019)
 Heute suche ich mir ein Programm aus, mit welchem ich mein Projekt verwirklichen möchte. Dabei suche ich viele Arten von einfachen Programmiersprachen, welche gut für Anfänger geeignet sind. Nachdem ich mir die Möglichkeiten und Schwierigkeitsgrade verschiedener Sprachen angeschaut hatte, entschied ich mich nach ["Greenfoot"](https://www.greenfoot.org/door) und ["Unity"](https://unity.com/de) für die ["Godot-Engine"](https://godotengine.org/).
 Diese Engine besitzt die Möglichkeit mir, als Anfänger, hilfreiche Vorlagen zu bieten und zudem viele aufschlussreiche Tutorials. Außerdem gibt es eine einfach Hilfe in der Engine selber, wodurch ich einfach wichige Befehle und ihre Funktion finde.
 Zudem kann ich nun mich einfach zwischen einer 2D- oder 3D-Welt entscheiden, wobei ich mich für eine 2D-Welt entscheide:
 ![Menu erster test](https://user-images.githubusercontent.com/9617583/28182906-940ac83a-67db-11e7-8472-59ce285900b1.gif)

Nun werde ich beginnen heruszufinden, wie ich texturen in das Spiel bekomme und die allgmeine Spielwelt erschaffe, in welcher meine Figur gesteuert wird. Dazu schaue ich mir ein hilfreiches Video auf Youtube an, in welchem ein Spiel programmiert wird bzw. es angefangen wird: [Videoreihe](https://www.youtube.com/watch?v=zBlVezhQeq0&list=PLv3l-oZCXaqkUEqrLsKJIAhAxK_Im6Qew&index=2)

## Informatikstunde Nr. 4  (27.08.2019)
Heute habe ich angefangen die ersten zwei Vidoes, der Videoreihe, anzuschauen. Damit konnte ich mir einen kleinen Überblick verschaffen, bezüglich der Frage, wie man überhaupt beginnt mit solch einer Programmierung und was ich dazu benötige. 
Ich weiß nun, dass ich ein Texturenprogramm brauche, in welchem ich meine Figuren erstellen kann, wenn ich dies tun möchte. Allerdings kann ich auch Bilder aus dem Internet verwernden, wobei es sicherlich viele hilfreiche Foren, mit vorgefertigten Texturen gibt. Ich weiß nun zudem, dass wie ich mir meine Engine so sortiere, dass es so bequem, wie möglich fpr mich ist, wenn ich anfange zu proframmieren.

Ich beginne also damit, Bilder im Internet zu suchen, welche ich im Spiel verwenden möchte. Dafür lege ich einen neuen Ordner auf dem Desktop an, in welchem ich meine Dateien vorerst sotiere.

## Informatikstunde Nr. 5  (28.08.2019)
Ich habe heute viele der essentiellen Sounds, Bilder und Musiken heruntergeladen und in meinem Sammelordner sortiert. Diese habe ich über die Unterrichtsstunde gesammelt und sende sie mir am ende per E-mail, an mich selber. Somit kann ich Zuhause damit anfangen zu programmieren.

## Zuhausestunde Nr. 1  (22.09.2019)
Ich habe bemerkt, dass in der Videoreihe, welche mir als Hilfe dient, eine ältere Version der Engine genutzt wird. 
Das heißt, ich werde recherchieren müssen, wie alte Befehle in neue übersetzt wurden. Für meine Recherche nutze ich das [Godot-Forum](https://www.godot-community.de/). Hier finde ich viele Diskussionen und Hilfestellungen rund um die Engine und ihre Sprache.
Ich beginne nun damit die, in der Programmierung genutzten, Dateien in die richtig benannten Ordner zu sotieren. 
Dabei dient ein "sprites"-Ordner ordner für die Texturen, welche ich für mein Spiel verwende. Dazu kommt ein "Skript"-Ordner im welchen ich die verschiedenen Skripts aufbewahre, welche die Befehle und Gegebenheiten für das Spielumfeld und die Objekte im Spiel bestimmen.

### Erster Schritt: 
Zuerst ändere ich die allgemeine Farbe des Spielhintergrundes in Schwarz, denn mein Spiel findet im Weltraum statt.
Als nächstes erstelle ich bereits mein erstes Objekt: Das Raumschiff, welches man im Spiel steuert. Dazu erstelle ich eine "Node", an welche ich einen "Sprite"-Pfad und einen "Collition"-Pfad anschließe. Die "Node" stellt dabei das Objekt selber da und in dieser wird später auch der Programmiertext kodiert. Der "Sprite"-Pfad sorgt dafür, dass das Raumschiff eine Textur bekommt und der "Collition"-Pfad sorgt für die "Hitbox". Diese bestimmt den bereich in welcher das Objekt mit anderen "Hitboxen" reagiert.
Den "Sprite"-Pfad verinde ich nun mit einer Datei, welche meine Textur ist. Somit bekommt mein Raumschiff ein Aussehen.
Danach erstelle ich eine "Collition-Hitbox" welche der Größe meines Raumschiffes entspricht, damit es so wirkt, als würde das Raumschiff etwas berühren und mit dem Berührten reagieren. Da diese beiden Pfade in einer Node, also dem Objekt "Raumschiff" plaziert sind, werden die verbunden und zusammen zur Objekt der "Node". Der folgende Code sieht dann wie folgt aus:
![Code für das Schiff](https://www.bilder-upload.eu/bild-0e1dbd-1569406227.png.html)

### Zweiter Schritt:
Zunächst muss ich dafür sorgen, dass ich mein Raumschiff steuern kann. Dafür werde ich die Maus als Controller nutzen. Für das im ersten Schritt erstellte Objekt schreibe ich also ein Skript wodurch das Raumschiff weiß, dass es meinem Mauszeiger folgen muss, sofern sich dieser bewegt. Dabei hatte ich zuerst das Problem, dass wenige Befehle in, der von mir verwendeten, neueren Version von Godot, verändert wurden. Die Funktion dieser bleibt dennoch die Gleiche. Zuerst also versuchte ich dieses Skript:
![Falsches Skript]([URL=https://www.bilder-upload.eu/bild-15457b-1569484584.png.html][IMG]https://www.bilder-upload.eu/thumb/15457b-1569484584.png[/IMG][/URL])







## Informatikstunde Nr. 6  (24.09.2019)
Heute schreibe ich lediglich meinen Studenblog weiter. Dabei beschreibe ich, was ich Zuhause erarbeitet habe in einzelnen Schritten.

## Informatikstunde Nr. 7  (25.09.2019)
Heute habe ich gemerkt,dass ich keine Bilder in meinem Studenblog einfügen kann, sofern ich es nicht über einen Web-Link versuche. 
Allerdings sind meine Bilder auf dem USB-Stick und auf dem Rechner gespeichert. Also versuche ich die Bilder auf Google hochzuladen. Allerdings fallen diese dann in viel zu kleiner Auflösung aus.

## Informatikstunde Nr. 8  (26-09-2019)
Ich entscheide mich dazu, das Problem mit den zu kleinen Bildern im Stundenblog ein anderes Mal zu solvieren, denn am Ende werde ich trotzdem den gleichen Befehl nutzen müssen. Somit füge ich erst einmal weiterhin die benötigten Bilder ein und schreibe weiter auf, was ich Zuhause erarbeitet habe.

