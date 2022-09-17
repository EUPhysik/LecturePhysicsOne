# Gerader zentraler elastischer Stoß

```{figure} Bilder/stoss-5.svg
---
width: 700px
name: stoss-5
---
Gerader zentraler elastischer Stoß.
 ```

Der gerade zentrale Stoss ist der einfachste mögliche Stossprozess. Es findet kein Impulsübertrag in $\perp$ Richtung statt, so dass es sich hier um ein eindimensionales Problem handelt. 

Zusammenhänge zwischen $\vec{v}_1 , \,  \vec{v}_2$ und $\vec{v}^\prime_1 , \,  \vec{v}^\prime_2$ ergeben sich durch die Betrachtung von Energie- und Impulserhaltung. 

**Energieerhaltung**

$E_{vor} = E_{nach}$

$\frac{1}{2} m_1 v_1^2 + \frac{1}{2} m_2 v_1^2 
= \frac{1}{2} m_1 \left(v^\prime_1 \right)^2 + \frac{1}{2} m_2 \left(v^\prime_2 \right)^2
\Leftrightarrow 
m_1 v_1^2 + m_2 v_1^2 
= m_1 \left(v^\prime_1 \right)^2 + m_2 \left(v^\prime_2 \right)^2
$

$\Leftrightarrow 
m_1 v_1^2 - m_1\left(v^\prime_1 \right)^2 =  m_2 \left(v^\prime_2 \right)^2 - m_2 v_2^2
\Leftrightarrow 
m_1 \left( v_1^2 - \left(v^\prime_1 \right)^2 \right)
=  m_2 \left( \left(v^\prime_2 \right)^2 - v_2^2\right)$

$\Leftrightarrow 
m_1 \left(v_1 - v_1^\prime\right)\left(v_1 + v_1^\prime\right)
= m_2 \left(\left(v_2^\prime\right) - v_2\right)\left(\left(v_2^\prime\right) + v_2\right)$ </t> <span style="color:blue"> (1)</span>

**Impulserhaltung**

$p_{vor} = p_{nach}$

$m_1 v_1 + m_2v_2 = m_1 v_1^\prime + m_2 v_2^\prime
\Leftrightarrow m_1 \left( v_1 - v_1^\prime \right)
= \Leftrightarrow m_2 \left(v_2^\prime - v_2\right)$ </t> <span style="color:green"> (2)</span>

Die beiden hierausgewonnen Gleichungen <span style="color:blue"> (1)</span> und <span style="color:green"> (2)</span> werden auf jeder Seite dividiert

<span style="color:blue"> (1)</span> / <span style="color:green"> (2)</span>
$\Rightarrow v_1 + v_1^\prime = v_2^\prime + v_2
\Leftrightarrow v_1 - v_2 = v_2^\prime - v_1^\prime
\Leftrightarrow v_2^\prime - v_1 = v_2 + v_1^\prime$
</t> <span style="color:orange"> (3)</span>

Wird Gleichung <span style="color:orange"> (3)</span> in Gleichung <span style="color:green"> (2)</span> eingesetzt, ergibt sich

$m_1 \left( v_1 - v_1^\prime \right) = m_2 \left( v_1 - v_2 + v_1^\prime - v_2 \right)
\Leftrightarrow m_1 v_1 - m_1 v_1^\prime = m_2 v_1 - 2 m_2 v_2 + m_2 v_1^\prime$

$\Leftrightarrow m_1 v_1 -m_2 v_1 + 2 m_2 v_2 = m_2 v_1^\prime + m_1 v_1^\prime = v_1^\prime \left( m_1 + m_2\right)$

$\Leftrightarrow 
v_1^\prime = \frac{m_1 v_1 -m_2 v_1 + 2 m_2 v_2}{m_1 + m_2} $

$
\Leftrightarrow v_1^\prime = \frac{m_1 v_1 -m_2 \left(v_1 - 2 v_2 \right)}{m_1 + m_2} 
$

Ebenfalls ergibt sich aus <span style="color:orange"> (3)</span> in <span style="color:green"> (2)</span>  mit 
$v_1^\prime = v_2^\prime -v_1 + v_2$

$m_1 \left( v_1 - \left( v_2^\prime -v_1 + v_2 \right) \right) = m_2 \left( v_2^\prime -v_2\right)
\Leftrightarrow m_1 v_1 - m_1 v_2^\prime + m_1 v_1 -m_1 v_2 = m_2 v_2^\prime - m_2 v_2$

$\Leftrightarrow 2 m_1 v_1  - m_1 v_2 + m_2 v_2 = v_2^\prime \left( (m_1 + m)2 \right)
\Leftrightarrow m_1 \left( 2 v_1  - v_2 \right) + m_2 v_2 = v_2^\prime \left((m_1 + m)2 \right)$

$\Leftrightarrow v_2^\prime = \frac{m_1 \left(2 v_1 - v_2 \right) + (m_2 v_2)}{m_1 + m_2}$