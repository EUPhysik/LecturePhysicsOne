# Aerostatik

Auf Meeresspiegelhöhe bei $20^\circ$ wiegt $1 \, m^3$ Luft rund $1.2041 \,kg$. Dieses Gewicht hängt von der Dichte der Luft ab. Die Dichte der Luft wiederum hängt davon ab, mit welcher Kraft die Luft zusammengedrückt wird, also wie groß der Luftdruck ist. 

Die Existenz des Luftdrucks wurde das [Magdeburger Hallbkugel Experiment](https://de.wikipedia.org/wiki/Magdeburger_Halbkugeln) nachgewiesen. 

## Barometrische Höhenformel

In der Erdatmosphäre sinkt der Luftdruck mit steigender Höhe, da in größerer Höhe die darüberliegenden Luftmassen kleiner sind. Da Luft ein Gas und somit kompressibel ist, ändert sich die Dichte der Luft mit dem Druck. Die Änderung von Druck und Dichte der Atmosphäre mit der Höhe wird durch die hydrostatische Grundgleichung beschrieben. 

```{figure} Bilder/barometrischehoehenformel.svg
---
width: 60%
alt: Barometrische Höhenformel
name: barom-1
---
Barometrische Höhenformel
 ```

Wenn sich das infinitesimale Luftelement nicht bewegt, befindet es sich im statischen Gleichgewicht (ansonsten würde es sich solange bewegen, bis es sich im Gleichgewicht befindet).

statisches Kräftegleichgewicht 

$\Rightarrow F_{ges} = 0 = p(h)\cdot A -(p(h) + dp )\cdot A - dm\cdot g$

$\Leftrightarrow -A \cdot dp - dm \cdot g = 0 \Leftrightarrow -A \cdot dp - \rho \cdot g \cdot A \cdot dh = 0 \Leftrightarrow -dp - \rho \cdot g \cdot dh = 0$

Unter der Annahme, dass die Dichte proportional zum Druck ist, gilt $\rho \propto p$. Auf Meereshöhe können Druck und Dichte einfach vermessen werden $\left( p_0, 
\rho_0 \right)$

$\Rightarrow \frac{\rho}{p} = \frac{\rho_0}{p_0}$

Dann ist

$dp = - p \frac{\rho_0 }{p_0} g dh \Leftrightarrow \frac{dp}{p} = - \frac{\rho_0 }{p_0} g dh$

$\frac{dp}{p} = - \frac{\rho_0 }{p_0} g dh \longrightarrow \int_{p_0}^{p(h)} \frac{dp}{p} = \int_{h_0}^h- \frac{\rho_0 }{p_0} g dh$

$\Rightarrow ln \left( \frac{p(h)}{p_0} \right) = - \frac{\rho_0}{p_0} g h \Rightarrow p(h) = p_0 e^{- \left(\rho_0/p_0\right) gh}$

```{figure} https://upload.wikimedia.org/wikipedia/commons/9/95/Pressure_air.svg
---
width: 80%
alt: Barometrische Höhenformel
name: barom-2
---
Barometrische Höhenformel,  [Von Klaus-Dieter Keller](https://commons.wikimedia.org/w/index.php?curid=25608825)
 ```