# Starre Körper

**Definition Starrer Körper** 

Ein starrer Körper ist eine Modelvorstellung eines festen Gegenstandes, mit dessen Hilfe Bewegungen von ausgedehnten Körpern (im Gegensatz zu Massenpunkten) berechnet werden können. Ein starrer Körper ist ein System aus beliebig vielen einzelnen Massenpunkten, die in konstantem Abstand zueinander stehen. Auch unter dem Einfluss äußerer Kräfte ändert der starre Körper seine Form nicht. 

```{figure} Bilder/starrerkoerper.svg
---
width: 300px
name: starrerkoerper-1
---
Modell eines starren Körpers.
 ```

## Model

Ein starrer Körper kann durch die Position des Schwerpunktes und der Massenverteilung bezüglich dieses Schwerpunktes beschrieben werden. 

```{figure} Bilder/starrerkoerper2.svg
---
width: 300px
name: starrerkoerper-2
---
Modell eines starren Körpers bzgl. eines Koordinatensystems. 
 ```


### Massenverteilung

Die Positionen der einzelnen Massenelemente $m_i$ wird bezüglich eines gewählten Koordinatensystem durch den Vektor $\vec{r}_i$ beschrieben (siehe beispielsweise der der rote Pfeil in {numref}`Abbildung %s <starrerkoerper-2>`). Damit gibt es pro Massenelement einen dazugehörenden Ortsvektor.

Beim Übergang zu einem kontinuierlichen System wird

$m_i \rightarrow dm$

### Schwerpunkt

Als Schwerpunkt wird der Massenmittelpunkt des starren Körpers verstanden. 
Bei diskreten Systemen wird der Schwerpunkt bestimmt durch 

$\vec{r}_S = \frac{1}{M}\sum_i m_i \vec{r}_i$  mit $M = \sum_i m_i$

Beim Übergang zu einem kontinuierlichen System wird $\sum \rightarrow \int$ und

$\vec{r}_S = \frac{1}{M} \int \vec{r} \, dm = \frac{1}{M} \int \vec{r} \rho(r)\, dV $ mit $M = \int \, dm$


### Bewegungen 

Die möglichen Bewegungen eines starren Körpers sind

1. **Translationsbewegung** Der starre Körper bewegt sich in eine Richtung ohne Drehbewegung. Die Bewegung kann vollständig durch die Bewegung des Schwerpunktes beschrieben Werden, da der Abstand jedes Massenpunktes zum Schwerpunkt konstant ist. 
1. **Rotationsbewegung** Der starre Körper dreht sich um eine feste Drehachse. Dies bedeutet, dass der Abstand der einzelnen Massenelemente zur Drehachse konstant ist. Die Bewegung kann nicht über die Bewegung des Schwerpunktes beschrieben werden. 

```{figure} Bilder/trans_vs_rot.svg
---
width: 700px
name: trans_vs_rot-1
---
Mögliche Bewegung eines starren Körpers.  
 ```
