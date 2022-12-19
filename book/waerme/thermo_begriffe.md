# Thermodynamische Grundbegriffe

Bislang wurde das Verhalten von Festkörper, Flüssigkeiten und Gase bei Temperaturänderungen betrachtet. Für ein tieferes Verständnis werden im Folgenden die Grundlagen thermodynamischer Zustandsänderungen beschrieben.
Hierzu werden zunächst wichtige Begriffe definiert und erläutert. 

## Begriffsdefinitionen

### Volumen

Das Volumen $V$ ist die Ausdehnung bzw. der Platzbedarf eines Körpers

$\left[ V\right] = 1 \, m^3$

Für Flüssigkeiten oft $\left[V\right] = 1 \, l = \, 1\, \text{Liter} \, = 1 \, \left(0,1 \, m\right)^3 = 10^{(-3)} \, m^3$

### Druck

Der Druck $p$ ist definiert durch $p = \frac{F}{A}$.

Der thermodynamische Druck ist eine Zustandsgröße, die bei einem Gas mit einer Zustandsgleichung definiert wird, und kann im Ungleichgewicht vom mechanischen Druck abweichen.

Beispiele sind

* Hydrostatischer Druck $p(h) = \rho g h \left(+ \rho_0 \right)$
* Hydrodynamischer Druck $p(v)= \frac{1}{2} \rho v^2$
* Gasdruck $p \cdot V = n\cdot R\cdot T$

### Temperatur

Die Temperatur ist die mittlere kinetische Energie der Teilchen in einem Material. Eine Temperatur kann daher nur für ein System bestimmt werden, welches sich im Gleichgewicht befindet. Die SI-Einheit der Temperatur ist 1 Kelvin (1 $K$).

### innere Energie

Die innere Energie $U$ ist die gesamte für thermodynamische Umwandlungsprozesse zur Verfügung stehende Energie eines physikalischen Systems, das sich in Ruhe und im thermodynamischen Gleichgewicht befindet. 
Die innere Energie ändert sich, wenn das System mit seiner Umgebung Wärme oder Arbeit austauscht. 

$\Delta U = \Delta Q + \Delta W$

$\Delta Q = $ dem System zugefügte oder entnommene Wärme

$\Delta W = $ am System verrichtete Arbeit

Im Allgemeinen ist die innere Energie die gesamte kinetische Energie der ungeordneten Bewegung der Teilchen.
Weitere Beiträge zur inneren Energie (molekülinterne Schwingungen, chemische Reaktionen, Radioaktivität, Bindungskräfte und van-der-Waals Kräfte) können oft vernachlässigt werden.
Zur inneren Energie eines Systems gehört nicht die potentielle oder kinetische Energie des gesamten Systems. 
Die innere Energie ist eine extensive Größe. 

Der Absolutwert der inneren Energie ist schwer zu berechnen, da es viele mögliche Beiträge gibt.

Für ideale Gase kann $U$ bäherungsweise berechnet werden. 
Hierzu verwendet man den [Gleichverteilungssatz](https://de.wikipedia.org/wiki/Gleichverteilungssatz). Ein Teilchen in einem System, das sich im thermodynamischen Gleichgewicht befindet, besitzt für jeden Freiheitsgrad eine Energie von ￼$\frac{1}{2} k_B \cdot T= \frac{1}{2} \frac{R}{N_A}T$

Dann gilt für die innere Energie des idealen Gases $U = \frac{f}{2} n R T$, wobei $f$ die Anzahl der Freiheitsgrade ist. 
Für ein 1-atomiges Gas ist $f=3$, dies entspricht den drei Freiheitsgraden der Translation.

### Enthalpie

Die Enthalpie $H$ kann als Wärmeinhalt eines thermodynamischen Systems verstanden werden.
Sie ist die Summe aus der inneren Energie $U$ des Systems und dem Produkt aus Druck $p$ und Volumen $V$.

$H = U + p\cdot V$

$\left[ H\right] = 1 \, J$

Die Enthalpie ist eine extensive Größe: Die Enthalpie eines Gesamtsystems ist die Summe der Enthalpien der Teilsysteme.

### Entropie

Die Entropie ist ein abstrakter Begriff und folgt aus der statistischen Herleitung der Thermodynamik.
Die Thermodynamische Definition der Entropie erfolge durch Ludwig Boltzmann und ist gegeben durch

$S = k_B \cdot ln \left(\Omega\right)$ 

Dabei ist $\Omega$ das Phasenraumvolumen. Dieses kann man sich in etwa wie folgt vorstellen:

Betrachtet man ein System aus vier Teilchen, die entweder auf der rechten oder der linken Seite eines Behälters sein können. In {numref}` Abbildung %s <phasenraum>` sind die Möglichkeiten dagestellt, mit denen ein bestimmter Zustand erzeugt werden kann. Beispielsweise gibt es nur eine Möglickeit, wenn alle Teilchen links sein sollen, jedoch 6 Moglichkeiten, wenn je 2 Teilchen links und 2 Teilchen rechts sein sollen. Da die Teilchen ununterscheidbar sind, sind die Möglichkeiten jeweils gleichwertig. Die Anzahl der Möglichkeiten, mit der ein Zustand konstruiert werden kann, stellt das Phasenraumvolumen dar.

```{figure} https://upload.wikimedia.org/wikipedia/commons/2/28/Possible-distributions-4-particles.svg
---
width: 70%
alt: Veranschaulichung des Phasenraumvolumens
name: phasenraum
---
Veranschaulichung des Phasenraumvolumens [Von MikeRun](https://commons.wikimedia.org/w/index.php?curid=84321913)
 ```

Die Einheit der Entropie ist

$\left[ S \right] = \frac{J}{K}$

Die Entropie ist somit als ein objektives Maß für die Menge an Information zu begreifen, die benötigt würde, um von einem beobachtbaren Makrozustand auf den tatsächlich vorliegenden Mikrozustand des Systems schließen zu können. (Das umgangssprachliche: „Maß für Unordnung“ trifft die Definition der Entropie daher nur in etwa.

Entropie ist eine extensive Größe: Fasst man zwei System zu einem einzigen System zusammen, ist die Gesamtentropie die Summe der Entropien beider Systeme.

Bei reversiblen Prozessen gilt

$dS = \frac{dQ_{reversibel}}{T}$



### Wärmeenergie und -kapazität

Wird einem System Wärme zugeführt, ändert sich die Temperatur des Systems, der Betrag der Temperaturänderung hängt von den Stoffeigenschaften ab.
Die Menge an Energie, die aufgewendet werden muss, um $1 \, kg$ Stoff um $1 \, K$ zu erwärmen wird als Wärmekapazität $C$ bezeichnet. 

$C = \frac{\Delta Q}{\Delta T}$

Die Wärmekapazität ist stoffspezifisch, bezogen auf die Masse ergibt sich die spezifische Wärmekapazität $c = \frac{C}{m}$ bzw. $C=c\,m=C_m\,n$ mit $C_m$ molare Wärmekapazität.

Ein Stoff verhält sich prinzipiell unterschiedlich beim Erwärmen, je nachdem ob die Messung bei konstantem äußerem Druck $p$ oder bei gleichbleibendem Volumen $V$ durchgeführt wird, daher unterscheidet man

* $C_p$ Wärmekapazität bei konstantem Druck, sie ist definiert als $C_P = \left(\frac{dH}{dT} \right)_{p = \text{konst.}}$
* $C_V$ Wärmekapazität bei konstantem Volumen, sie ist definiert als $C_V = \left(\frac{dU}{dT} \right)_{V = \text{konst.}}$

Die spezifische Wärmekapazität ist 

$c = \frac{C}{m}$

Dies ist hauptsächlich für kompressible Stoffe, wie Gase, relevant. Für Feststoffe und Flüssigkeiten gilt $c_p \approx c_V = c$. 

Für ideale Gase gilt

$C_p = C_V + n \cdot R$ beziehungsweise $c_p = c_V + R_S$



Die Wärmekapazität ist die Fähigkeit eines Stoffes, Wärme und damit thermische Energie zu speichern. 

Die hinzugefügte Wärme $\Delta Q$ einer Masse $m$ bei einer Temperaturdifferenz 

$\Delta T$ ist $\Delta Q = m \cdot c \cdot \Delta T$


Die Einheit der Wärme ist die einer Energie $\rightarrow \left[ \Delta Q \right] = 1 \, J$.

#### Beispiel: Wasser kochen

Wie groß ist die hinzugefügte Wärmeenergie, wenn $1 \,l$ Wasser von $T_1 = 20^\circ C$ au4 $T_1 = 100^\circ C$ erhitzt wird?

$\Delta T = T_2 -T_1 = 80 \,K$

$\Delta Q = c \cdot m \cdot \Delta T = c \cdot \rho \cdot V \cdot \Delta T$

Für Wasser ist die Wärmekapazität $c = c_{Wasser} = 4,19 \frac{kJ}{kg \cdot K}$

Die Dichte von Wasser ist $\rho = \rho_{Wasser}(20 ^\circ C) = 0,998202 \frac{g}{cm^3} $

Streng genommen müsste die Dichte- und Volumenänderung des Wassers berücksichtigt werden. Da die Masse aber konstant bleibt, mitteln sich diese Änderungen weg.

Damit ist 

$\Delta Q = 4,19 \frac{kJ}{kg \cdot K} \cdot 10^{-3} m^3 \cdot 9982,02 \frac{kg}{m^3} \cdot 80 \, K = 335 \, kJ = 0,093 \, kWh$