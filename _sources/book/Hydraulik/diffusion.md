# Diffusion

Als Diffusion wird der ohne äußere Einwirkung eintretende Ausgleich von Konzentrationsunterschieden in Stoffgemischen bezeichnet. Dieser Ausgleich entsteht durch statistisch verteilte Eigenbewegungen der Teilchen. Um Diffusion zu verstehen, werden nicht die Bewegungsgleichungen der einzelnen Teilchen betrachtet, sondern die Bewegungen werden statistisch betrachtet. Das Phänomen der Diffusion wird in diesem Skript nur qualitativ diskutiert. 

Die Diffusion führt mit der Zeit zur vollständigen Durchmischung zweier oder mehrerer Stoffe durch die gleichmäßige Verteilung der beweglichen Teilchen und erhöht damit die [Entropie](https://de.wikipedia.org/wiki/Entropie) des Systems. 

Diffusion findet in mikroskopischen Skalen statt (bewirkt aber auf mikroskopische Skalen sichtbare Effekte)

Ursache für die Diffusion ist die statistische Bewegung der Teilchen, sie wird beschrieben durch die Brown'sche Molekularbewegung. 

Die brownsche Molekularbewegung wurde 1827 von Robert Brown entdeckt und später von Einstein theoretisch hergeleitet
Sie beschreibt die größen- und temperaturabhängige zufällige Bewegung von mikroskopisch kleinen Teilchen; je kleiner die Teilchen, desto stärker ist bei einer bestimmten Temperatur ihre Bewegung.
Sie kommt zustande durch Zusammenstöße der Teilchen, die beim Aufprallen Impulse auf die Teilchen übertragen und zur Verschiebung der Teilchen führen. 

Die mittlere quadratische Verschiebung eines Teilchens in eine Raumrichtung ist $\overline{x^2} = 2 D t = \frac{k_B \cdot T}{3 \cdot \pi \cdot \eta \cdot r} \cdot t$

$k_B = $ Boltzmannkonstante $= 1.380649 \cdot 10^{-23} \frac{J}{K}$

$\eta = $ Viskosität der Flüssigkeit / des Gases

$r = $ Teilchenradius

$T = $ absolute Temperatur


```{figure} https://upload.wikimedia.org/wikipedia/commons/5/5a/Brownianmotion_beads_in_water_spim_video.gif
---
width: 60%
alt: brown
name: brown-1
---
Brown'sche Molekularbewegung [Von Jkrieger, Deutschen Krebsforschungszentrum, Arbeitsgruppe B040 Biophysik der Makromoleküle](https://commons.wikimedia.org/w/index.php?curid=12213651)
 ```

<!--Videos/Brownianmotion_beads_in_water_spim_video.gif-->

Dies bedeutet im Einzelnen

* Je höher die Temperatur ist, desto schneller die Teilchenbewegung, damit ist auch die Durchmischung schneller.
* Teilchen in einem viskosem (dickflüssigem) Medium können nicht so schnell diffundieren wie in einem leichtflüssigem Medium. 
* Je größer die Teilchen sind, desto größer ist der Widerstand, den das Medium diesen Teilchen leistet.


<!-- TODO: Video mit statistischer Durchmischung mit Python -->

Der Verlauf der Durchmischung wird durch die Diffusionsgleichung beschrieben. Diese gilt für gelöste Stoffe in Flüssigkeiten und für Gase. Sie kann in eingeschränkter Form sogar auf Festkörper angewendet werden. 

```{figure} Bilder/Diffusion.png
---
width: 60%
alt: diffusion
name: diffusion-1
---
Diffusion durch eine Fläche
 ```

Die Teilchendichte ist definiert $c = \frac{N}{V}$. 

Die Anzahl der Teilchen, die durch $A$ hindurch diffundieren ist $\frac{dN}{dt} = -D \cdot A \frac{dc}{dx}$, wobei $D$ der Diffusionskoeffizient ist. Dieser hängt unter anderem ab von der Temperatur und vom Druck.  Alternativ wird die Schreibweise $J = -D \frac{dc}{dx}$ verwendet, wobei $J = \frac{1}{A}\dot{N}$ die Teilchenstromdichte ist. 

Der [Diffusionskoeffizient](https://de.wikipedia.org/wiki/Diffusionskoeffizient) unterscheidet sich je nach Aggregatzustand stark. In Flüssigkeiten wird der Diffusionskoeffizient für kugelförmige Teilchen mit Radius $r$ durch die Stokes-Einstein-Gleichung beschrieben $D = \frac{k_B \cdot T}{6 \cdot \pi \cdot \eta \cdot r}$. In Gasen ist der Diffusionskoeffizient deutlich größer als in Flüssigkeiten.
In Feststoffen zeigt sich ein ganz anderes Verhalten, die Teilchen müssen zwischen verschiedenen Gitterplätzen springen. Dabei müssen die Teilchen eine Energiebarriere E überwinden, es gilt $D = D_0 e^{-\frac{E}{RT}}$.