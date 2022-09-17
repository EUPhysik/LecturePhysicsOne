# Grundlagen der Thermodynamik

Die Thermodynamik beschreibt die Zustände und deren Änderung infolge der Wechselwirkung mit der Umgebung von kompliziert zusammengesetzten makroskopischen Systemen durch eine geringe Anzahl makroskopischer Variablen, wie z. B. Druck oder Temperatur, sowie durch thermodynamische Potentiale. 

Eine Betrachtung auf mikropischer Ebene erfolgt durch statistische Mechanik und Quantenmechanik, diese sind nicht Bestandteil der Vorlesung.

Im Rahmen dieser Vorlesung werden thermodynamische Betrachtungen mit Hilfe von Zustandsgleichunen umgesetzt.

Mit Zustandsgleichungen ist die Beschreibung von Gleichgewichtszuständen und Gleichgewichtsbedingungen möglich. 
Thermodynamische Prozesse werden hier also nicht während der dynamischen Phase betrachtet, vielmehr werden Anfangs- und Endzustand miteinander verglichen.

Wichtige Grundannahme für eine derartige Betrachtungsweise ist:

Die Änderung einer Zustandsgröße hängt nicht von der Art der Prozessführung ab!

Zu Beginn und Ende eines Prozesses werden Zustandsgrößen betrachtet. Dabei unterscheidet man zwischen direkt messbaren und abgeleiteten Größen.

Direkt messbaren thermische Zustandsgrößen sind
* Druck
* Volumen
* Temperatur

Abgeleitete kalorische Zustandsgrößen sind
* innere Energie
* Enthalpie
* Entropie

Bleiben die Zustandsgrößen zeitlich konstant befindet sich das System in einem Gleichgewichtszustand.

Darüber hinaus gibt es noch die Prozessgrößen. Diese beschreiben den Prozess der Zustandsänderung.
Im Gegensatz zu den Zustandsgrößen sind diese von dem Verlauf des Prozesses abhängig, sie beschreiben, wie ein Zustand in einen anderen Zustand übergeht.
Eine Prozessgröße tritt demnach ausschließlich bei Zustandsänderungen auf.

Prozessgrößen sind
* Wärme
* Arbeit

Die grundlegenden Annahmen, auf denen die Gesetze der Wärmelehre basieren, werden als **Hauptsätze der Thermodynamik** bezeichnet. Sie werden im Folgenden beschrieben.

## Nullter Hauptsatz

Im thermodynamischen Gleichgewicht haben alle Bestandteile eines Systems dieselbe Temperatur.

Dies bedeutet:

Wenn das System A mit dem System B in thermischem Gleichgewicht steht und das System B auch mit System C im thermischen Gleichgewicht steht, folgt daraus zwingend, daß auch die beiden Systeme A und C miteinander im thermischen Gleichgewicht stehen müssen.

```{figure} Bilder/0ter_h.svg
---
width: 100%
alt: Nullter Hauptsatz der Thermodynamik
name: 0hs
---
Nullter Hauptsatz der Thermodynamik
 ```

## Erster Hauptsatz

Der erste Hauptsatz ist der Energieerhaltungssatz. 

„Die Energie in einem abgeschlossenen System ist konstant“

Eine Änderung der inneren Energie $\Delta U$ kann durch Wärmezufuhr $Q$ und/oder Arbeitsverrichtung $W$ erfolgen.

Innerhalb des Systems können die verschiedenen Energieformen ineinander umgewandelt werden. 

Dabei gibt es zwei Möglichkeiten für thermodynamische Systeme:

* Geschlossenes System: Ein abgeschlossenes thermodynamisches System wechselwirkt nicht mit seiner Umgebung
* Offenes System: Bei offenen Systemen kann sowohl Energie als auch Materie die Systemgrenze passieren

Bei einer exothermen Reaktion nimmt die Enthalpie $H$ des Systems ab, $\Delta H$ ist negativ.
Bei einer endotherm  Reaktion ist $\Delta H$  positiv.

## Zweiter Hauptsatz

Der Zweite Hauptsatz der Thermodynamik trifft Aussagen über die Richtung von Prozessen und das Prinzip der Irreversibilität.

„Es gibt keine Zustandsänderung, deren einziges Ergebnis die Übertragung von Wärme von einem Körper niederer auf einen Körper höherer Temperatur ist.“

Dies bedeutet im Einzelnen:
* Wärme kann nicht von selbst von einem Körper niedriger Temperatur auf einen Körper höherer Temperatur übergehen.
* Alle spontan (in eine Richtung) ablaufenden Prozesse sind irreversibel.
* Alle Prozesse, bei denen Reibung stattfindet, sind irreversibel.
* In einem geschlossenen adiabaten System kann die Entropie nicht geringer werden.
* Das Gleichgewicht isolierter thermodynamischer Systeme ist durch ein Maximalprinzip der Entropie ausgezeichnet.

## Dritter Hauptsatz

Der absolute Temperaturnullpunkt lässt sich nicht erreichen 

Ein Beweis des dritten Hauptsatzen erfolgte durch quantenmechanische Betrachtungen ([Nernst-Theorem](https://de.wikipedia.org/wiki/Dritter_Hauptsatz_der_Thermodynamik)).

Die Entropie eines geschlossenen Systems geht dabei für $T \rightarrow 0$ gegen eine von thermodynamischen Parametern unabhängige Konstante.

Für ein geschlossenes System gilt: $dS = \frac{d Q}{T} + \frac{d W_{diss}}{T}$

$W_{diss}$ ist dabei die Reibungsarbeit, diese ist immer positiv.

Daraus folgt: 
„In einem geschlossenen adiabaten System kann die Entropie nicht abnehmen, sie nimmt in der Regel zu. Nur bei reversiblen Prozessen bleibt sie konstant“

Dies bedeutet:
* Reversible Prozesse sind nicht mit einer Erhöhung der Gesamtentropie verbunden und laufen daher auch nicht spontan ab
* Spontan ablaufende Prozesse sind irreversibel und erhöhen die Entropie