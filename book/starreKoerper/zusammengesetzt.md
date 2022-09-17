# Trägheitsmoment zusammengesetzter Körper

Das Trägheitsmoment von zusammengesetzten Körper kann berechnet werden durch die Summee der einzelnen Teile.

$\Theta = \sum_i \Theta_i$

## Beispiel: Trägheitsmoment einer Hantel, längs

```{figure} Bilder/hantel.svg
---
width: 800px
name: hantel
---
Rotierende Hantel, längs
 ```

Trägheitsmoment einer Kugel: $\Theta_{Kugel} = \frac{2}{5} m_{Kugel} R^2$

Trägheitsmoment eines Zylinders: $\Theta_{Zylinder} = \frac{1}{2} m_{Zylinder} \left( \frac{d}{2} \right)^2$

Gesamtträgheitsmoment $\Theta = 2 \cdot \Theta_{Kugel} + \Theta_{Zylinder} = \Theta_{gesamt} = \frac{4}{5} m_{Kugel} R^2 + \frac{1}{2} m_{Zylinder} \left(\frac{d}{2} \right)^2$

## Beispiel: Trägheitsmoment einer Hantel, quer

```{figure} Bilder/hantel2.svg
---
width: 500px
name: hantel-2
---
Rotierende Hantel, quer
 ```

Trägheitsmoment der Kugel durch den Schwerpunkt: $\Theta_{Kugel,SP} =\frac{2}{5} m_{Kugel} R^2$

Trägheitsmoment um die um $\frac{l}{2}$ verschobene Achse $\Rightarrow \Theta_{Kugel} = \frac{2}{5} m_{Kugel} R^2 + m_{Kugel} \left( \frac{l}{2} \right)^2$

$\Theta_{Zylinder,quer} = \frac{1}{4}m_{Zylinder}\,\left( \frac{d}{2} \right)^2 + \frac{1}{12}m_{Zylinder}\,l^2$

$\Theta_{Gesamt} =  \frac{1}{4}m_{Zylinder}\, \left( \frac{d}{2} \right)^2 + \frac{1}{12}m_{Zylinder}\, l^2 + 2\cdot \left( \frac{2}{5} m_{Kugel} R^2 + m_{Kugel} \left( \frac{l}{2} \right)^2 \right)$