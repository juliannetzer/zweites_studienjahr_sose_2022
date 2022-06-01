# 03.06.2022 - Zelluläre Automaten 


## Referenzen Emergenz/ Zelluläre Automaten/ Game of Life 

* [Wikipedia: Emergenz](https://de.wikipedia.org/wiki/Emergenz)
* [Wikipedia: Zelluläre Automaten](https://de.wikipedia.org/wiki/Zellulärer_Automat)
* [Coding Train](https://natureofcode.com/book/chapter-7-cellular-automata/)
* [Stephen Wolfram's A New Kind of Sciene](https://www.wolframscience.com/nks/)
* [Troika: Hierophany](http://troika.uk.com/work/troika-hierophany/)
* [Troika: Calculating the Universe](http://troika.uk.com/work/troika-calculating-the-universe/)
* [Wikipedia: Conway's Game of Life](https://de.wikipedia.org/wiki/Conways_Spiel_des_Lebens)
* [New York Times: The Lasting Lessons of John Conway's Game of Life](https://www.nytimes.com/2020/12/28/science/math-conway-game-of-life.html)
* [Life Wiki](https://conwaylife.com/wiki/)

### Übung 1.1: Einfacher Wolfram-Automat
![Wolfram1](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_1_wolfram_1.jpg)
![Wolfram1](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_1_wolfram_2.jpg)
![Wolfram1](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_1_wolfram_3.jpg)
![Wolfram1](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_1_wolfram_4.jpg)

Erstelle einen einfachen Zellulären Automaten (Wolfram Automat), mit 10 Startzellen, bei dem du die Startzeile selbst festlegst 

Die Regeln sind dabei wie folgt: 
- wenn die aktuelle Zelle und die beiden benachbarten Zellen weiß sind, dann färbe die Zelle schwarz
- wenn nur die aktuelle und die linke Nachbarzelle weiß sind, dann belasse die Zelle weiß
- wenn beide Nachbarn weiß sind, aber die aktuelle Zelle schwarz ist, dann belasse sie schwarz
- wenn die aktuelle Zelle und die rechte Nachbarzelle schwarz sind, und die linke Zelle weiß, dann färbe sie weiß
- wenn die aktuelle Zelle und die rechte Nachbarzelle weiß sind, aber die linke Nachbarzelle schwarz ist, belasse sie weiß 
- wenn die aktuelle Zelle weiß ist und die benachbarten schwarz, dann färbe sie schwarz 
- wenn die aktuelle und die linke Nachbarzelle schwarz sind, die rechte weiß, dann färbe die Zelle weiß 
- wenn die aktuelle und beide benachbarten Zellen schwarz sind, belasse die Zelle schwarz 


Fortgeschritten: 
* gehe zu Übung 1.2

Mögliche Lösung: https://editor.p5js.org/netzerjulian/sketches/4K7vkUY8y

### Übung 1.2: Wolfram-Automat
![Wolfram1](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_1_wolfram_1.jpg)
![Wolfram1](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_1_wolfram_2.jpg)
![Wolfram1](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_1_wolfram_3.jpg)
![Wolfram1](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_1_wolfram_4.jpg)

Erweitere deinen Automaten jetzt, indem du die Zahl der Startzellen variabel machst und diese zu Beginn zufällig füllst. Verändere auch jetzt wieder die Regeln und beobachte wie sich das Ergebnis verändert.
Erstellen mindestens 5 Variationen und lade sie auf die Nextcloud. 

Fortgeschritten: 
* Wie kannst du die erste Zeile nicht zufällig füllen, sondern gezielt mit einzelnen schwarzen Vierecken füllen, welche Muster kannst du damit erzeugen? 
* Verändere die Farben (z.B. auch im Laufe der Generationen)
* Kannst du auch Regeln erstellen, die auf mehr als drei nebeneinander liegende Zellen einen Einfluss haben? 

Mögliche Lösung: https://editor.p5js.org/netzerjulian/sketches/Qy670u-3P

### Übung 2.1: Game of Life
Öffne die Game of Life Online-Anwendung: https://playgameoflife.com/

Aufgabe: Probiere eine Formation zu finden, die möglichst lange interessante Muster erzeugt, du kannst dich dabei auch auf der folgenden Website inspirieren lassen: [Life Wiki](https://conwaylife.com/wiki/). Speichere Muster (Screenshot) ab, die besonders gut funktionieren. 

Einige interessante Formen sind z.B.: 
* [Übersicht](https://conwaylife.com/wiki/Tutorials)
* Spaceships:
	* [Glider](https://conwaylife.com/wiki/Glider)
	* [Lightweight spaceship](https://conwaylife.com/wiki/Lightweight_spaceship)
* Oscillators: 
	* [Worker Bee]()


### Übung 2.2: Map Generator 
Probiere mit dem folgenden Generator Grafiken zu erstellen, die an Leveldesigns erinnern. 
https://editor.p5js.org/netzerjulian/sketches/kFRZRF-Aq

Der Generator funktioniert nach einem ähnlichen, aber leicht vereinfachten Prinzip wie Game of Life: 

- am Anfang wird die Fläche zufällig mit schwarzen (inaktiv) oder weißen (aktiv) Quadraten gefüllt (die Wahrscheinlichkeit, dass ein Quadrat weiß gefüllt wird, kannst du über den "probability"-Wert einstellen)
- du kannst einstellen, ab wie vielen aktiven Nachbarn die Zelle inaktiv geschaltet wird, also schwarz gefärbt wird (Parameter "overpopulation")
- du kannst einstellen, ab wie viele inaktiven Nachbarn die Zelle aktiv geschaltet wird, also weiß gefärbt wird (Parameter "reproduction")
- außerdem kannst du die Auflösung die Zahl der Generation einstellen 

![Zellulärer Automat](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/2_2_cellular_1.jpg)
![Zellulärer Automat](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/2_2_cellular_2.jpg)
![Zellulärer Automat](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/2_2_cellular_3.jpg)
![Zellulärer Automat](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/2_2_cellular_4.jpg)

***
***

## Aufgabe: 
Erstelle ein generatives Leveldesign mit Zellulären Automaten, du kannst auch Perlin Noise mit einbauen. Du kannst wie beim letzten Mal mit Grafiken arbeiten, den 8-bit-Grafik-Generator findest du [hier](https://make8bitart.com/). Erstelle mindestens 5 Variationen und lade die Variationen wieder auf die Nextcloud (Link auf Incom). 

Beispiele: 
* Erstelle ein Jump ’n’ Run Level mit verschiedenen Plattformen ähnlich Super Mario (die Plattformen mit dem Zellulären Automaten, die Wolken mit Perlin Noise)
	* [Beispielbild Super Mario](https://videospielhalbwissen.de/wp-content/uploads/2020/02/timeline-super-mario-bros.png)
* Erstelle ein Level ähnlich zu Pac Man 
	* [Beispielbild Pac Man](https://img.redbull.com/images/c_limit,w_1500,h_1000,f_auto,q_auto/redbullcom/2020/7/8/xzlb8zjf9aghyiotbb1f/pac-man-screenshot)
* Erstelle ein Spiel mit Caves/Dungeon, z.B. ein Maulwurf oder Ameisensimulator
	* [Beispielbild Maulwurf](https://www.ndr.de/ratgeber/verbraucher/maulwurf178_v-fullhd.jpg)
* Erstelle Texture mit dem 8-Bit-Grafik-Generator 

Beispiel mit Game of Life Algorithmus: https://editor.p5js.org/netzerjulian/sketches/yqDpatvnx

![Zellulärer Automat](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/BeispielCellular1.jpg)
![Zellulärer Automat](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/BeispielCellular2.jpg)

