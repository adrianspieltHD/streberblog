---

title: "Trigonometrische Funktionen"

categories:
    - klasse10
    - Mathe

fach:
    - Mathe


toc: true
toc_label: "Inhalt"
toc_sticky: true

---

Ich habe jetzt als Winkel den griechischen Buchstaben **Lambda** ($\lambda$) genommen. Es geht natürlich auch jeder andere Buchstabe.

## Das Bogenmaß

**Das Bogenmaß** ist neben dem sogenannten Gradmaß ein weiteres **Winkelmaß**. Die Maßzahl entspricht der Bogenlänge auf dem Einheitskreis ($r = 1$)

Das Bogenmaß des Winkels $\lambda$ wird mit $arc(\lambda)$ bezeichnet.

**Gleichung:**  
$arc(\lambda) = \dfrac{\pi*\lambda}{180°}$

* * *

## Umrechnungen von Gradmaß in Bogenmaß und umgekehrt

### Vom Gradmaß ins Bogenmaß

Die Formel, um vom Gradmaß ins Bogenmaß zu rechnen, ist wie folgt:

$arc(\lambda) = \dfrac{\pi*\lambda}{180°}$

### Vom Bogenmaß

Die Formel, um vom Gradmaß ins Bogenmaß umzurechnen, ist die vorherige Funktion, nur ein bisschen umgestellt:

$\lambda = \dfrac{arc(\lambda)*180}{\pi}$

* * *

## Die Sinusfunktion

Um sich irgendwie das Bild von der Sinusfunktion machen zu können brauchen wir einen Kreis mit dem Radius von 1\. Außerdem haben wir neben dem Einheitskreis einen Punkt P, der sich auf der Kreislinie des Einheitskreises bewegt. Wenn wir jetzt jeder Winkelgröße $\lambda$ den Y-Wert de Punktes P zuordnet, so erhält man eine Periodische Funktion, welche auch die Sinusfunktion genannt wird. Der Graph dieser Funktion, nennt man auch Sinuskurve.

Hier mal eine grafische Sinusfunktion (mit <a href="https://geogebra.org">GeoGebra</a> erstellt):

![sinus](https://adrian.mvbuddies.de/bilder/mathe10/trifunk/sinus1.PNG){:class="img-responsive"}

### Eigenschaften der Sinusfunktion

Natürlich gehört auch zu jeder Funktion eine Reihe an Eigenschaften, die man abarbeiten muss:

*   **Definitionsbereich:** $x\in\mathbb{R}$
*   **Wertebereich:** $[-1;1]$
*   **Monotonie:**

*   steigend: $-\dfrac{\pi}{2}+2k\pi \leq x \leq \dfrac{\pi}{2}+2k\pi \wedge k \in \mathbb{Z}$

*   fallend: $\dfrac{\pi}{2} + 2k\pi \leq x \leq \dfrac{\pi}{2} + (2k + 1)\pi \wedge k \in \mathbb{Z}$

*   **Länge der Periode:** $2\pi$
*   **Nullstellen:** $k\pi \wedge k \in \mathbb{Z}$

Wegen der Symmetrie und Periodezität gelten:

<table class="table table-hover">
    <thead>
                    <th>Bogenmaß ($k \in \mathbb{Z}$)</th>
                    <th>Gradmaß ($k \in \mathbb{Z}$)</th>
    </thead>
                <tr>
                    <td>$sin(x+k*2\pi) = sin(x)$</td>
                    <td>$sin(x+k*360°) = sin(x)$</td>
                </tr>
                <tr>
                    <td>$sin(\pi-x) = sin(x)$</td>
                    <td>$sin(180°-x) = sin(x)$</td>
                </tr>
                <tr>
                    <td>$sin(-\pi-x) = sin(x)$</td>
                    <td>$sin(-180°-x) = sin(x)$</td>
                </tr>
                <tr>
                    <td>$sin(\pi+x) = -sin(x)$</td>
                    <td>$sin(180°+x) = -sin(x)$</td>
                </tr>
                <tr>
                    <td>$sin(-x) = -sin(x)$</td>
                    <td>$sin(-x) = -sin(x)$</td>
                </tr>
            </table>


**Beispielaufgaben: $[0 ; 2\pi]$**

$sin(x) = 0,9 \quad \| arcsin()$

$x_1 \approx 1,1$

$x_2 = \pi - x_1 = \pi - 1,1 = 2,04$

**Problem 1:** Es kann aber auch mal sein, dass der erste Wert, den man rausbekommt, nicht im Vorgegebenden Intervall liegt dann muss man folgendes machen:

$sin(x) = -0,8 \quad \| arcsin()$

$x = -0,9 \rightarrow entfällt$

$2\pi + x = 2\pi-0,9 = 5,4 = x_1$

$x_2 = \pi - x = \pi + 0,9 = 4,04 $

**Erklärung:**

Man hat als erstes Ergebnis jetzt den wert $x = -0,9$ rausbekommen. Da dieser nicht im Intervall von $0$ und $2\pi$ liegt, dreht man einfach mit diesem Wert nochmal einen Ganzen Kreis und somit $2\pi$. Somit rechnest du ja einfach zu diesen $0,9$ den Vollwinkel $2\pi$ drauf. Damit kommst du auf ein Ergebnis von ca. $5,4$ was dein erstes Ergebnis ist. Und damit du jetzt noch das zweite Ergebnis ausrechnen kannst, musst du dieses ergebnis jetzt nur noch auf $\pi$ raufrechnen um den für den $x_1$ gegenüberliegenden Winkel rauszufinden.

**Problem 2:** Es kann aber auch mal sein, dass es eine Aufgabe wie z.B. $sin(x) = 2$ gibt. Dort musst du denn einfach nur hinschreiben, dass diese Funktion nicht definiert ist

**Problem 3:** Natürlich kann es auch sein dass du die Aufgabe $sin(x) = -0,3$ hast und das Intervall wie folgt aussieht: $[0;\pi]$. Wenn dann das erste Ergebnis negativ ist, kannst du ruhig aufhören zu rechnen, da die Sinuskurve niemals in den negativen Bereich gehen wird.

### Die Bedeutung der Parameter der Sinusfunktion

**Allgemeine Sinusfunkion:** $f(x) = a\*sin(b\*(x+c))+d$

<table class="table table-hover">
                <thead>
                    <th>Gleichung</th>
                    <th>Einfluss auf den Graphen</th>
                </thead>
                <tr>
                    <td>$f(x) = a*sin(x)$</td>
                    <td>$a=]1;\infty]$ : gestreckt in y-Richtung<br>
                        $a=]0;1[$ : gestaucht in y-Richtung <br>
                        $a=[-\infty;0[$ : zusätzlich an der x-Achse gespiegelt
                    </td>
                </tr>
                <tr >
                    <td>$f(x) = sin(bx)$</td>
                    <td>$b=]0;1[$ : gestreckt in x-Richtung <br>
                        $b=]1;\infty]$ : gestaucht in x-Richtung</td>
                </tr>
                <tr >
                    <td>$f(x) = sin(x+c)$</td>
                    <td>$c=[-\infty;0[$ : Verschiebung nach rechts entlang der x-Achse <br>
                        $c=]0;\infty]$ : Verschiebung nach links entlang der x-Achse</td>
                </tr>
                <tr>
                    <td>$f(x) = sin(x)+d$</td>
                    <td>$d=]0;\infty]$ : Verschiebung nach oben entlang der y-Achse <br>
                        $d=[-\infty;0[$ : Verschiebung nach unten entlang der y-Achse</td>
                </tr>
            </table>

Da wir jetzt die allgemeine Form kennengelernt haben gelten natürlich auch ein paar andere Eigenschaften um etwas zu berechnen etc. (gilt nur für $f(x) = asin(b(x+c))$)

*   **Definitionsbereich :** $x \in \mathbb{R}$
*   **Wertebereich** : $[-a;a]$
*   **Nullstellen** : $x_k = \dfrac{k\pi - c}{b} \wedge k \in \mathbb{Z}$
*   **Periode** : $\dfrac{2\pi}{\|b\|}$

Bei der Funktion mit dem Parameter $d$ muss man ist der **Wertebereich** $[-a+d;a+d]$ und die **Nullstellen** lassen sich wie gewohnt ausrechnen, indem man $f(x) = 0$ setzt.

* * *

## Kosinus und Tangensfunktion

### Eigenschaften der Kosinusfunktion

*   **Definitionsbereich** : $x\in\mathbb{R}$
*   **Wertebereich** : $[-1;1]$
*   **Nullstellen** : $(2k+1)\dfrac{\pi}{2} \wedge k \in \mathbb{Z}$
*   **Periode** : $2\pi$

Hier mal eine grafische Kosinusfunktion (mit <a href="https://geogebra.org">GeoGebra</a> erstellt):

![Kosinus](https://adrian.mvbuddies.de/bilder/mathe10/trifunk/kosinus.PNG){:class="img-responsive"}

### Eigenschaften Tangensfunktion

*   **Definitionsbereich** : $x \in \mathbb{R} \quad\wedge\quad x \neq (2k + 1)\dfrac{\pi}{2} \wedge$ $k \in \mathbb{Z}$
*   **Wertebereich** : $y \in \mathbb{R}$
*   **Nullstellen** : $k\pi \wedge k \in \mathbb{Z}$
*   **Periode** : $\pi$

Hier mal eine grafische Tangensfunktion (mit <a href="https://geogebra.org">GeoGebra</a> erstellt):

![Tangens](https://adrian.mvbuddies.de/bilder/mathe10/trifunk/tangens.PNG){:class="img-responsive"}