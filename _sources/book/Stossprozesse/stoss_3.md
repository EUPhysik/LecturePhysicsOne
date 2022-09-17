# Schiefer zentraler elastischer Stoß

```{figure} Bilder/stoss-7.svg
---
width: 700px
name: stoss-7
---
Schiefer zentraler elastischer Stoß
 ```

Beim schiefen zentraler elastischer Stoß kann das Problem nicht auf eine Dimension reduziert werden, es handelt sich um ein 2-dimensionales Problem.

Folgende Annahmen können gemacht werden:

* Keine Reibung, x und y Komponenten können unabhängig voneinander betrachtet werden
* Die Komponenten der Impulse in $x$- Richtung sind vor und nach dem Stoß gleich:
$m_1 v_{1x} = m_1 v_{1x}^\prime$ 
und 
$m_2 v_{2x} = m_2 v_{2x}^\prime$
* In $y$-Richtung gilt die Impulserhaltung
$m_1 v_{1y} + m_2 v_{2y} = m_1 v_{1y}^\prime + m_2 v_{2y}^\prime $
* und Energieerhaltung
$\frac{m_1}{2} \left(v_{1x}^2 + v_{1y}^2\right)+ \frac{m_2}{2} \left(v_{2x}^2 + v_{2y}^2\right)= \frac{m_1}{2} \left(v_{1x}^{\prime 2} + v_{1y}^{\prime 2} \right)+ \frac{m_2}{2} \left(v_{2x}^{\prime 2} + v_{2y}^{\prime 2} \right)$

Aus diesen Annahmen ergeben sich folgende Zusammmenhänge:

||Vor dem Stoß|Nach dem Stoß|
|-|-|-|
|Masse 1| $v_{1x}$ | $v_{1x}^\prime = v_{1x}$|
||$v_{1y}$|$v_{1y}^\prime = \frac{(m_2 - m_1)v_{1y} + 2 m_2 v_{2y}}{m_1 + m_2}$|
|Masse 2| $v_{2x}$| $v_{2x}^\prime = v_{2x}$|
||$v_{2y}$|$v_{2y}^\prime = \frac{2 m_1 v_{1y} + (m_2 - m_1)v_{2y} }{m_1 + m_2}$|