# Integralrechnung

Das Gegenstück zur Differentialrechnung ist die Integralrechnung. Das Integral wird mit einem $\int f(x) \, dx$ gekennzeichnet. Das Integral oder auch die Stammfunktion einer Funktion ist diejenige Funktion, deren Ableitung wieder die Funktion ergibt. Da die Ableitung einer Konstanten immer Null ergibt, kann zu jeder Stammfunktion eine beliebige Konstante dazuaddiert werden. Die Stammfunktion wird oft mit einem $F(x) = \int f(x) \, dx$ bezeichnet. 

Beispiel:

$f(x) = x^2$

$F(x) = \int x^2 \, dx = \frac{1}{3} x^3 + C$

|Beispiel einer Funktion | Integral dieser Funktion|
|- | - |
|![drawing](Beispiel_Funktion.png) | ![drawing](Beispiel_Integral.png)|

Das finden von Stammfunktionen ist schwieriger als das Bilden von Ableitungen, da hier nicht für alle Fälle Rechenregeln zur Verfügung stehen. 
Es gibt jedoch einige Ansätze, die beim Finden der Stammfunktion helfen können.

Die wichtigsten sind {download}`hier <Formelsammlung_Physik_1.pdf>` zusammengefasst.

Ein bekanntes Nachschlagewerk ist der [Bronstein](https://link.springer.com/book/10.1007/978-3-8348-2359-5).

Eine besondere Bedeutung hat das bestimmte Integral $\int_a^b f(x) \, dx$. Für dieses gilt

$\int_a^b f(x) \, dx = F(b) - F(a)$.

Es beschreibt die Fläche S, die von der Funktion f(x) eingeschlossen wird. 

```{figure} Integral_as_region_under_curve.svg
---
width: 300px
name: best_int-fig
---
Beispiel für ein Flächenintegral ([von 4C](https://commons.wikimedia.org/w/index.php?curid=1039841))
```