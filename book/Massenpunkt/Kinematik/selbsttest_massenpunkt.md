# Selbsttest Kinematik

Um das Verständnis zu Fragen der Kinematik zu prüfen sind hier einige Fragen vorbereitet. Die Antwort kann durch Klicken sichtbar gemacht werden

```{admonition} Welche beiden Größen werden in der Kinematik bei der 1-dimensionalen Bewegung durch einen funktionalen Zusammenhang beschrieben?
:class: tip, dropdown
Zeit und Ort (x=x(t))
```

```{admonition} Ein Ball wird senkrecht nach oben geworfen und fällt anschließend wieder runter. Welche Funktion beschreibt die auf den Ball wirkende Beschleunigung?
:class: tip, dropdown
Die Beschleunigung ist die ganze Zeit eine Konstante, nämlich g.
```

```{admonition} Unter welcher Bedingung können bei der zweidimensionalen Bewegung x- und y-Koordinate unabhängig voneinander betrachtet werden?
:class: tip, dropdown
Wenn die Bewegung frei ist und es keine zusätzlichen Bedingungen gibt.
```

```{admonition} Wie hängen Ort $\vec{r}$ und Geschwindigkeit $\vec{v}$ zusammen?
:class: tip, dropdown
$ \vec{v} = \frac{d}{dt} \vec{r}$
```

```{admonition} Wie hängen Geschwindigkeit $\vec{v}$ und Beschleunigung $\vec{a}$ zusammen?
:class: tip, dropdown
$ \vec{a} = \frac{d}{dt} \vec{v}$
```

```{admonition} Unter welcher Bedingung gilt $v = \frac{s}{t}$?
:class: tip, dropdown
Wenn $a = 0$ (gleichförmige Bewegung), mit $s = x - x_0$
```

```{admonition} Wie ergeben sich die Konstanten $v_0$ und $x_0$ im Zusammenhang $x(t) = \frac{1}{2}\cdot a \cdot t^2 + v_0 \cdot t + x_0$?
:class: tip, dropdown
Durch die Anfangsbedingungen der Bewegung.
```

```{admonition} In welche Richtung zeigt die Beschleunigung $\vec{a}$?
:class: tip, dropdown
In Richtung der Änderung der Geschwindigkeit
```

```{admonition} Welche Wurfbewegung ergibt sich aus dem schiefen Wurf, wenn $v_{x,0} = v_{y,0} =0$?
:class: tip, dropdown
Der freie Fall
```

## Aufgabe

Gegeben sei die Ortskurve 
$\vec{r}(t) = t \cdot \left(\begin{array}{c} \sin(t) \\ \cos(t) \\ 1 \end{array}\right) + \vec{b}$ mit einem konstanten Vektor $\vec{b}$.

Berechnen Sie die Geschwindigkeit und die Beschleunigung.

```{admonition} Lösung
:class: tip, dropdown
Mit der Produktregel ergibt sich

$\vec{v}(t) = \dot{\vec{r}}(t) = \left(\begin{array}{c} \sin(t) + t \cos(t) \\ \cos(t) - t \sin(t) \\ 1 \end{array}\right)$

$\vec{a}(t) = \dot{\vec{v}}(t) = \left(\begin{array}{c} 2 \cos(t) - t \sin(t) \\ -2 \sin(t) - t \cos(t) \\ 0 \end{array}\right)$

Der konstante Vektor $\vec{b}$ fällt beim Ableiten weg.
```
