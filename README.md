# Stundenblog
## Informatikstunde Nr. 1  (14.08.2019)
In der ersten Informatikstunde, habe ich mir Gedanken über mein mögliches Projekt gemacht. Dabei musste ich beachten, dass ich keinerlei Vorkenntnisse bezüglich des Programmierens besitze.
Dennoch wollte ich ein Spiel programmieren, denn sowas wollte ich schon immer mal machen.
 Ich machte mir also Gedanken, was für eine Art von Spiel ich programmieren könnte. Es sollte nicht zu schwer zu programmieren sein und 
 entschied mich schon einmal für eine 2D Welt, in welcher ich mein Spiel zum Leben erwecken möchte. Dazu soll die Spielmechanik einfach 
 und dennoch "fesselnd" strukturiert sein.
 Somit fasste ich zusammen, was mein Spiel folgendes beinhalten soll:
 
 1. Eine 2D-Welt mit einfachen Texturen 
 2. Eine packende Spielmechanik, welche den Spieler zum weiteren Versuchen treibt.
 3. Der Spieler kann gerne ans Ende seiner Nerven gelangen.
 
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

## Zuhausestunde(n) Nr. 1  (22.09.2019)
Ich habe bemerkt, dass in der Videoreihe, welche mir als Hilfe dient, eine ältere Version der Engine genutzt wird. 
Das heißt, ich werde recherchieren müssen, wie alte Befehle in neue übersetzt wurden. Für meine Recherche nutze ich das [Godot-Forum](https://www.godot-community.de/). Hier finde ich viele Diskussionen und Hilfestellungen rund um die Engine und ihre Sprache.
Ich beginne nun damit die, in der Programmierung genutzten, Dateien in die richtig benannten Ordner zu sotieren. 
Dabei dient ein "sprites"-Ordner ordner für die Texturen, welche ich für mein Spiel verwende. Dazu kommt ein "Skript"-Ordner im welchen ich die verschiedenen Skripts aufbewahre, welche die Befehle und Gegebenheiten für das Spielumfeld und die Objekte im Spiel bestimmen.

### Erster Schritt: 
Zuerst ändere ich die allgemeine Farbe des Spielhintergrundes in Schwarz, denn mein Spiel findet im Weltraum statt.
Als nächstes erstelle ich bereits mein erstes Objekt: Das Raumschiff, welches man im Spiel steuert. Dazu erstelle ich eine "Node", an welche ich einen "Sprite"-Pfad und einen "Collition"-Pfad anschließe. Die "Node" stellt dabei das Objekt selber da und in dieser wird später auch der Programmiertext kodiert. Der "Sprite"-Pfad sorgt dafür, dass das Raumschiff eine Textur bekommt und der "Collition"-Pfad sorgt für die "Hitbox". Diese bestimmt den bereich in welcher das Objekt mit anderen "Hitboxen" reagiert.
Den "Sprite"-Pfad verinde ich nun mit einer Datei, welche meine Textur ist. Somit bekommt mein Raumschiff ein Aussehen.
Danach erstelle ich eine "Collition-Hitbox" welche der Größe meines Raumschiffes entspricht, damit es so wirkt, als würde das Raumschiff etwas berühren und mit dem Berührten reagieren. Da diese beiden Pfade in einer Node, also dem Objekt "Raumschiff" plaziert sind, werden die verbunden und zusammen zur Objekt der "Node".


### Zweiter Schritt:
Zunächst muss ich dafür sorgen, dass ich mein Raumschiff steuern kann. Dafür werde ich die Maus als Controller nutzen. Für das im ersten Schritt erstellte Objekt schreibe ich also ein Skript wodurch das Raumschiff weiß, dass es meinem Mauszeiger folgen muss, sofern sich dieser bewegt. Dabei hatte ich zuerst das Problem, dass wenige Befehle in, der von mir verwendeten, neueren Version von Godot, verändert wurden. Die Funktion dieser bleibt dennoch die Gleiche. Zuerst also versuchte ich dieses Skript:




<a href="https://ibb.co/f2MRWKm"><img src="https://i.ibb.co/s2jS4DL/altes-skript-schiff.png" alt="altes-skript-schiff" border="0"></a>






Nach einer Rechere auf dem Godot-Forum und Korrektur des Codes, kam ich zu diesem Ergebnis:




<a href="https://ibb.co/0fB1w3q"><img src="https://i.ibb.co/LCQBGfS/Code-Schiff.png" alt="Code-Schiff" border="0"></a>






### Dritter Schritt:
Als nächstes muss ich eine Hintergrund (Sterne) einfügen, welche von "oben" nach "unten" verlaufen und somit für die Illusion sorgen, als würde das Raumschiff sich fort bewegen. Dazu füge ich Texturen für Sterne ein über eine "Sprite", welche mit einer "Node" verbunden ist, in welcher ich dann Befehle über das Skript, an die Textur weiter geben kann. Dazu verwende ich diesen Code:




<a href="https://ibb.co/ZVBc8q7"><img src="https://i.ibb.co/37pSNgQ/Code-sterne.png" alt="Code-sterne" border="0"></a>

(Das y in der ersten Reihe des Codes im Befehl "Extends" wurde natürlich noch korrigiert)




### Vierter Schritt:
Nun habe ich ein Raumschiff, welches mit der Umwelt reagieren kann und gesteuert werden kann. Als nächstes programmiere ich also den ersten Gegner von zwei. Ich beginne, wie auch mit bei dem Schiff, damit eine Node zu erstellen welche eine Sprite und ein Skript bekommt. 
Das Skript sieht für meinen "Enemy" wie folgt aus:

<a href="https://ibb.co/FnDh7vZ"><img src="https://i.ibb.co/cxryT5f/Code-Enemy.png" alt="Code-Enemy" border="0"></a>


Hierbei konnte ich die gleichen Befehle nutzen, wie sie auch im Video dargestellt werden. Eine weitere Recherche blieb mir hier also erspart.

Allerdings musste ich noch ein weiteres Skript, an eine Kopie des Skripts des Enemys, anfügen, welche dafür sorgt dass diese Enemys oben im Spiel gespawnt werden. Dazu verwende ich diesen Skript:

<a href="https://ibb.co/HnBKhcn"><img src="https://i.ibb.co/gzmr40z/code-spawner-enemy.png" alt="code-spawner-enemy" border="0"></a>


## Informatikstunde Nr. 6  (24.09.2019)
Heute schreibe ich lediglich meinen Studenblog weiter. Dabei beschreibe ich, was ich Zuhause erarbeitet habe in einzelnen Schritten.

## Informatikstunde Nr. 7  (25.09.2019)
Heute habe ich gemerkt,dass ich keine Bilder in meinem Studenblog einfügen kann, sofern ich es nicht über einen Web-Link versuche. 
Allerdings sind meine Bilder auf dem USB-Stick und auf dem Rechner gespeichert. Also versuche ich die Bilder auf Google hochzuladen. Allerdings fallen diese dann in viel zu kleiner Auflösung aus.

## Informatikstunde Nr. 8  (26.09.2019)
Das Problem mit den zu kleinen Bildern, habe ich nun behoben. Ich musste lediglich einen anderen Befehl verwenden, welcher das Bild als "Vorschau" darstellt, sonder als "Vollbild". Die Bilder ludt ich im Internet mit der Website [ImgBB](https://de.imgbb.com/) hoch.

## Zuhausestunde Nr. 2  (10.10.2019)
Ich arbeite dort weiter, wo ich gestoppt hatte.

### Fünfter Schritt:
Als nächstes programmiere ich meinem Schiff die Fähigkeit an, Projektile abfeuern zu können, womit man die "Enemys" zerstören kann. 
Dazu erstelle ich ein weiteres Objekt aus einer Node mit den Anhängen einer Skript und Sprite. Diesem Objekt muss ich nun den Befehl geben an einer Koordinate, in meiner Schifftextur, zu erscheinen, von dort aus gerade nach vorne zu "fliegen", indem ich das Verhältnis zur Gravitation ändere, wodurch sie entgegengesetzt der Gravitation verlaufen. Dazu muss ich eine Collition-Node anfügen, wodurch die Projektile die Gegner treffen und ihnen Schaden zufügen können. 
Dafür verwende ich diesen Code:


















## Informatikstunde Nr. 9  (23.10.2019)
Heute habe ich mir vorgenommen die Seite, auf welcher ich mein Spiel vorstelle, zu erarbeiten. Dazu suchte ich zuerst eine Möglichkeit mir eine kostenlose Internetseite einzurichten, auf welcher ich mein Spiel mit Bildern und Texten vorstelle, so wie es große Spieleentwickler mit ihren neuen Spielen tun.
Dazu nutze ich die Internetseite [Wix.com](https://de.wix.com)
Hier erstelle ich meine eigene kostenlose Seite: [Musicblaster](https://msteglich.wixsite.com/musicblaster). 
Diese bearbeite ich so, dass sie mein Spiel gut vorstellt.

## Informatikstunde Nr. 10  (24.10.2019)
Heute habe ich noch etwas an meiner Website gearbeitet, wobei ich denke, sie gut gestaltet zu haben.
Zudem schrieb ich meinen Stundenblog weiter.



## Informatikstunde Nr. 11  (29.10.2019)
Ich habe versucht euine Musikdatei in mein Spiel einzufügen, welche mein Raumschiff "einsammeln" kann, wodurch eigentlich Musik gespielt werden sollte. Allerdings gelingt mir das nicht, da die Dateien auf dem Schul-Computer verschoben wurden. Meine Engine kann nicht auf diese Dateien zugreifen. Zudem verutscht die Auflösung in meiner Engine gelegentlich, was meine Arbeit um einiges erschwert. Das ist also ein Problem, welches ich Zuhause beheben muss.
Zudem stehe ich Zuhause auch noch vor dem Problem, dass ich die Projektlile, welche mein Schiff schießen soll, nicht programmiert bekomme. Eine Lösung habe ich leider noch nicht gefunden.

## Zuhausestunde(n) Nr. 2  (29.10.2019)
Ich habe festgestellt, dass ich mit der 3.0 Version von Godot nicht weiter komme. Ich finde, selbst nach langer Suche, keinen passenden Code, welcher dafür sorgt dass die geschossenen Projektile ihren eigen linearen Weg folgen. 
Ich sehe mich gezwungen eine ältere Version der Engine aufzusuchen und werde fündig: [Godot Engine - old versionen](https://godot-engine.en.uptodown.com/windows/versions).
Ich wiederhole nun also alle Schritte beschrieben unter dem Artikel Zuhausesunde Nr. 1, mit einer älteren Verison, in welcher mein ode funktionieren sollte.

### Fünfter Schritt (vorherige Schritte unter "Zuhausestunde(n) Nr. 1")
Ich programmierte also die Projektile, welche aus meinem Schiff geschossen werden. Dabei bekamen diese Objekte lediglich den befehl an bestimmten Koordinaten meines Schiffs-Objektes zu erscheinen und eine Negative Gravitation aufzuweisen. Zudem befehle ich, dass diese Objekte verschwinden bzw. gelöscht werden, sofern diese aus dem Bild verschwinden.
Ich schrieb zudem einen Code und richtete eine Animation ein, welche an der Stelle, an welcher die Projektile entsehen, einen Feuer-Effekt einrichteten. Dieser erscheint auch, wenn Gegner getroffen werden. 

### Sechster Schritt
Mit dem Code für die Lasergeschosse, aus dem fünften Schritt, werde ich nun einen zweiten Gegner erstellen, welcher Laser gegen mein Schiff schießt. Hierfür verwende ich den gleichen Code für die Laser, richte ihre Gravitation aber in die andere Richtung, so dass sie nach "unten" laufen. Dazu füge ich den Code meines ersten erstellten Gegners und füge noch den Befehl hinzu, dass dieser nicht in einer geraden Linie läuft, sondern auch etwas seitlich und dabei am Bildrand abspringt. Nach einem Test wird mir gemeldet, dass ein Befehl nicht erkannt werden kann. Ich suchte nach diesem, fand einen Schreibfehler und korrigierte ihn, was den Fehler behob.

### Siebter Schritt
Um darzustellen, dass mein Schif Schaden bei Kontakt mit den Gegnern oder ihren Lasern kommt, Schaden erleidet, füge ich eine weiter Animation ein, welche "über" allen Objekten stattfindet. Diese ANimation besteht lediglich daraus den ganzen Bildschirm kurz rot werden zu lassen. Außerdem füge ich einen Lebensbalken ein, wobei es eigentlich 4 sind, welche untereinander liegen, mit jeweils einem Balken weniger als der andere. Ich programmiere diese Stelle also nun so, dass wenn immer mein Schiff Schaden erleidet, eine Schicht dieser vier Texturen ausgeblendet wird. Dadurch ist die untere im Vordergrund und es wirkt so, als wäre ein Balken verschwunden.
Nach einer Korrektur von 4 Zeil- und Schreibfehlern funktioniert das ganze einwandfrei.

### Achter Schritt
ZUnächst möchte ich weitere Animationen einfügen, welche eine Explosion darstellen, sofern ein Objekt all seine Leben verloren hat. Dafür code ich die Eigenschaft "armor" ein und programmiere ich jedem Objekt eine Anzahl von "armor" ein und erstelle eine Animation, mit Partikel-effekten. Diese erscheint nun immer, wenn ein Gegner oder mein Schiff zersört wird. Also befehle ich der Animation immer dann zu erscheinen, wenn ein Objekt all seine "armor" verloren hat.

### Neunter Schritt
Zu guter Letzt gebe ich meinem Spiele ein "HUD" (Head-up-display), durch welches der Spieler sehen kann, wie viele Leben sein Schiff besitzt und wie viele Punkte er, durch das zerstören von Gegnern, besitzt. Zudem erstelle ich ein Menu, mit welchem man das Spiel starten und beenden kann. Dieses Menu erscheint beim Öffnen des Spiels und sobald das Schiff zerstört wurde.

### Letzter Schritt für mein Projekt "SHOOTEM!"
Ich gebe meiner Website einen letzten Feinschliff und errichte einen Button auf meiner Website, welcher einen zu meiner Dropbox bringt, aus welcher man alles nötige dowloaden kann



