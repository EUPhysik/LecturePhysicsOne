# Erde

## Gravitationskräfte auf der Erde

Die Erde ist ein oft verwendetes Bezugssystem, da wir auf ihr leben und viele Bewegungen aus der Perspektive eines Bezugssystems auf der Erdoberfläche betrachten.
Für Bewegungen in der Nähe der Erdoberfläche wurde 

$\vec{F} = m \cdot \vec{g}$ 

verwendet. Allgemein ist der Zusammenhang komplexer.

Zwischen Massen wirkt generelle eine anziehende Kraft, die Gravitationskraft. 
Die Gravitationskraft zwischen zwei (punktförmigen) Massen wird nach Newton beschrieben durch 

$F_G = - G \cdot\frac{m_1 \cdot m_2}{r^2} $

wobei $G$ die universelle Gravitationskonstante ist. Es gilt $G = 6.674 \cdot 10^{-11} \frac{N m^3}{kg^2}$.
Die Kraft wirkt entlang des Verbindungsvektors $\vec{r}$ entlang der Verbindungslinie der Massen.

```{figure} gravitation.svg
---
width: 900px
name: gravitation-1
---
Anziehung zwischen zwei Massen. 
 ```

 Betrachtet man nun $m_1 = M_E$ als Masse der Erde und $m_2 = m$ als eine Masse in der Nähe der Erdoberfläche, so ist die Gravitationskraft der Masse $M_E$ auf die Masse $m$

 $F_G = - G \cdot\frac{M_E \cdot m}{R_E^2} $

 wobei $R_E$ der Erdradius mit $R_E = 6371 km$ und $M_E$ die Masse der Erde mit $M_E = 5.9722 \cdot 10^{24} \,kg $.

 Setze man nun

$F = F_G $

$\Leftrightarrow m \cdot a \stackrel{!}{= } m \cdot g = - G \cdot\frac{M_E \cdot m}{R_E^2} $

$\Leftrightarrow g = - G \cdot\frac{M_E }{R_E^2} = 6.674 \cdot 10^{-11} \frac{N m^3}{kg^2} \frac{5.9722 \cdot 10^{24} \,kg }{\left( 6371 km \right)^2} = 9.82 \, \frac{m}{s^2}$

Dieser Wert ist allerdings nur an der Erdoberfläche gültig. 
In Deutschland verwendet man im Mittel für Bewegungen in Oberflächennähe

$g = 9.81 \, \frac{m}{s^2}$.

Für Bewegungen, die in größerer Entfernung zur Erdoberfläche stattfinden, ist dieser Wert nicht mehr gültig und muss für den entsprechenden Abstand der Massen neu mit Hilfe des Gravitationsgesetzes berechnet werden. Solange die Massen getrennt sind, können die Massen bezüglich ihres Schwerpunktes als Punktmassen betrachtet werden.

## Scheinkräfte auf der Erde

Da die Erde sich einmal pro Tag um ihre eigene Achse dreht, befinden wir uns auf der Erde in einem rotierenden Bezugssystem. Dieses rotiert mit konstanter Winkelgeschwindigkeit. Das für dazu, dass auf der Erde Scheinkräfte wie die Zentrifugalkraft und die Corioliskraft auftreten (siehe Kapitel [](../../Scheinkraefte/scheinkraefte_rot.md)).

Lokal und für geringe Massen sind diese Kräfte jedoch so klein, dass wir sie nicht wahrnehmen. Bei der Betrachtung von größeren Massen, sind sie jedoch deutlich spürbar. So sorgt beispielsweise die Corioliskraft für die Entstehung der globalen Winde und ist auch an der Entstehung von großräumigen ozeanischen Strömungen beteiligt. 