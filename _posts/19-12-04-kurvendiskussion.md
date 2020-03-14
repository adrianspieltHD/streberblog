---

title: "Kurvendiskussion"

categories:
    - klasse11
    - Mathematik

fach:
    - Mathematik

toc: true
toc_label: "Inhalt"
toc_sticky: true
---

# 1. Der Definitionsbereich

Der Definitionsbereich einer Funktion gibt an, welche x-Werte einer Menge auf eine Zielmenge abgebildet werden können. (Ich weiß nicht, ob man das so richtig formulieren kann)

Bei **ganzrationalen Funktionen** ist dies immer $x \in \mathbb{R}$

Bei Funktionen mit einem Bruch wie zum Beispiel $f(x) = \dfrac{x^2+4}{x-2}$ ist es allerdings nicht gleich $x \in \mathbb{R}$ da bei der 2 im Nenner des Bruches eine 0 stehen würde und durch 0 darf man ja nicht teilen, wenn man ein bisschen in der Schule aufpasst.

Deswegen sieht das ganze jetzt für den Definitionsbereich so aus: $x \in \mathbb{R},x≠2$

---
# 2. Der Wertebereich

Der Wertebereich einer Funktion gibt an, welche y-Werte die Funktion annehmen kann.

Bei $f(x) = x^3$ ist es zum Beispiel $y \in \mathbb{R}$

Bei $f(x) = x^2$ ist es aber $y \in \mathbb{R}, y \geq 0$

---
# 3. Die Symmetrie

Es gibt zwei Arten von Symmetrien zu untersuchen:

## 3.1 Achsensymmetrie

Wenn man von der Funktion $f(x)$ jetzt $f(-x)$ bildet und dort dann wieder die Ursprungsfunktion $f(x)$ rauskommt, dann haben wir eine Achsensymmetrie an der Stellen $x=0$ (y-Achse) vorliegen.

## 3.2 Punktsymmetrie

Wenn man von der Funktion $f(x)$ jetzt $f(-x)$ und dort jetzt die Ursprungsfunktion nur mit dem jeweils anderen Vorzeichen $-f(x)$ rauskommt, dann ist es eine Punktsymmetrie am Punkt $O(0/0)$

---
# 4. Nullstellen und Schnittpunkt mit der X-Achse

Nullstellen berechnet man, indem man immer als erstes die Funktion gleich 0 setzt ($f(x) = 0$). Danach gibt es verschiedene Lösungsverfahren und Arten von Funktionen, welche man nehmen oder vorfinden kann.

## 4.1 ganzrationale Funktion

Bei einer Ganzrationalen Funktion können wir verschiedene Wege gehen, um auf ein Ergebniss zu kommen.

zum einen wäre dort:

1. Polynomdivision
2. Ausklammern eines/mehrerer x (wenn kein absolutes Glied vorhanden ist)
3. Substitution (biquadratische Funktionen ($f(x) = ax^4+bx^2+c$))
4. Bei quadr. Funktionen: abc- oder pq-Formel

## 4.2 Wurzelfunktionen (Potenzfunktion mit gebrochenem Exponenten)

Was man sich bei den Wurzelfunktionen eigentlich nur merken muss ist, dass die Umkehrung von einer $\sqrt{a}$ das $a²$ (a -> irgendeine Zahl) ist.

Mit dem Quadrieren wird die Wurzel in dem Term aufgehoben.

Aber Achtung!:

Es könnten die binomischen Formeln vertreten. Deswegen schön auswendig lernen oder diese im Tafelwerk nachschlagen.

**Die Ergebnisse nach dem Ausrechnen nochmal zu einer Probe in die Ausgangsgleichung einsetzen, wenn 0 rauskommt -> Nullstelle**

## 4.3 Exponentialfunktionen

Um eine Exponentialfunktion aufzuheben benötigen wir den sogenannten Logarithmus. Der Logarithmus, welcher verwendet werden muss, sagt uns die Basis, welcher das x im Exponenten hat. Hier mal ein Beispiel: (Das X ist nur ein Platzhalter)

$10^x -> log_{10}(x)$

Also um die Basis 10 bei der Exponentialfunktion loszuwerden, musst du den Logarithmus zur Basis 10 nehmen, damit das x dann alleine steht.

Eine kleine Sache noch:

$a^x \quad a \in \mathbb{R}, a≠0 ​$ --> es gibt keine Nullstellen

## 4.4 Logarithmusfunktionen

Wenn wir gerade schon von Logarithmus geredet haben, kommen wir jetzt dazu. Um den Logarithmus aufzuheben, müssen wir eine den Logarithmus als Exponent zur Basis nehmen, welcher der Logarithmus hat. Hier ein Beispiel: (Das X ist nur ein Platzhalter)

$log_{10}(x) --> 10^x$

Zudem gilt:

$log_a(x) \quad a \in \mathbb{R}, a > 0$ --> Nullstelle bei $x = 1$

## 4.5 Trigonometrische Funktionen

Zu den Trigonometrischen Funktionen habe ich schon mal eine kleine (Zusammenfassung)[] erstellt. Hier geht es jetzt nur darum, wie man die Substitution bei einer Aufgabe macht.

Beispiel $[-\pi;2\pi]$:

$f(x) = 3sin(x+1)+2$

--> bis $sin(x+1)$ umstellen 

$-\dfrac{1}{3} = sin(x+1)$

-> x+1 durch z.B. z ersetzen

$-\dfrac{1}{3} = sin(z)$

alle z-Werte für das Intervall ausrechnen

- $z_1 = -0.34$
- $z_2 = -2.8$
- $z_3 = 3.48$
- $z_4 = 5.94$

Rücksubstitution von z:

$z_n = x_n + 1$

- $x_1 = -0.34 - 1 = -1.34$
- $x_2 = -2.8 - 1 = -3.8$ --> entfällt, da außerhalb des Bereiches
- $x_3 = 3.48 - 1 = 2.48$
- $x_4 = 5.94 - 1 = 4.94$

## 4.6 Schnittpunkt angeben

Den Schnittpunkt mit der X-Achse gibt man wie folgt an --> $S_{x_n}(x_n / 0)$

---
# 5. Schnittpunkt mit der y-Achse

Dort braucht man einfach nur für die x-Werte die Zahl 0 einsetzen und dann kommt man auf folgenden Schnittpunkt: $S_y(0/f(0))$

---
# 6. Das Verhalten von Funktionen im Unendlichen

Um das Verhalten im Unendlichen zu überprüfen, brauchen wir den Limes. Bei ganzrationalen Funktionen muss man immer nach der höchsten Potenz gucken, da diese am schnellsten im Unendlichen ansteigt.

Bei Brüchen ist das ein bisschen anders.

Dort muss man die **höchste Potenz im Nenner ausklammern**, um so viele Nullfolgen (Funktionen, die im Unendlichen gegen 0 gehen) zu kriegen. Ein Beispiel:

$f(x) = \dfrac{x^2+4x+5}{x^3+4}$

$\lim\limits_{x \rightarrow \pm\infty} (\dfrac{x^3+4x+5}{x^2+4})$

$ \lim\limits_{x \rightarrow \pm\infty} (\dfrac{x^3(\dfrac{1}{x}+\dfrac{4}{x^2}+\dfrac{5}{x^3})}{x^3(1+\dfrac{4}{x})}) = \dfrac{0}{1} = 0$

Und natürlich kann man auch eine Exponentialfunktion ausklammern, falls diese vorhanden sein sollte und dies die größe "Potenz" im Nenner ist.

---
# 7. Funktion auf Polstelle untersuchen

Eine Polstelle ist dann vorhanden, wenn bei $\dfrac{u(x)}{v(x)}$ --> $u(x) ≠ 0$ und $v(x) = 0$. Wenn dies erfüllt ist, ist bei $x_0$ eine Polstelle. ($x_p$)

---
# 8. Asymptoten

Es gibt 3 verschiedene Asymptoten:

## 8.1 waagerechte Asymptote

Diese kann man schon aus der davor gemachten Grenzwertbetrachtung ablesen. Eine waagerechte Asymptote ist auch dann vorhanden, wenn der Zählergrad (ZG) kleiner oder gleich dem Nennergrad (NG) ist

## 8.2 senkrechte Asymptote

Eine senkrechte Asymptote bekommt man nur, wenn man eine Polstelle zu der jeweiligen Funktion gefunden hat.

## 8.3 schräge Asymptote

Die schräge Asymptote entsteht dann, wenn der ZG größer als der NG wird. Falls man die schräge Asymptote berechnen möchte, kann man dies Tun, in dem man den Zähler durch den Nenner mit Polynomdivision Teilt. Die ganzrationale Funktion, welche rauskommt (vor dem Rest) ist dann die schräge Asymptote.

---

# 9. Ableitungen

Um die nächsten Punkte zu verstehen und anwenden zu können, braucht man die sogenannte Ableitung. Hierfür gibt es einige Regeln, die man können sollte.

## 9.1 Potenzregel

Die Allgemeine Ableitung, die man bei z.B. ganzrationalen Funktionen machen muss, geht folgendermaßen:

$x^n \rightarrow nx^{n-1}$
Ein Beispiel dazu wäre folgendes:

$x^3 \rightarrow 3x^2 \rightarrow 6x \rightarrow 6 \rightarrow 0$

## 9.2 Summenregel

Die Summenregel sagt, dass man bei einer Summe/Differenz von jedem einzelnen Summanden die Ableitung bilden muss:

$v(x) + u(x) \rightarrow v'(x) + u'(x)​$

Noch ein Beispiel:

$x^3 + 2x^2 \rightarrow 3x^2 + 4x \rightarrow 6x+4 \rightarrow 6 \rightarrow 0$



## 9.3 Produktregel

Die Produktregel geht folgendermaßen ($v$ und $u$ sind dabei Teilfunktionen. Sieht man nachher auch am Beispiel) :

$u*v \rightarrow u'v+uv'$

Ein Beispiel:

$x²*7x³ \rightarrow 2x(7x³)+x²(21x²) => 14x^4+21x^4 => 35x^4$

Man hätte in diesem Beispiel jetzt natürlich auch einfach die beiden Produkte zusammenmultiplizieren können und dann die Ableitung bilden können. Aber ich wollte dir mal damit ein sehr simples Beispiel geben.

## 9.4 Kettenregel (Nur LK)

Bei der Kettenregel kommt zu dem ganzen Ableiten noch bspw. eine Klammer hinzu. Und dann würde es allgemein so etwas ergeben:

$u[v(x)] \rightarrow u'[v(x)]*v'$

Ein geeignetes Beispiel wäre das hier:

$(3x+4)^3 \rightarrow 3(3x+4)^2 * 3 => 9(3x+4)^2$

## 9.5 Quotientenregel (optional)

Wenn ihr eine Funktion habt, wo zwei "Teilfunktionen" in einem Bruch darstehen, kann man neben der Produktregel (Umformungen) auch die Quotientenregel verwenden. Die sieht allgemein so aus:

$\dfrac{u}{v} \rightarrow \dfrac{u'v-uv'}{v^2}$

Ein kleines Beispiel dazu wäre:

$\dfrac{x^2+2}{2x+1}$

$\rightarrow \dfrac{2x(2x+1) - (x^2+2)2}{(2x+1)^2}​$

$\rightarrow \dfrac{4x^2+2x-(2x^2+4)}{(2x+1)^2}$

$\rightarrow \dfrac{4x^2+2x-2x^2-4}{(2x+1)^2} \rightarrow \dfrac{2x^2+2x-4}{(2x+1)^2}$



## 9.6 Die Ableitung spezieller Funktionen

$e^x \rightarrow e^x$

$ln(x) \rightarrow \dfrac{1}{x}$

$sin(x) \rightarrow cos(x)​$

$cos(x) -> -sin(x)$

---

# 10. Extrempunkte berechnen

Für die Extrempunktberechnung braucht man die erste aber auch die zweite Ableitung der Funktion. 

Die Bedingung, damit es ein Extrempunkt (Hoch- oder Tiefpunkt) ist lautet so:

$f'(x) = 0$

und

$f''(x) > 0 $ --> Tiefpunkt

$f''(x) < 0$ --> Hochpunkt

Falls die zweite Ableitung 0 sein sollte, muss man in der ersten Ableitung überprüfen, ob an dieser Stelle ein Vorzeichenwechsel vorliegt. Wenn ja ist es ein Extrempunkt. Wenn allerdings nicht, könnte es auf etwas anderes hinweisen.

Und nachdem man die x-Werte raushat, diese in die Ursprungsfunktion einsetzen, um den y-Wert rauszubekommen

---

# 11. Wendepunkte berechnen

Wendepunkte berechnet man mit der zweiten und dritten Ableitung. Man kann auch sagen, dass Wendestellen die Extremstellen der ersten Ableitung sind. Daraus kann man folgendes schließen:

$f''(x) = 0$

und 

$f'''(x) \ne 0$

Auch hier wieder: Wenn bei der 3. Ableitung 0 rauskommt, dann überprüfen, ob bei der 2. Ableitung an dieser Stelle ein Vorzeichenwechsel vorliegt. Wenn ja dann ist es ein Wendepunkt. Wenn nicht dann nicht. 

Es gibt aber zudem auch besondere Wendepunkte. Diese haben eine waagerechte Tangente und somit den Anstieg 0. Diese nennt man **Sattelpunkte**

Um ein Sattelpunkt vorliegen zu haben muss folgendes erfüllt sein:

$f'(x) = 0$

$f''(x) = 0$

und 

$f'''(x) \ne 0$

---

# 12. Krümmungsänderung an Wendepunkten bestimmen

Mit der Krümmungsänderung an Wendepunkten gibt man an, ob es ein Rechts-Links- (RL-WP) oder ein Links-Rechts-Wendepunkt (LR-WP) ist.

Man hat bei folgenden Werten den entsprechenden Wendepunkt vorliegen:

$f'''(x) < 0$ --> LR-WP

$f'''(x) > 0$ --> RL-WP

