# Trägheitsmoment

Um die Drehbewegung eines starren Körpers zu beschreiben, werden Trägheitsmomente verwendet. 
Um den Begriff des Trägheitsmomentes zu verstehen, bietet sich der Vergleich mit der Kreisbewegung eines Massenpunktes an. 

```{figure} Bilder/Drehimpuls_Punktmasse.svg
---
width: 300px
name: Drehimpuls_Punktmasse-1
---
Kreisbewegung einer Punktmasse.  
 ```

Der Drehimpuls ist dabei:

$\vec{L} = m \cdot \left( \vec{v} \times \vec{r} \right)$

Da bei der Kreisbewegung $\vec{v} \perp \vec{r}$ ist, gilt:

$\Rightarrow \left| \vec{L} \right| = m  \cdot v \cdot r = m  \cdot \omega r \cdot r = m r^2 \omega$

Analog zum Impuls $ \vec{p} = m \cdot \vec{v}$ definiert man dann das Trägheitsmoment $\Theta$

$\vec{L} = \Theta \vec{\omega}$

Für eine Punktmasse auf einer Kreisbahn ist demnach
$ \Theta =: mr^2$

Für Drehimpuls und Drehmoment gilt dann analog zu Impuls und Kraft der Zusammenhang

$\vec{M} = \frac{d \vec{L}}{dt} = \Theta \frac{d \vec{\omega}}{dt} = \Theta \vec{\alpha}$

wobei $\vec{\alpha}$ die Winkelbeschleunigung ist.


|Translation||Rotation||
|-|-|-|-
|Kraft|$\vec{F} = \frac{d \vec{p}}{dt}$|Drehmoment|$\vec{M} = \frac{d \vec{L}}{dt}$|
||$\vec{F} = m \cdot \vec{a}$||$\vec{M} = \Theta \cdot \vec{\alpha}$| 
|Impuls|$\vec{p}$|Drehimpuls|$\vec{L} = \vec{r} \times \vec{p}$|
||$\vec{p} = m \cdot \vec{v}$||$\vec{L} =\Theta \cdot \omega$|

Wie der Impuls bei der Translationsbewegung, ist der Drehimpuls bei der Drehbewegung eine Erhaltungsgröße, wenn kein äußeres Drehmoment anliegt.


## Drehimpulserhaltung bei mehreren Massen

Im Folgenden wird nun ein einfacher starrer Körper, der aus drei fest miteinander verbundenen Massenpunkten besteht. 

```{figure} Bilder/starrer_koerper_drehung.png
---
width: 400px
name: starrer_koerper_drehung-1
---
Drehbewegung eines starren Körpers aus mehreren diskreten Massenpunkten.  
 ```

Für $m_1$ gilt:

$\vec{M}_{1} = \vec{r}_{1} \times \left( \vec{F}_{1,e} + \vec{F}_{12,i} + \vec{F}_{12,i} \right)$

Und äquivalent gilt nach Newton für $\vec{M}_2$ und $\vec{M}_3$

$\vec{F}_{kj,i} = - \vec{F}_{jk,i} $

Zum Beispiel gilt:

$\vec{r}_1 \times \vec{F}_{12,i} + \vec{r}_2 \times \vec{F}_{21,i} = \left( \vec{r}_1 -\vec{r}_2 \right) \times \vec{F}_{12,i} = 0$

da $\left( \vec{r}_1 - \vec{r}_2 \right) \parallel \vec{F}_{12,i}$

Damit gilt $\vec{M} = \sum_k \vec{M}_k = \sum_k \vec{M}_{k,e} $

mit $\vec{M}_k = \frac{d \vec{L}_k}{dt} = \vec{r}_k \times \left( \vec{F}_{k,e} + \sum_{k \not= j} \vec{F}_{kj,i} \right)$

da die inneren Kräfte sich aufheben. Es gilt:

$\frac{d \vec{L}}{dt} = \frac{d}{dt} \sum_k \vec{L}_k = \vec{M}$

Greift kein äußeres Drehmoment an, ist der Gesamtdrehimpuls erhalten:

$\vec{M} = 0 \Rightarrow \vec{L} = \sum_k \vec{L}_k = \text{konstant}$

Für die Drehimpulse gilt $\vec{L}_k = \Theta_k \omega_k$

Und damit $\vec{L} = \Theta_1 \omega_1 + \Theta_2 \omega_2 + \Theta_3 \omega_3$

Da die Massen einen festen Abstand zueinander haben, gilt $\omega_1 = \omega_2 = \omega_3 =:\omega$ und somit $\vec{L} = \left(\Theta_1  + \Theta_2  + \Theta_3 \right)\omega$

Das gesamte Trägheitsmoment $\Theta = \left(\Theta_1  + \Theta_2  + \Theta_3 \right)$ ist also die Summe der Trägheitsmomente der Massenpunkte. 

## Trägheitsmoment von starren Körpern

Wie in [](#trägheitsmoment) dargestell, ist das Trägheitsmoment einer Punktmasse mit Abstand $r$ zur Drehachse und Masse $m$ 

$\Theta = m \cdot r^2$

```{figure} Bilder/Berechnung_Traegheitsmoment.svg
---
width: 300px
name: Berechnung_Traegheitsmoment
---
Übergang zur kontinuierlichen Massenverteilung  
 ```


Trägheitsmoment eines infinitesimalen Masse-Elements mit Abstand $r$ zur Drehachse und Masse $dm$ ist somit

$d\Theta = dm \cdot r^2$

Für das Massenelement $dm$ gilt mit $\rho = \frac{m}{V}$ $\Rightarrow dm = \rho dV$
Damit ist dann das Trägheitsmoment

$\Theta = \int_V \, r^2 \rho \, dV$

## Beispiel: Trägheitsmoment eines dünnen Stabs

```{figure} Bilder/Duenner_Stab.svg
---
width: 600px
name: Duenner_Stab-1
---
Modell eines dünnen Stabes  
 ```

Das Trägheitsmoment eines dünnen Stabes soll berechnen werden. 

Allgemein gilt $\Theta = \int_V \, r^2 \rho \, dV$

Da da radiale Ausdehnung des Stabs vernachlässigbar ist $\left( l \gg d \right)$ Daher wird das Volumenintegtal zum Längenintegral und die Dichte ist $\rho = \frac{l}{m}$.

$\Rightarrow \Theta = \int_l \, r^2 \rho \, dl$

Dabei ist der Abstand $r$ zur Drehachse ($y$-Achse) $r = r_\perp \rightarrow x = \left[ -\frac{l}{2} .. \frac{l}{2} \right]$

Und somit $\Theta = \int_V r_\perp^2 \rho dV = \int_{-\frac{l}{2}}^{\frac{l}{2}} x^2 \frac{m}{l} \, dx = \left| \frac{1}{3} x^3 \frac{m}{l} \right|_{-\frac{l}{2}}^{\frac{l}{2}} = \frac{m}{3l} \left( \left( \frac{l}{2} \right)^3 - \left(- \frac{l}{2} \right)^3\right) = \frac{m}{3l} 2 \frac{l^3}{8} = \frac{m}{12} l^2$

## Beispiel: Trägheitsmoment einer Kugel

```{figure} Bilder/Kugel.svg
---
width: 300px
name: Kugel-1
---
Modell eines=r homogenen Kugel
 ```

Dichte einer homogenen Kugel: $\rho = \frac{m}{V} = \frac{m}{\frac{4}{3}\pi R^3}$

Abstand zur Rotationsachse (z.B. $z$-Achse) $r_\perp^2 = x^2+y^2 = r^2 \, sin^2(\theta)$

Integration in Kugelkoordinaten: $dxdydz=r^2sin(\theta)d\theta d \phi$

$x = r \, sin(\theta) \, cos (\phi)$
$y = r \, sin(\theta) \, sin(\phi)$
$z = r \, cos (\theta)$

$\Theta = \int dV \rho r_\perp^2 = \frac{3 \,m}{4\pi R^3} \int_0^R \int_0^\pi \int_0^{2\pi} r^2 sin(\theta) r^2 sin^2(\theta) dr\, d\theta \, d\phi = \frac{3 \,m}{4\pi R^3} 2\pi \int_0^Rdr \, r^4 \int_0^\pi sin^3(\theta)\, d\theta = \frac{2}{3}m R^2$


## Übersicht Trägheitsmomente

```{figure} Bilder/TM_Kugel.png
---
width: 150px
name: TM_Kugel
---
$\Theta = \frac{2}{5}mr^2$  
 ```

```{figure} Bilder/TM_Scheibe.png
---
width: 150px
name: TM_Scheibe
---
$\Theta = \frac{1}{2}mr^2$
 ```

```{figure} Bilder/TM_Scheibe_2.png
---
width: 100px
name: TM_Scheibe_2
---
$\Theta = \frac{1}{4}mr^2$
 ```

```{figure} Bilder/TM_Zylinder.png
---
width: 150px
name: TM_Zylinder
---
$\Theta = \frac{1}{2}mr^2$
 ```

```{figure} Bilder/TM_Wuerfel.png
---
width: 200px
name: TM_Wuerfel
---
$\Theta = \frac{1}{6}ma^2$
 ```

```{figure} Bilder/TM_Quader.png
---
width: 200px
name: TM_Quader
---
$\Theta = \frac{1}{12}m \left(b^2 + c^2\right)$
 ```

```{figure} Bilder/TM_Stab.png
---
width: 200px
name: TM_Stab
---
$\Theta = \frac{1}{12}ml^2$
 ```

```{figure} Bilder/TM_Stab_2.png
---
width: 200px
name: TM_Stab_2
---
$\Theta = \frac{1}{3}ml^2$
 ```

```{figure} Bilder/TM_Hohlzylinder.png
---
width: 120px
name: TM_Hohlzylinder
---
$\Theta = \frac{1}{2}m \left(r_a^2 +r_i^2\right)$}
 ```

```{figure} Bilder/TM_Zylinderwand.png
---
width: 150px
name: TM_Zylinderwand
---
$\Theta \approx m r^2$
 ```

```{figure} Bilder/TM_Kegel.png
---
width: 150px
name: TM_Kegel
---
$\Theta = \frac{3}{10}m\,r^2$
 ```

```{figure} Bilder/TM_Zylinder_quer.png
---
width: 150px
name: TM_Zylinder_quer
---
$\Theta = \frac{1}{4}m\,r^2 + \frac{1}{12}m\,l^2$
 ```

<!---
Die Drehbewegung eines starren Körpers hängt nicht nur ab von der Masse, sondern auch von der Massenverteilung. 

Man unterscheidet zwischen

1. dem Bahndrehimpuls, als dem Anteil, der aufgrund einer Bewegung eines massebehafteten Körpers bezüglich eines Bezugspunkts entsteht, sofern der Körper sich nicht direkt auf den Bezugspunkt zu oder von ihm weg bewegt.
1. dem Eigendrehimpuls, als dem Anteil, der nicht Bahndrehimpuls ist. In der Mechanik wird dieser Anteil von der Rotation um den Massenschwerpunkt des Körpers hervorgerufen.
--->