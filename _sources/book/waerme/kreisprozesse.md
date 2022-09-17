# Thermodynamische Vergleichsprozesse

Mithilfe der vier grundlegenden Zustandsänderungen können nun thermodynamische Kreisprozesse berechnet werden. 
Kreisprozesse beschreiben die Umwandlung von Wärmeenergie in technische Arbeit durh einen Wärmekraftprozess.

**Definition Wärmekraftmaschine**

Eine Wärmekraftmaschine ist eine Maschine, die Wärme in mechanische Energie (Arbeit) umwandelt. Sie nutzt dabei das Bestreben der Wärme aus, von Gebieten mit höheren zu solchen mit niedrigeren Temperaturen zu fließen.

```{figure} Bilder/waermekraftmaschine.svg
---
width: 80%
alt: Wärmekraftmaschine
name: wkm-1
---
Schematische Darstellung einer Wärmekraftmaschine
 ```

**Definition Kreisprozess**

„Durchläuft ein System eine Folge von Zustandsänderungen, sodass der Endzustand wieder mit dem Anfangszustand übereinstimmt, so handelt es sich um einen Kreispro- zess. 
Ein rechtsläufiger Kreisprozess liegt vor, wenn die Zustandsänderungen im ￼Diagramm im Uhrzeigersinn durchlaufen werden.“ {cite}`hering`

```{figure} Bilder/kreisprozess.svg
---
width: 80%
alt: Kreisprozess
name: kreisprozess-1
---
Rechtsläufiger Kreisprozess im $p-V$-Diagramm
 ```

Die (bei rechtsläufigen Prozessen) nach außen abgegebene Nutzarbeit entspricht dem Flächeninhalt der vom Kreisprozess eingeschlossenen Figur in {numref}` Abbildung %s <kreisprozess-1>`.

Im Folgenden werden zwei Annahmen getroffen
* Reibungsfreie Zustandsänderungen 
* Gas befindet sich stets im thermodynamischen Gleichgewicht mit der Umgebung

Am Ende des Kreisprozesses ist der gleich Zustand erreicht, wie zu Beginn des Kreisprozesses. Dies bedeutet, dass die thermodynamischen Zustandsgrößen am Anfang und am Ende gleich sind. 

Damit gilt für das Integral über den durchlaufenen Weg im $p-V$-Diagramm

$\oint dU = 0$

Aus dem [ersten Hauptsatz](hauptsaetze.html#erster-hauptsatz) folgt dann

$\oint dU = 0 = \oint dQ + \oint dW \Rightarrow 0 = Q_{zu} + Q_{ab} + W_{Nutz}$

Die Effizienz eines Kreisprozesses wird durch den Wirkungsgrad beschrieben. Dieser ist definiert als

$\eta =  \frac{\left| W_{Nutz}\right|}{Q_{zu}} $

Der Kreisprozess mit dem größten möglichen Wirkungsgrad ist der Carnot-Prozess

## Carnot-Prozess

Der Carnot-Prozess ist ein theoretischer Kreisprozess, mit dem Wärme in einer periodisch arbeitenden Maschine in mechanische Arbeit umgeformt werden kann. 
Er läuft in folgender Weise ab:

1. Ein Gas steht wechselweise mit einem Wärmereservoir von konstant hoher Temperatur (zur Aufnahme von Wärme) und einem Kältereservoir mit konstant niedrigerer Temperatur (zur Abgabe von Wärme) in Kontakt, wobei es wechselweise durch Aufbringen mechanischer Arbeit verdichtet wird und unter Abgabe von mechanischer Arbeit wieder expandiert. 
1. Das Gas erreicht nach vollständigem Durchlauf des Prozesses wieder den Ausgangszustand, d. h. alle Zustandsgrößen, wie Temperatur T, Druck p, Volumen V, Innere Energie U und Entropie S sind damit wieder so groß wie zu Beginn des Prozesses.

Eine Darstellung des Prozesses ist in {numref}` Abbildung %s <carnot-1>` zu finden. 
 
Dieser Prozess ist deshalb ein theoretischer Prozess, da es in der Praxis nicht möglich ist kaltes und warmes Reservoir verlustfrei zu tauschen.

```{figure} https://upload.wikimedia.org/wikipedia/commons/8/83/Carnotprozess_im_Zeitdiagramm.svg
---
width: 80%
alt: Carnot-Prozess
name: carnot-1
---
Carnot-Prozess ([Von Menner](https://commons.wikimedia.org/w/index.php?curid=37913632))
 ```

Der Carnot-Prozess besteht aus vier Schritten

1. Von (1) nach (2): Isotherme Kompression
1. Von (2) nach (3): Isentrope Kompression
1. Von (3) nach (4): Isotherme Expansion
1. Von (4) nach (1): Isentrope Expansion

**Von (1) nach (2): Isotherme Kompression**

```{figure} Bilder/carnot-1.svg
---
width: 80%
alt: Carnot-Prozess
name: carnot-2
---
Carnot-Prozess von (1) nach (2): Isotherme Kompression
 ```

Für die isotherme Zustandsänderung gilt: 

$p \cdot V = n \cdot R \cdot T = \text{konst.}$

$p \propto \frac{1}{V}$

$\Delta U = 0 \Rightarrow \Delta Q = -\Delta W$

Die dem Prozess zugeführte Arbeit ist

$W_{12} = - \int_1^2 p(V) \cdot dV = - \int_1^2 \frac{n R  T_1}{V} \cdot dV = n  R T_1 \cdot ln \left( \frac{V_1}{V_2}\right)$


Da der Prozess isotherm ist, muss die gleiche Menge Wärme an die Umgebung abgegeben werden. Damit ist

$Q_{12} = - W_{12} = - n  R T_1 \cdot ln \left( \frac{V_1}{V_2}\right)$

**Von (2) nach (3): Isentrope Kompression**

```{figure} Bilder/carnot-2.svg
---
width: 80%
alt: Carnot-Prozess
name: carnot-3
---
Carnot-Prozess von (2) nach (3): Isentrope Kompression
 ```

Für die isentrope Zustandsänderung gilt

$\rightarrow \Delta Q = 0$

$\rightarrow dU = dW$

Aus der Definition von $C_V$ ergibt sich

$C_V = \left(\frac{dU}{dT} \right)_{V = \text{konst.}} \Leftrightarrow dU = C_V \cdot dT = m \cdot c_V \cdot dT $

Damit gilt allgemein für ein ideales Gas für die Änderung der inneren Energie $\Delta U$ durch  Temperaturänderung $\Delta T$

$\Delta U = m \cdot c_V \cdot \Delta T $

Isentrope Kompression von $V_2$ auf $V_3, Temperatur steigt von $T_2 = T_1$ auf $T_3$:

Damit ist die zugeführte Arbeit: $W_{23} = \Delta U_{23} = m c_V \left( T_3 - T_1 \right)$


**Von (3) nach (4): Isotherme Expansion**

```{figure} Bilder/carnot-3.svg
---
width: 80%
alt: Carnot-Prozess
name: carnot-4
---
Carnot-Prozess von (3) nach (4): Isotherme Expansion
 ```

Für die isotherme Zustandsänderung gilt wieser : 

$p \cdot V = n \cdot R \cdot T = \text{konst.}$

$p \propto \frac{1}{V}$

$\Delta U = 0 \Rightarrow \Delta Q = -\Delta W$

Die dem Prozess zugeführte Arbeit ist

$W_{34} = - \int_3^4 p(V) \cdot dV = - \int_3^4 \frac{n R  T_3}{V} \cdot dV = n  R T_3 \cdot ln \left( \frac{V_4}{V_3}\right)$

Diesmal wird die Wärmemenge aus der Umgebung aufgenommen

$Q_{34} = n  R T_3 \cdot ln \left( \frac{V_4}{V_3}\right)$

**Von (4) nach (1): Isentrope Expansion**

```{figure} Bilder/carnot-4.svg
---
width: 80%
alt: Carnot-Prozess
name: carnot-5
---
Carnot-Prozess von (4) nach (1): Isentrope Expansion
 ```

Analog zur isentropen Kompression gilt

$W_{41} = \Delta U_{42} = m c_V \left( T_1 - T_3 \right) = - m c_V \left( T_3 - T_1 \right)$

Die Nutzarbeit im Carnot-Prozess ist somit

$W_{Nutz} = \oint dW = W_{12} + W_{23} + W_{34} + W_{41} = n  R T_1 \cdot ln \left( \frac{V_1}{V_2}\right) + m c_V \left( T_3 - T_1 \right) + n  R T_3 \cdot ln \left( \frac{V_4}{V_3}\right)- m c_V \left( T_3 - T_1 \right) $

$= n  R \left( T_1 \cdot ln \left( \frac{V_1}{V_2}\right) + T_3 \cdot ln \left( \frac{V_4}{V_3}\right) \right)$

Dies lässt sich weiter vereinfachen durch eine Beziehung zwischen den verschiedenen Volumina.

Da es sich um eine adiabate Zustandsänderung handelt, gilt:

$p \cdot V^\kappa = \text{konst.}$

Mit Hilfe der idealen Gasgleichung lässt sich dieses umstellen zu 

$p \cdot V^\kappa = \text{konst.} \Rightarrow \frac{n \cdot R \cdot T}{V}V^\kappa = \text{konst.} \Rightarrow T \cdot V^{\kappa -1} = \text{konst.}$

Daraus folgt

(A) $T_2 \cdot V_2^{\kappa -1} = T_1 \cdot V_2^{\kappa -1} = T_3 \cdot V_3^{\kappa -1}$
(B) $T_4 \cdot V_4^{\kappa -1} = T_3 \cdot V_4^{\kappa -1} = T_1 \cdot V_1^{\kappa -1}$

da $T_2 = T_1$ und $T_4 = T_3$

(A)/(B) $= \frac{V_1^{\kappa - 1}}{V_2^{\kappa - 1}} = \frac{V_4^{\kappa - 1}}{V_3^{\kappa - 1}} = \frac{V_1}{V_2} = \frac{V_4}{V_3}$

Damit vereinfacht sich die Nutzarbeit zu

$W_{Nutz} = - n  R \cdot ln \left( \frac{V_4}{V_3}\right) \left( T_3  - T_1 \right) $

Diese ist negativ, weil Arbeit vom System nach außen abgegeben wird.

Wärme wird dem Prozess nur von (3) nach (4) zugeführt. Also ist

$Q_{zu} = Q_{34} = n  R T_3 \cdot ln \left( \frac{V_4}{V_3}\right)$

Damit ist der Wirkungsgrad des Carnot-Prozesses

$\eta_{th} = \frac{\left| W_{Nutz}\right|}{Q_{Zu}} = \eta_{th} = \frac{\left| - n  R \cdot ln \left( \frac{V_4}{V_3}\right) \left( T_3  - T_1 \right) \right|}{n  R T_3 \cdot ln \left( \frac{V_4}{V_3}\right)} =\frac{T_3 - T_1}{T_3} \Leftrightarrow \eta_{th} = 1 - \frac{T_3}{T_1}$

Der Wirkungsgrad des Carnot-Prozesses hängt also nur von der Temperaturdifferenz zwischen Wärme- und Kältereservoir ab und ist immer kleiner als 1.

Alle realen Kreisprozesse haben einen niedrigeren Wirkungsgrad also der Carnot-Prozess. Der Carnot-Prozess stellt damit eine theoretische Obergrenze dar, die ein Kreisprozess nicht überschreiten kann.


```{figure} https://upload.wikimedia.org/wikipedia/commons/6/63/Carnot_Wirkungsgrad.svg
---
width: 80%
alt: Carnot-Prozess
name: carnot-6
---
Wirkungsgrad des Carnot-Prozesses ([Von Menner](https://commons.wikimedia.org/w/index.php?curid=32812564))
 ```