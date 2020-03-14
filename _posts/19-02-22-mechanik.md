---

title: "Mechanik"

categories:
    - klasse10
    - Physik

fach:
    - Physik

toc: true
toc_label: "Inhalt"
toc_sticky: true
---

**Alle Formeln sind auch noch mal im Tafelwerk zu finden: Dazu einfach auf die Seiten 84-86 gucken!  
(Außer bei Überlagerung von gleichförmigen Bewegungen)**  

## 1\. Definition von Bewegung <a name="defbewegung"></a>

1\. Ein Körper ist in **Bewegung**, wenn er seine Lage gegenüber einem Bezugkörper ändert.  
2\. Ein Körper ist in **Ruhe**, wenn er seine Lage gegenüber einem Bezugskörper beibehält.  

## 2\. Bewegungsformen

*   **geradlinige Bewegung** (Bsp.: Zug/Auto auf gerader Strecker, Mensch auf gerader Strecke)
*   **Kreisbewegung** (Bsp.: Riesenrad, Looping fahren, Erde dreht sich um die eigene Achse)
*   **Schwingung** (Bsp.: Schaukel, Pendel)

## 3\. Bewegungsarten

*   **gleichförmige Bewegung** (Geschwindigkeit($v$) konstant)
*   **ungleichförmige Bewegung** (veränderliche Geschwindigkeiten)

* * *

## 4\. Geschwindigkeit

**Definition:**

Die Geschwindigkeit gibt an, wie schnell oder wie langsam sich ein Körper bewegt.

**Formelzeichen:** $v$

**Einheiten:** $\dfrac{m}{s}$ und $\dfrac{km}{h}$

**Formel:** $v = \dfrac{s}{t}$  
$s$ = Strecke  
$t$ = Zeit

**Umrechnung von $\dfrac{m}{s}$ in $\dfrac{km}{h}$:**

$1\dfrac{m}{s} = 3,6\dfrac{km}{h}$

* * *

## 5\. Beschleunigung

**Definition:**

Die Beschleunigung gibt an, wie schnell sich die Geschwindigkeit eines Körpers ändert.

**Formelzeichen:** $a$

**Einheit:** $\dfrac{m}{s^2}$

**Formel:** $a = \dfrac{\Delta v}{\Delta t}$

**Strecke($s$) berechnen:**

$s$ = fläche von v/t Diagramm.

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/Beschleunigung1.jpg){:class="img-responsive"}

Da Fläche ein Dreieck und die Fläche von Dreieck (rechtwinklig) gleich $A = \dfrac{ab}{2}$
ist kommen wir auf $s = \dfrac{v_1t_1}{2}$ da aber die steigende Geschwindigkeit und keine Konstante, formen wir  
$a = \dfrac{v}{t}$ zu $v = at$ um welches wir dann in die Gleichung einsetzen:
$s = \dfrac{att}{2}$ und das ganze jetzt noch zusammenfassen: $s = \dfrac{at^2}{2}$

Ein s/t Diagramm würde dann aussehen, wie eine halbe Parabel

### 5.1 Der freie Fall

**Bewegungsform:** geradlinig  
**Bewegungsart:** gleichmäßige Beschleunigung

Die Beschleunigung, mit der ein frei fallender Körper fällt, wird als **Fallbeschleunigung $g$** bezeichnet.  
Die Fallbeschleunigung ist ortsabhängig.

In der Schule (wofür das hier gemacht ist) nutzen wir aber die Fallbeschleunigung: $g = 9,81\dfrac{m}{s^2}$

* * *

### 5.2 Gleichmäßig beschleunigte Bewegung mit Anfangsgeschwindigkeit

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/BeschleunigungMitV0.jpg){:class="img-responsive"}

**Endgeschwindigkeit $v_{end}$ berechnen:**  
$v_{end} = v_0 + \Delta v$ -> Schräge von $v_0$ bis $v_{end}$ = $a$ -> $a = \dfrac{\Delta v}{t}$ ->  
$\Delta v = at$ -> und da $v_{end} = v_0 + \Delta v$ -> $v_{end} = v_0 + at$

**Strecke $s$ berechnen:**  
$s$ = Fläche des Graphen. Dies unterteilen wir in 2 "Teile". Einmal ein Rechteck $A_1$ und ein Dreieck $A_2$  

$A_1$: Die Fläche eines Rechteckes ist wie folgt definiert: $A = ab$ und diese sind folgende Größen: $a = v_0$ und $b = t_{end}$  
-> Also lautet die Strecke für den ersten Teil wie folgt: $A_1 = v_0t$  

$A_2$: Da $A_2$ ein Dreieck mit einem rechten Winkel ist, nimmt man die Formel $A = \dfrac{ab}{2}$ und da setzen wir jetzt die jeweiligen Einheiten ein $A_2 = \dfrac{\Delta vt_{end}}{2}$  
Da wir aber eine gleichmäßig beschleunigte Bewegung hier vorliegen haben müssen wir $\Delta v$ wieder mit $at$ ersetzen, denn $ \Delta v = at_{end}$  
Jetzt sieht die Gleichung so aus: $A_2 = \dfrac{t_{end}t_{end}a}{2}$ und zusammengefasst würde da stehen:  
$A_2 = \dfrac{at_{end}^2}{2}$ und da $t_{end}$ sogesagt $t$ ist lautet die Formel: $A_2 = \dfrac{at^2}{2}$  

Und da wir jetzt die beiden Flächen der Teile haben rechnen wir die beiden zusammen, um die Strecke zu bekommen:  
$A_{ges} = A_1 + A_2$ -> $A_{ges} = v_0t + \dfrac{at^2}{2}$ und somit ist $s = v_0t + \dfrac{at^2}{2}$  
Und wenn man jetzt noch eine Anfangsstrecke($s_0$) haben sollte, verbindet man die Anfangsstrecke mit der jetzigen Formel mit einem $+$ und raus kommt:  
$s = v_0t+\dfrac{at^2}{2}+s_0$

* * *

## 6\. Überlagerung von Bewegungen

**Definition:**  
Führt ein Körper gleichzeitig mehrere Teilbewegungen aus, so überlagert sich diese unabhängig voneinander **resultierenden** Gesamtbewegung.

### 6.1 Überlagerung zweier gleichförmiger Bewegungen

#### 6.1.1 gleiche Richtung:

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/ueberlagerung1.jpg){:class="img-responsive"}

Da sich zwei konstante Geschwindigkeiten $v_1$ und $v_2$ in die gleiche Richtung bewegen,  
ist die resultierende Geschwindigkeit $v$ die Summe aus den einzelnen Geschwindigkeiten: $v = v_1 + v_2$

#### 6.1.2 entgegengesetzte Richtung:

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/ueberlagerung2.jpg){:class="img-responsive"}

Da sich zwei konstante Geschwindigkeiten $v_1$ und $v_2$ in die entgegengesetzte Richtung bewegen,  
ist die resultierende Geschwindigkeit $v$ die Differenz aus den einzelnen Geschwindigkeiten: $v = v_1 - v_2$  
**Nicht vergessen! $v$ kann auch negativ sein.**

#### 6.1.3 im rechten Winkel zueinander:

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/ueberlagerung3.jpg){:class="img-responsive"}

Da sich zwei konstante Geschwindigkeiten $v_1$ und $v_2$ in einem rechten Winkel zueinander "bewegen",  
ist die resultierende Geschwindigkeit $v$ die Wurzel aus der Summe der einzelnen quadrierten Geschwindigkeiten:  
$v = \sqrt{v_1^2+v_2^2}$

* * *

### 6.2 Überlagerung von gleichförmiger und gleichmäßig beschleunigter Bewegung

#### 6.2.1 gleiche Richtung (Senkrechter Wurf nach unten):

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/ueberlagerung4.jpg){:class="img-responsive"}

Da sich eine konstante Anfangsgeschwindigkeit $v_0$ und der Freie Fall $v_f = gt$ in die gleiche Richtung bewegen,  
ist die resultiere Geschwindigkeit $v$ die Summe der beiden Geschwindigkeiten: $v = v_0+gt$  

Die Strecke $s$/$y$ berechnet man aus der Summe von der Strecke der Anfangsgeschwindigkeit $s = v_0t$ und  
der Strecke des Freien Falls $s = \dfrac{gt^2}{2}$ --> $s = v_0t+\dfrac{gt^2}{2}$  
Laut Tafelwerk (S. 86) ist es $v = -v_0-gt$ -> kommt aber mit der anderen Formel aufs gleiche hinaus, außer, dass das Ergebnis negativ sein sollte.

#### 6.2.2 entgegengesetzte Richtung (senkrechter Wurf nach oben):

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/ueberlagerung5.jpg){:class="img-responsive"}

Da sich eine konstante Anfangsgeschwindigkeit $v_0$ und der Freie Fall $v_f = gt$ in die entgegengesetzte Richtung bewegen,  
ist die resultiere Geschwindigkeit $v$ die Differenz der beiden Geschwindigkeiten: $v = v_0-gt$  
Die Strecke $s$/$y$ berechnet man aus der Differenz von der Strecke der Anfangsgeschwindigkeit $s = v_0t$ und  
der Strecke des Freien Falls $s = \dfrac{gt^2}{2}$ --> $s = v_0t-\dfrac{gt^2}{2}$  
Bei einem senkrechten Wurf nach oben, gibt es noch die Steigzeit $t_h$, die angibt, wie lange das  
Objekt insgesammt steigt. Dafür nutzt man die Formel: $t_h = \dfrac{v_0}{g}$  
Außerdem gibt es noch die Steighöhe $s_h$, die angibt, wie hoch ein Obejekt steigt, bis es wieder nach unten fällt  
Für die Steighöhe nutzt man diese Formel: $s_h = \dfrac{v_0^2}{2g}$

#### 6.2.3 Im rechten Winkel zueinander (waagerechter Wurf):

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/ueberlagerung6.jpg){:class="img-responsive"}

Da sich eine konstante Anfangsgeschwindigkeit $v_0$ und der freie Fall $v_f = gt$ in einem rechten Winkel  
zueinander "bewegen", so ist die resultierende Geschwindigkeit $v$ die Wurzel aus der Summe der einzelnen  
Geschwindigkeiten zum Quadrat: $ v= \sqrt{v_0^2+g^2t^2}$  

**Wissenswertes:** $v_y = -gt$ -> ist negativ, weil man in einem Koordinatensystem (Siehe Abbildung) ins Negative von der Y-Achse geht.  

Die Geschwindigkeit $v_x$ ist genauso groß wie die Geschwindigkeit $v_0$ -> $v_x = v_0$  

Die Strecke $s_x$ oder $x$ (siehe Schaubild) ist das, um die Strecke bei einer  
gleichförmigen Bewegung auszurechnen: $x = v_0t$  
Um die Strecke in Y-Richtung zu berechnen, muss man einfach die Formel $y = -\dfrac{gt^2}{2}$ nehmen. **(Ergebnis ist negativ!)**

* * *

## 7\. Kräfte und ihre Wirkungen

Die Kraft ist eine Wechselwirkungsgröße. Sie sind nur an den Wirkungen erkennbar:

*   Geschwindigkeitsänderung
*   Formänderung
*   Bahnänderung

**Definition**  
Die Kraft gibt an, wie stark zwei Körper aufeinander einwirken.

*   Formelzeichen: $F$
*   Einheit: $N$ (Newton) => $1\dfrac{kg*m}{s^2} = 1N$

### 7.1 Zusammensetzung von Kräften (TW. S. 85)

Jetzt kommt das gleiche wie bei der Überlagerung von gleichförmigen Bewegungen, bloß jetzt mit Kräften.  

#### 7.1.1 gleiche Richtung:

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/kraft1.jpg){:class="img-responsive"}

Formel hierfür ist folgende: $F = F_1 + F_2$

#### 7.1.2 entgegengesetzte Richtung:

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/kraft2.jpg){:class="img-responsive"}  

Formel hierfür ist folgende: $F = F_1 - F_2$

#### 7.1.3 in einem rechten Winkel zueinander:

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/kraft3.jpg){:class="img-responsive"}

Die Formel dafür lautet: $F = \sqrt{F_1^2+F_2^2}$

### 7.2 Newtonsche Gesetze

#### 7.2.1 Das Trägheitsgesetz (1\. Newtonsches Gesetz)

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/newton1.jpg){:class="img-responsive"}

Ein Körper bleibt in Ruhe oder in gleichförmiger geradliniger Bewegung, solange die Summe der auf ihn  
wirkenden Kräfte null ist. $v = konstant$ & $\Sigma F_{außen} = 0$

#### 7.2.2 Das Newtonsche Grundgesetz (2\. Newtonsches Gesetz)

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/newton2.jpg){:class="img-responsive"}

Zwischen Kraft, Masse und Beschleunigung gilt folgender Zusammenhang: $F = ma$

#### 7.2.3 Das Wechselwirkungsgesetz (3\. Newtonsches Gesetz)

![](https://adrian.mvbuddies.de/bilder/physik10/mechanik/newton3.jpg){:class="img-responsive"}

Wirken 2 Körper aufeinander ein, so wirkt auf jeden der Körper eine Kraft.  
Die Kräfte sind gleich und entgegengesetzt gewichtet: $F_1 = -F_2$

* * *

