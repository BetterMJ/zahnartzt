# Webseite Zahnarzt

## Aufgabenstellung
Aus persönlichem Interesse, aber auch als Auftrag, haben wir als Gruppe unsere erste Webseite im Lernatelier programmiert. Wir haben dieses Projekt in der Gruppenarbeit gemacht, wobei dieses ein dann ein Gruppenportfolio ist. Bei diesem Portfolio gehen wir auf unsere Webseite ein und schauen uns den Navigationbereich genauer an.
- Der Leser erfährt, was ein Navigationbereich ist.
- Der Leser lernt, wie man ein Navigationsbereich erstellt.
- Der Leser lernt, wie man den Navigationsbereich "sticky" macht.

## Inhalt 🧠
### Der Navigationsbereich
Ein **Navigationsbereich (Nav)** ist ein Teil der Webseite, mit dem man sich navigieren kann, zum Beispiel kann man mit diesem auf weitere Unterseiten zugreifen oder auf einen Bereich der momentanen Seite. Man kann auch darin das Logo der Firma und weiteres hineinschieben, der Nav findet man meistens ganz oben an der Webseite.

In HTML erstellt man einen Nav, indem man den command <nav></nav> einfügt und darin etwas schreibt, zum Beispiel einen Link auf eine weitere Seite schreiben kann, in unserem Falle https://bettermj.github.io/zahnarzt/albanian.html.
Man kann einen Link mit  ```<a href="albanian.html">Albanian</a>``` einfügen, man muss aber schauen, dass man die Seite ``albanian.html`` erstellt hat.

Jetzt müssen wir nur noch schauen, dass wir den Nav richtig positionieren, das machen wir mit CSS. Mit CSS ist wichtig, dass man ```width: 100%``` und ```top: 0``` hat, denn damit sagen wir, dass der Nav ganz oben am Bildschirm soll sein und die Breite des ganzen Bildschirmes soll haben.

### Code HTML
```HTML
   <nav>
        <img src="Logo.jpg" alt="Logo">
        <a href="#thetop"><button type="submit" class="contactsubmit" onclick="openPopup()">Contact</button></a>
        <a href="albanian.html">Albanian</a>
    </nav>

```
### Code CSS
```CSS
nav{
    /*background-color: rgb(61, 61, 61);*/
    background-color: var(--darkbluea);
    font-size: 4rem;
    display: flex;
    width: 100%;
    height: 10vh;
    align-items: center;

    position: sticky;
    overflow: hidden;
    top: 0;
    margin-bottom: -10vh;
    z-index: 5;
}

```
### Bild der Webseite (drücken um zu besuchen)
[![](https://i.imgur.com/TvHMOOS.png)](https://bettermj.github.io/zahnarzt/)
## Reflexion ✨
Wir fanden es gut, dass wir zusammen auf Github konnten arbeiten, da wir damit einfach Code teilen konnte und nicht einer der Gruppe das Programm auf seinem Computer tragen muss. Durch Github konnten wir genauer sehen wer welche Änderungen gemacht wurden und einfach 
Als Verbesserung könnte man .
Zum Beispiel kann man , , anstatt.

Am 5.4.2022 hat Matteo ein Portfolio gemacht, wo er als Verbesserungsvorschlag hatte, dass 
Wir haben 

## Verifikation ✅
Man lernt was Unity ist im Inhalt und dann "Ein Spiel mit Unity" ganz oben. 
Man findet heraus, wie man eine Szene macht im Inhalt, "Ein Spiel mit Unity" und dann der Teil in der Mitte.
Um über die Buttons herauszufinden, kann man zum Inhalt nochmal gehen, "Ein Spiel mit Unity" und dann der untere Teil.

