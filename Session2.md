# 27.05.2022 - Noise

## Generative Landschaften 

* [Studio Joanie Lemercier - La Montagne](https://joanielemercier.com/lamontagne/)
* [Memo Akten & Daniel Berio- Bozork Quest: In search for the lost Stroompang](https://vimeo.com/113106061)
* [Inconvergent - Isopleth](https://inconvergent.net/app/isopleth/)
* [Big Robot - British Countryside Generator](https://bldgblog.com/2013/04/british-countryside-generator/)
* [Molleindustria - Lichenia](https://molleindustria.org/lichenia/)


## Perlin Noise & 10,000 Bowls of Oatmeal
* [Ken Perlin](https://de.wikipedia.org/wiki/Ken_Perlin)
* [Text: Kate Crawford - So you want to build a generator](https://galaxykate0.tumblr.com/post/139774965871/so-you-want-to-build-a-generator)

### Übung 1.1: Perlin Noise in p5.js
![Noise 1.1](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_1_PerlinNoise.jpg)

Erstelle ein Perlin Noise Grid aus Vierecken. Die Größe der Vierecke, sowie die Auflösung des Perlin Noises soll dabei variabel sein. Erstelle außerdem eine Funktion, mit der du das Bild speichern kannst, wenn du auf "S" drückst. 

Hinweise: 
* [Noise](https://p5js.org/reference/#/p5/noise)
* [Key-Pressed](https://p5js.org/reference/#/p5/keyPressed)

Mögliche Lösung: https://editor.p5js.org/netzerjulian/sketches/XvAtisbfJ

Fortgeschritten: 
* Gehe direkt zu Übung 1.2

### Übung 1.2: Perlin Noise
![Noise 1.2](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_2_PerlinNoise_Octaves1.jpg)
![Noise 1.2](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_2_PerlinNoise_Octaves8.jpg)

Erweitere deine Skizze aus Übung 1.1 um die Parameter Octave (lod) und Falloff (siehe Reference p5.js). Experimentiere mit den Werten, welcher Wert verändert das Noise wie? Wie ist die Beziehung zur Auflösung des Noise? 

Hinweise: 
* [Noise-Detail](https://p5js.org/reference/#/p5/noiseDetail)

Mögliche Lösung: 
https://editor.p5js.org/netzerjulian/sketches/aldzmMFMW

Fortgeschritten: 
* Übung 1.3 

### Übung 1.3: Kolorierung
![Noise 1.3](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_3_Perlin_Noise.jpg)

Färbe dein Noise nun mit verschiedenen Farben ein. Erstelle damit eine fiktive Landkarte. Wie kannst du durch Farben den Eindruck einer Landkarte verstärken? Wie kannst du durch die Farben und die Art des Noise verschiedene Karten erstellen? 

Mögliche Lösung: 
https://editor.p5js.org/netzerjulian/sketches/y3PleIsTD

![Noise 1.3](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/Maps/maps_1.jpg)
![Noise 1.3](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/Maps/maps_2.jpg)
![Noise 1.3](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/Maps/maps_3.jpg)
![Noise 1.3](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/Maps/maps_4.jpg)
![Noise 1.3](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/Maps/maps_5.jpg)
![Noise 1.3](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/Maps/maps_6.jpg)

### Übung 1.4: Zusätzliche Objekte/Grafiken
![Noise 1.4](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/1_4_Objekte.jpg)

Füge in deine Karte zusätzliche Objekte ein, die nur an bestimmten Stellen auf der Karte erscheinen. Du kannst die Objekte z.B. mit einem 8-Bit Grafikgenerator (https://make8bitart.com/) erstellen. 

Mögliche Lösung: 
https://editor.p5js.org/netzerjulian/sketches/-Y6FGKc20

Fortgeschritte: 
Gehe direkt zur nächste Aufgabe. 

***
***

## Aufgabe: 
Erstelle mindestens einen Level/Landkarten-Generator basierend auf Perlin Noise. Auf der Karte sollen verschiedene Objekte zu finden sein.
Abgabe: Exportiere mindestens 10 Variationen in .jpg-Dateien mit mindestens 2000x3000px. Lade die jpg-Dateien zusammen mit einer Text-Datei, in der sich ein Link zu deinem Sketch befindet, in die Nextcloud (Link auf Incom).

Fortgeschritten: 
* Wie kannst du die Objekte unterschiedlich groß machen? 
* Baue Regler ein, um den Generator zu steuern 
* Wie kannst du die Karte interaktiv machen? z.B. ein Scroll-Effekt bei einer Bewegung mit der Maus.
* Wie kannst du einzelne Elemente auf der Karte animieren? z.B. das Wasser? 

Beispiel:
![Noise 1.3](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/BeispielMap.jpg)
![Noise 1.3](https://github.com/juliannetzer/zweites_studienjahr_sose_2022/blob/main/assets/BeispielMap2.jpg)





