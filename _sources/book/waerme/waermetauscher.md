# Wärmetauscher

Eine einfache Anwendung, bei der man sich dei Grundlagen thermodynamischer Prinzipien zu Nutze macht, ist ein Wärmetauscher.
Dies ist eine Vorrichtung, die thermische Energie von einem Stoffstrom auf einen anderen überträgt. 
Dabei gibt das warme Medium gibt Wärme ab und das kalte Medium nimmt Wärme auf.
Ein Beispiel für einen Wärmetauscher ist in {numref}` Abbildung %s <wt-1>` dargestellt.

```{figure} https://upload.wikimedia.org/wikipedia/commons/a/a8/WTU-Email.jpg
---
width: 80%
alt: Rohrbündelwärmetauscher
name: wt-1
---
Rohrbündelwärmetauscher ([Von JurecGermany](https://commons.wikimedia.org/w/index.php?curid=12046717))
 ```



## Prinzip eines Wärmetauschers

Im Wärmetauscher gibt es zwei Stoffströme, einen Warmen, der Energie abgibt, und einen Kalten, der Energie aufnimmt.
Im Gleichstromwärmetauscher fließen beide Stoffströme in die gleiche Richtung. Die beiden Stoffströme vermischen sich nicht, sondern tauschen nur Wärmeenergie aus. 

Der Druck im Wärmetauscher ist konstant. Daher liegt hier in jedem Strom eine Isobare Zustandsänderung vor.
Bei [Isobaren](./zustandsaenderungen.html#isobare-zustandsanderung) gilt für die Entropie

$dS = \frac{d Q}{T} = \frac{dH}{T} = \left| \frac{C_p \cdot dT }{T} \right| _{p = \text{konst.}} = m \cdot c_p \frac{dT}{T} \Rightarrow dQ = m \cdot c_p \cdot dT \Rightarrow \frac{dQ}{dt} = \frac{d}{dt} \left( m \cdot c_p \cdot dT \right)$

Sind $c_p$ und $dT$ nicht zeitabhängig sind, gilt

$\dot{Q} = \dot{m} c_p dT$

Die ist die thermische Leistung des Wärmetauschers.

```{figure} Bilder/waermetauscher.png
---
width: 100%
alt: Prinzip eines Wärmetauschers
name: wt-2
---
Prinzip eines Wärmetauschers
 ```

Da auf der warmen Seite die gleiche Leistung abgegeben wird (siehe {numref}` Abbildung %s <wt-2>`), wie von der kalten Seite aufgenommen wird, gilt

$\dot{Q}_{kalt} = \dot{m}_1 \cdot c_p \cdot \Delta T_{kalt}$

und

$\dot{Q}_{warm} = \dot{m}_2 \cdot c_p \cdot \Delta T_{warm}$

mit

$\dot{Q}_{warm} = \dot{Q}_{kalt}$

Zur Bestimmung der thermischen Leistung ist es meistens ausreichend, eine von der Strömungsführung abhängige mittlere Temperaturdifferenz des Gesamtapparates zu verwenden.


### Beispiel: Auskopplung von Nahwärme

Wasser zur Auskopplung der Nahwärme soll um $15\, K$ erwärmt werden. Der Massenstrom in der Fernwärmeleitung sei $10$ mal so groß wie in der Hauswärmeleitung.

```{figure} Bilder/waermetauscher2.png
---
width: 80%
alt: Prinzip eines Wärmetauschers
name: wt-3
---
Prinzip eines Wärmetauschers
 ```

Hauswärmeleitung $\Delta T_{kalt} = 15 \, K$

Massenstrom $\dot{m}_{warm} = 10 \cdot \dot{m}_{kalt}$

$\dot{Q}_{warm} = \dot{Q}_{kalt} \Leftrightarrow \dot{m}_{warm} \cdot c_p \cdot \Delta T_{warm} = \dot{m}_{kalt} \cdot c_p \cdot \Delta T_{kalt}$

$\Leftrightarrow \dot{m}_{warm} \cdot \Delta T_{warm} = \dot{m}_{kalt} \cdot \Delta T_{kalt} \Leftrightarrow 10 \cdot \dot{m}_{kalt} \cdot \Delta T_{warm} = \dot{m}_{kalt} \cdot \Delta T_{kalt}$

$\Leftrightarrow \Delta T_{warm} = \frac{ \Delta T_{kalt}}{10} = 1,5 \,K$

## Wärmeleitung 

Will man nicht nur die übertragenen Wärmeleistung berechnen, sondern genauer verstehen wie die Wärme transportiert wird, muss genauer angeschaut werden, die die Wärme transportiert werden.
Die Wärmeleitung ist ein Mechanismus zum Transport von thermischer Energie und wird beschrieben durch das Fouriersches-Gesetz:

$\dot{Q} = \lambda \cdot A \cdot \frac{\Delta T}{d}$

mit $\lambda =$ Wärmeleitfähigkeitskoeffizient, $\left[\lambda \right] = \frac{W}{m\cdot K}$ 

und $\Delta T = T_2 - T_1$

```{figure} Bilder/waermeleitung.png
---
width: 40%
alt: Wärmeleitung
name: wt-4
---
Wärmeleitung
 ```

Beispiel für Wärmeleitkoeffizienten sind

|Material|$\left[\lambda \right] = \frac{W}{m\cdot K}$|
|--|--|
|Beton | 0,18 - 1,3|
|Holz |0,15|
|Kupfer |401|
|Messing |120|
|Stahl |50-80|
|Luft |0,026|
|Wasser |0,61|
|Eis |2|
|Wolle |0,04|
|Glas |0,8|

Alternativ wird der Wärmedurchgangskoeffizient $k$ und die mittlere logarithmische Temperaturdifferenz verwendet, dann wird das Fouriersches-Gesetz zu

$\dot{Q} = k \cdot A \cdot \Delta T_{log}$

mit

Wärmedurchgangskoeffizient $k$ mit $\left[k\right] = \frac{W}{m^2 \cdot K}$

Austauschfläche $A$ mit $\left[A\right] = m^2$

Mittlere logarithmische Temperaturdifferenz $\Delta T_{log}$ mit $\Delta T_{log} = \frac{\Delta T_{max} - \Delta T_{min}}{ln \left( \frac{\Delta T_{max}}{\Delta T_{min}} \right)}$

und $\left[ \Delta T_{log} \right] = K$

Die beiden häufigsten Varianten eine Wärmeströmers sind das Gleichstromprinzip und das Gegenstromprinzip.

|![](https://upload.wikimedia.org/wikipedia/de/e/eb/Gleichstromprinzip.png)|![](https://upload.wikimedia.org/wikipedia/de/0/01/Gegenstromprinzip.png)| 

Quellen: [Gleichstrom](https://de.wikipedia.org/w/index.php?curid=2143054) und [Gegenstrom](https://de.wikipedia.org/w/index.php?curid=345286)


Beim Gleichstromwärmetauscher strömen beide Massenströme in die gleiche Richtung
Beim Gegenstromwärmetauscher strömen die Massenströme in die entgegengesetze Richtung

Gleichstromwärmetauscher hat eine hohe Wärmeaustauschrate bei großen Temperaturunterschieden $\Rightarrow$ schnelle Wärmeübertragung

Beim Gegenstromwärmetauscher ist die Leistung bei gleicher Austauschfläche größer als im Gleichstrom. Die Ausgangstemperatur des kalten Mediums kann über der Ausgangstemperatur des warmen Mediums liegen, so dass die Wärme optimaler übertragen wird.


