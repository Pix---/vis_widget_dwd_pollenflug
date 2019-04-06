# VIS Darstellung für ioBroker Pollenflug Adapter

![Screenshot](screenshot.jpg)

## VIS Widget
Code zum Importieren im VIS Editor in der Datei ``widget``

Es wird der ioBroker [Pollenflug-Adapter](https://github.com/schmupu/ioBroker.pollenflug) benötigt.

Bitte die Datenpunkte vor dem Importieren auf die eigene Region anpassen. Hier im Code ist die Region Oberbayern (#121) eingestellt. Mit der Funktion "Suchen und ersetzen" eines Texteditors ist das schnell erledigt.

## CSS
CSS Code zum Kopieren in den Reiter CSS/Projekt des VIS-Editors in der Datei ``css``
Im Code sind Fallbacks eingebaut, die u.a. für die CSS-Validität nötig sind. Falls der Client-Browser mit den RGBa-Angaben (Rot/Grün/Blau/Alpha) nicht arbeiten kann, nutzt er die Fallback-Definitionen. Diese Definitionen sind absichtlich zum Teil mit "unpassenden" Farben ausgestattet um den Fallback zu kennzeichnen.

![Screenshot](screenshot_detail.png)

## History
### 0.0.1 initial (06.04.2019)
Stand: https://forum.iobroker.net/post/250505
+ Farben zentral über CSS steuerbar
+ CSS-Validität optimiert

Copyright: Pix 2019
MIT Licence
