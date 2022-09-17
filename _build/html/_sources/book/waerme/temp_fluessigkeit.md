# Temperatureffekte auf Flüssigkeiten

Im Gegensatz zu Festkörper sind Flüssigkeiten nicht formstabil, da die Temperatur hoch genug ist, um die Festkörperbindungen aufzubrechen und die Moleküle sich gegeneinander verschieben können. Daher passen sich Flüssigkeiten dem Volumen an, welches sie umgibt. Es macht daher hier keinen Sinn einen linearen Ausdehnungskoeffizienten zu betrachten. Daher wird bei Flüssigkeiten immer ein Volumenausdehnungskoeffizient betrachtet. 

Wie beim Festkörper wird eine Näherung vorgenommen, so dass zum Schluss wieder eine einfache lineare Formel angewendet werden kann. Daher ist auch hier wieder bei Litheraturwerten zu beachten, für welchen Temperaturbereich ein entsprechender Volumenausdehnungskoeffizient gültig ist.

Dann gilt analog zur Volumenausdehnung eines Festkörpers für die Volumenausdehnung einer Flüssigkeit

$V \left( T_0 + \Delta T \right) = V \left( T_0 \right) \left( 1 + \gamma \Delta T \right)$

Oft wird auch die temperaturabhängige Dichteänderung der Flüssigkeit angegeben. 

Die Dichte ist definiert als

$\rho = \frac{m}{V}$

Damit ist

$\rho = \frac{m}{V} \Leftrightarrow V = \frac{m}{\rho}$

Da sich die Masse bei Temperaturänderung nicht ändert, gilt

$\Rightarrow \frac{m}{\rho(T_0)} = \frac{m}{\rho \left( T_0 + \Delta T \right)}  \left(1 + \gamma \cdot \Delta T\right) \Leftrightarrow \rho(T_0 + \Delta T) = \frac{\rho \left(T_0 \right)}{\left(1 + \gamma \cdot \Delta T\right) } $

Diese Formel ist für viele Flüssigkeiten anwendbar, jedoch __nicht__ für Wasser! Wasser hat eine [Dichteanomalie](https://de.wikipedia.org/wiki/Dichteanomalie), und verhält sich damit anders als eine Flüssigkeit ohne Dichteanomalie. So hat Wasser seine maximale Dichte bei $4^\circ C$ und wird bei geringeren Temperaturen weniger dicht. 

## Beispiel: Quecksilberthermometer

Quecksilber hat einen nahezu temperaturunabhängigen Wärmeausdehnungskoeffizienten und benetzt das Glas des Thermometerröhrchens nicht. Damit hat es ideale Eigenschaften für die Temperaturmessung. Leider ist es hochgiftig, sodass in vielen Bereichen Flüssigkeitsthermometer als Alternative zum Quecksilberthermometer verwendet werden.

Raumausdehnungskoeffizient von Quecksilber ist damit in sehr guter Näherung als konstant anzusehen und ist gegeben durch

$\gamma \left( 20 ^\circ C\right) = 0,1811 \cdot 10^{-3} \, K^{-1}$

In einem Fieberthermometer ist eine Quecksilbermenge von ungefähr $1 \,g$ enthalten.   ￼
Bei 20 °C Raumtemperatur entspricht dies einer Kugel mit ungefähr $5.2 /,mm$ Durchmesser. 
Das entsprechende Volumen ist

$\Rightarrow V \left( 20^\circ C\right) = \frac{4}{3}\pi \left(\frac{5,2 \cdot 10^{-3} m}{2} \right)^3 \approx 73,6 \, mm^3 $

Ein Temperaturunterschied von $10^\circ$ erzeugt damit ein Volumen

$\Rightarrow V \left( 30^\circ C\right) = V\left(20^\circ C\right)\left(1+\gamma\cdot 10 K\right) \approx  73,8 \, mm^3 $

Diese Volumina befinden sich in einem zylindrischen Röhrchen. Typischerweise ist das Thermometer so geeicht, dass eine Temperaturänderung von  $10^\circ$ einen Höhenunterschied von $1 \, cm$ erzeugt. Bei einer zylindrischen Form hat somit das Glasröhrchen einen Durchmesser von 

$V_{Zylinder} = r^2 \cdot \pi \cdot h \Rightarrow \text{ mit } \Delta h = 1 \, cm \Rightarrow r = \sqrt{\frac{\Delta V}{\pi \Delta h}} \Rightarrow d = 2r \approx 0.13 \, mm $

Die Ausdehnung des Glasröhrchens wurde in dieser Rechnung vernachlässigt, da sie sehr klein gegenüber der Ausdehnung des Quecksilbers ist. 

## Beispiel: Volumenausgleichsgefäß beim Transformator

Bei große Transformatoren verwenden meist zur Isolation Schmieröle, sogenannte [Transformatorenöle](https://de.wikipedia.org/wiki/Transformatoren%C3%B6l). Im laufenden Betrieb erwärmt sich der Trafo, sodass auch das Trafoöl erwärmt wird. Dieses dehnt sich dann aus, weshalb Öltransformatoren ein Ausgleichsgefäß besitzen, um die Volumenänderung des Schmieröls aufzunehmen.

Raumausdehnungskoeffizient von Schmieröl ist $\gamma \left( 20 ^\circ C\right) \approx 0,6 \cdot 10^{-3} \, K^{-1}$ 
Laut TransnetBW beträgt Ölvolumen bis zu rund 100.000 Liter pflanzliches Isolieröl.

$\Rightarrow V_0 = 10 \cdot 10^{5}\cdot 10 \cdot 10^{-3} m^3 =100 \, m^3$

Im heissen Betrieb beträgt die Öltemperatur $T_{heiss} = 60^\circ C$

Die durchschnittliche Umgebungstemperatur beträgt $T_{heiss} = 60^\circ C$

Dies ergibt eine Temperaturdifferenz von $\Rightarrow \Delta T = 40 \,K$

Das Ölvolumen im heissen Zustand ist somit

$V_{heiss} = V_{kalt} \left(1 + \gamma \Delta T \right)= 100 \, m^3  \left(1 + 0,6 \cdot 10^{-3} K^{-1} 40 \,K \right)= 102,4 \, m^3$

Damit würde bei dieser Konfiguration ein Volumenausgleichsgefäß mit einer Größe von $\Rightarrow \Delta V = 2,4 \, m^3$ benötigt.
