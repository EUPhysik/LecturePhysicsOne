# Grenzen des einfachen Modells

Bislang wurden reibungsfreie und laminare Strömungen betrachtet. In Realität treten jedoch Phänomene wie Reibung und Turbulenz auf. 
Im folgenden werden diese Inhalte soweit bearbeitet, wie es notwendig ist, um zu verstehen, in welchen Grenzen das einfach Modell der laminaren Strömung gilt und welche Effekte darüber hinaus auftretende Phänomene wie Reibung und Turbulenz haben.

## Viskosität

Bei realen Strömungen muss der Reibungswiderstand berücksichtigt werden.
Die Reibung setzt sich zusammen aus 
* der Wechselwirkung des Fluids mit der Wand
* der Zähigkeit (Viskosität) des Fluids

Die Viskosität bezeichnet die Zähigkeit, von Fluiden, sie wirkt also der Bewegung entgegen. Je höher die Viskosität ist, desto dickflüssiger ist das Fluid. Ein Beispiel für ein Fluid mit hoher Viskosität ist Honig.

```{figure} Videos/Viscosities.gif
---
width: 80%
alt: Viskosität
name: Viskosität-1
---
[Von Synapticrelay](https://commons.wikimedia.org/w/index.php?curid=50627718)
 ```



Um zu verstehen, was dies beispielsweise für eine Rohrströmung bedeutet, teilt man das Fluid in infinitesimale Schichten auf ({numref}`siehe Abbildung %s <reibung-1>`). 

```{figure} Bilder/reibung.svg
---
width: 80%
alt: Reibung
name: reibung-1
---
Infinitesimale Schichten in einer Rohrströmung
 ```
Die dynamische Viskosität ist definiert als $F = \eta \cdot A \frac{\Delta v}{\Delta y}$ 
Da es sich immer noch um eine lamiare Strömung handelt, bedeutet dies, dass $\perp$ zu Strömunggeschwingungkeit ein Impulsaustausch, aber kein Massenaustausch stattfindet, d.h. es findet keine Durchmischung der einzelnen Schichten statt.

Dies bedeutet folgendes für eine Rohrströmung:
* die Reibung zwischen den Wänden und der ersten Fluidschicht sorgt dafür, dass diese Fluischicht abgebremst wird
* die Reibung zwischen der ersten und zweiten Fluidschicht sorgt dafür, dass versetzt zur ersten Fluidschicht die zweite Fluidschicht abgebremst wird
* die Reibung zwischen der zweiten und dritten Fluidschicht sorgt dafür, dass versetzt zur zweiten Fluidschicht die dritte Fluidschicht abgebremst wird
* ...
* Es bildet sich somit ein Profil aus, bei dem die an den Rand liegenden Schichten hinter den weiter in der Mitte liegenden Schichten hinterherlaufen.

Die Form dieses Profils lässt sich über eine Kräftebilanz bestimmen. 
Zum einen wirken Druckkräfte, die das Fluid durch die Rohrleitung drücken. Diese sind gegeben durch 
$F_D = A \cdot \Delta p = r^2 \cdot \pi \cdot \left( p_2 - p_1 \right)$ 

Die Reibungskräfte wirken der Bewegung entgegen. Sie sind gegeben durch
$F_R = U\cdot l \left( - \eta \frac{du}{dr}\right) = 2 \cdot \pi \cdot r \cdot l \left( - \eta \frac{du}{dr}\right)$, wobei der Term $- \eta \frac{du}{dr}$ den Impulsübertrag in radiale Richtung beschreibt. 

Hierbei ist in der Mitte der Rohrleitung $r=0$ und am Rand $r=R$ und $u(R) = 0$.

Die daraus resultierende Differentialgleichung hat (bei konstanter Druckkraft) die Lösung $u (r) = \frac{\Delta p}{4 \cdot \eta \cdot l} \left(R^2 - r^2 \right)$

Die maximale Geschwindigkeit ist bei $r = 0$: $u_{max} = \frac{\Delta p \cdot R^2}{4 \cdot \eta \cdot l}$

Und die mittlere Geschwindigkeit $\bar{u} = \frac{u_{max}}{2}$

Dies ist auch bekannt als das Gesetz von Hagen-Poseuille. 

```{figure} Bilder/laminar2.svg
---
width: 80%
alt: Laminare Rohrströmung
name: reibung-2
---
Laminare Rohrströmung mit Geschwindigkeitsprofil
 ```

## Turbulenz

Bislang wurden laminare Strômungen betrachtet. Kennzeichnend hierfür war, das $\perp$ zu Strömunggeschwingungkeit ein Impulsaustausch, aber kein Massenaustausch stattfindet. Ab einer bestimmten Strömungsgeschwindigkeit ist das nicht mehr der Fall, sondern es kommt zu Verwirbelungen. Dies wird auch als Turbulenz bezeichnet. 

```{figure} Bilder/False_color_image_of_the_far_field_of_a_submerged_turbulent_jet.jpg
---
width: 60%
alt: Turbulenz
name: turbulenz-1
---
Turbulenz [Von C. Fukushima and J. Westerweel, Technical University of Delft](https://commons.wikimedia.org/w/index.php?curid=3082535)
 ```

1883 machte Reynolds grundlegende Expermiente zur Turbulenz und lieferte wichtige theoretische Grundlagen. Er lies einen starken Farbstoff durch eine Fluidströmung mitlaufen und analysierte die dadurch sichtbar gemachten Schichten. Dennoch sind viele Aspekte der Turbulenz auch heute noch ein aktives Forschungsfeld.

```{figure} https://upload.wikimedia.org/wikipedia/commons/f/f3/Reynolds_fluid_turbulence_experiment_1883.jpg
---
width: 60%
alt: Reynolds Experiment
name: reynolds-1
---
Experiment von Reynolds zur Turbulenz [Von Svebert](https://commons.wikimedia.org/w/index.php?curid=39278179)
 ```

Auch wenn das Phänomen der Turbulenz ein Kompliziertes ist, kann relativ einfach eine Grenzgeschwindigkeit bestimmt werden, ab der Turbulenz auftritt. So kann abgeschätzt werden, ob in einer bestimmten Strömung Turbulenzeffekte berücksichtigt werden müssen. 

Die Größe, die angibt, ob eine Strömung laminar oder turbulent ist die Reynoldszahl  

$Re = \frac{\text{Trägheitskräfte}}{\text{Reibungskräfte}} = \frac{\rho \cdot v \cdot d}{\eta} = \frac{v \cdot d}{\nu}$

mit

$\rho =$ Dichte

$v = $ Strömungsgeschwindigkeit

$\eta = \nu \cdot \rho$ mit 

$\eta = $  dynamische Viskosität

$\nu = $ kinematische Viskosität



Turbulenz führt zu Massenaustausch zwischen den einzelnen Schichten. Dies hat zur Folge, dass 
 erhöhte Reibungsverluste auftregen, sodass das in {numref}`Abbildung %s <reibung-2>` abgeflacht wird ({numref}`siehe Abbildung %s <reynolds-2>`).

```{figure} https://upload.wikimedia.org/wikipedia/commons/6/61/Flow-profile-roughness.svg
---
width: 40%
alt: Verbreiterung des Geschwindigkeitsprofils durch Turbulenz
name: reynolds-2
---
Verbreiterung des Geschwindigkeitsprofils durch Turbulenz [Von Svebert](https://commons.wikimedia.org/w/index.php?curid=39278179)
 ```

Bei Rohrströmungen werden als charakteristische Größen üblicherweise der Innendurchmesser $d$, der Betrag der über den Querschnitt gemittelten Geschwindigkeit $v_m$ und die Viskosität des Fluids $\nu = \eta$ verwendet.

$Re_{Rohr} = \frac{v_m \cdot d}{\nu}$

Für Wasser gilt: $Re_{Rohr} = 2040 \pm 10 $



