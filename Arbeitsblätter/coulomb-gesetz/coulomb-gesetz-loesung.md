# Musterlösung: Das Coulomb-Gesetz anwenden

Musterlösung zum [Arbeitsblatt](coulomb-gesetz-uebung.md). Grundlage ist der Text [Das Coulomb-Gesetz: Die Kraft zwischen geladenen Körpern](coulomb-gesetz-grundlagen.md).

Gerechnet wird mit $\dfrac{1}{4\pi\varepsilon_0} \approx 8{,}99 \cdot 10^{9}\ \dfrac{\text{N}\,\text{m}^2}{\text{C}^2}$. Zwischenergebnisse sind gerundet.

---

## Aufgabe 1: Das Elektron auf der Kreisbahn

**a) Kraft $F$.**

$$F = \frac{1}{4\pi\varepsilon_0} \cdot \frac{2e \cdot e}{r^2} = 8{,}99 \cdot 10^{9}\ \frac{\text{N}\,\text{m}^2}{\text{C}^2} \cdot \frac{2 \cdot (1{,}60 \cdot 10^{-19}\ \text{C})^2}{(2{,}65 \cdot 10^{-11}\ \text{m})^2} \approx 6{,}55 \cdot 10^{-7}\ \text{N}$$

Kern (positiv) und Elektron (negativ) **ziehen sich** mit etwa $6{,}6 \cdot 10^{-7}$ N **an**.

**b)** Aus $F = m_\text{e} \cdot \dfrac{v^2}{r}$ folgt

$$v = \sqrt{\frac{F \cdot r}{m_\text{e}}} = \sqrt{\frac{6{,}55 \cdot 10^{-7}\ \text{N} \cdot 2{,}65 \cdot 10^{-11}\ \text{m}}{9{,}11 \cdot 10^{-31}\ \text{kg}}} \approx 4{,}37 \cdot 10^{6}\ \frac{\text{m}}{\text{s}}$$

Das sind etwa 1,5 % der Lichtgeschwindigkeit.

**c) Abstand $r$.** Gleichsetzen und einmal durch $r$ kürzen:

$$\frac{1}{4\pi\varepsilon_0} \cdot \frac{2e^2}{r^2} = m_\text{e} \cdot \frac{v^2}{r} \quad\Rightarrow\quad r = \frac{1}{4\pi\varepsilon_0} \cdot \frac{2e^2}{m_\text{e} \cdot v^2}$$

Mit $v = 2{,}18 \cdot 10^{6}\ \dfrac{\text{m}}{\text{s}}$:

$$r = 8{,}99 \cdot 10^{9}\ \frac{\text{N}\,\text{m}^2}{\text{C}^2} \cdot \frac{2 \cdot (1{,}60 \cdot 10^{-19}\ \text{C})^2}{9{,}11 \cdot 10^{-31}\ \text{kg} \cdot (2{,}18 \cdot 10^{6}\ \frac{\text{m}}{\text{s}})^2} \approx 1{,}06 \cdot 10^{-10}\ \text{m}$$

Der Radius ist **viermal** so groß. Begründung ohne Zahlen: Nach der umgestellten Formel gilt $r \sim \dfrac{1}{v^2}$. Halbe Geschwindigkeit bedeutet also den Faktor $2^2 = 4$ beim Radius.

**d) Ladung $Q$.**

$$F_\text{Z} = m_\text{e} \cdot \frac{v^2}{r} = 9{,}11 \cdot 10^{-31}\ \text{kg} \cdot \frac{(6{,}57 \cdot 10^{6}\ \frac{\text{m}}{\text{s}})^2}{1{,}76 \cdot 10^{-11}\ \text{m}} \approx 2{,}23 \cdot 10^{-6}\ \text{N}$$

Die Coulomb-Kraft ist genauso groß. Umgestellt nach der Kernladung:

$$Q_\text{Kern} = \frac{4\pi\varepsilon_0 \cdot F \cdot r^2}{e} = \frac{2{,}23 \cdot 10^{-6}\ \text{N} \cdot (1{,}76 \cdot 10^{-11}\ \text{m})^2}{8{,}99 \cdot 10^{9}\ \frac{\text{N}\,\text{m}^2}{\text{C}^2} \cdot 1{,}60 \cdot 10^{-19}\ \text{C}} \approx 4{,}8 \cdot 10^{-19}\ \text{C} = 3e$$

Der Kern hat **3 Protonen**. Es handelt sich um **Lithium**, genauer um das Ion $\text{Li}^{2+}$.

---

## Aufgabe 2: Protonen im Atomkern und die Gewichtskraft

**a) Kraft $F$.**

$$F_\text{C} = \frac{1}{4\pi\varepsilon_0} \cdot \frac{e^2}{r^2} = 8{,}99 \cdot 10^{9}\ \frac{\text{N}\,\text{m}^2}{\text{C}^2} \cdot \frac{(1{,}60 \cdot 10^{-19}\ \text{C})^2}{(1{,}0 \cdot 10^{-15}\ \text{m})^2} \approx 230\ \text{N}$$

Eine gleich große Gewichtskraft hat die Masse $m = \dfrac{F}{g} = \dfrac{230\ \text{N}}{9{,}81\ \frac{\text{m}}{\text{s}^2}} \approx 23\ \text{kg}$. Zwei winzige Protonen stoßen sich also so stark ab, wie ein Kind von der Erde angezogen wird.

**b)**

$$F_\text{G} = G \cdot \frac{m_\text{p}^2}{r^2} = 6{,}67 \cdot 10^{-11}\ \frac{\text{N}\,\text{m}^2}{\text{kg}^2} \cdot \frac{(1{,}67 \cdot 10^{-27}\ \text{kg})^2}{(1{,}0 \cdot 10^{-15}\ \text{m})^2} \approx 1{,}9 \cdot 10^{-34}\ \text{N}$$

$$\frac{F_\text{C}}{F_\text{G}} \approx \frac{230\ \text{N}}{1{,}9 \cdot 10^{-34}\ \text{N}} \approx 1{,}2 \cdot 10^{36}$$

Die Gravitation ist völlig vernachlässigbar. Weil beide Kräfte mit $\dfrac{1}{r^2}$ abnehmen, gilt das Verhältnis bei jedem Abstand.

**c)** Die Abstoßung müsste den Kern auseinandertreiben, und die Gravitation kann sie nicht ausgleichen. Weil der Kern trotzdem stabil ist, muss es eine **weitere, anziehende Kraft** zwischen den Kernbausteinen geben, die auf diese Entfernung noch stärker ist als die elektrische Kraft. Das ist die **starke Kernkraft**. Sie wirkt nur auf sehr kurze Entfernungen (etwa $10^{-15}$ m), deshalb merkt man sie außerhalb des Kerns nicht.

**d) Abstand $r$.** Gewichtskraft des Protons: $m_\text{p} \cdot g = 1{,}67 \cdot 10^{-27}\ \text{kg} \cdot 9{,}81\ \frac{\text{m}}{\text{s}^2} \approx 1{,}64 \cdot 10^{-26}\ \text{N}$. Mit $|Q| = e$:

$$r = \sqrt{\frac{1}{4\pi\varepsilon_0} \cdot \frac{e^2}{m_\text{p} \cdot g}} = \sqrt{8{,}99 \cdot 10^{9}\ \frac{\text{N}\,\text{m}^2}{\text{C}^2} \cdot \frac{(1{,}60 \cdot 10^{-19}\ \text{C})^2}{1{,}64 \cdot 10^{-26}\ \text{N}}} \approx 0{,}12\ \text{m}$$

Das obere Proton schwebt etwa **12 cm** über dem unteren. Eine einzige Elementarladung reicht also, um in 12 cm Abstand die Anziehung der ganzen Erde auszugleichen.

**e) Ladung $Q$.**

$$|Q| = \frac{4\pi\varepsilon_0 \cdot m_\text{p} \cdot g \cdot r^2}{e} = \frac{1{,}64 \cdot 10^{-26}\ \text{N} \cdot (1{,}0\ \text{m})^2}{8{,}99 \cdot 10^{9}\ \frac{\text{N}\,\text{m}^2}{\text{C}^2} \cdot 1{,}60 \cdot 10^{-19}\ \text{C}} \approx 1{,}1 \cdot 10^{-17}\ \text{C}$$

Die Kugel muss **positiv** geladen sein, damit sie das Proton abstößt. Das entspricht $\dfrac{1{,}1 \cdot 10^{-17}\ \text{C}}{1{,}60 \cdot 10^{-19}\ \text{C}} \approx 71$ Elementarladungen.

---

## Aufgabe 3: Tonerteilchen im Laserdrucker

**a) Kraft $F$.**

$$F = \frac{1}{4\pi\varepsilon_0} \cdot \frac{|Q_\text{T}| \cdot |Q_\text{B}|}{r^2} = 8{,}99 \cdot 10^{9}\ \frac{\text{N}\,\text{m}^2}{\text{C}^2} \cdot \frac{(4{,}0 \cdot 10^{-15}\ \text{C})^2}{(1{,}0 \cdot 10^{-5}\ \text{m})^2} \approx 1{,}4 \cdot 10^{-9}\ \text{N}$$

Die Kraft ist anziehend (ungleichnamige Ladungen).

Gewichtskraft: $F_\text{G} = m \cdot g = 2{,}0 \cdot 10^{-13}\ \text{kg} \cdot 9{,}81\ \frac{\text{m}}{\text{s}^2} \approx 2{,}0 \cdot 10^{-12}\ \text{N}$. Die Coulomb-Kraft ist etwa **730-mal** so groß. Deshalb fällt der Toner nicht von der Trommel, auch wenn die Stelle unten ist.

Überschüssige Elektronen: $\dfrac{4{,}0 \cdot 10^{-15}\ \text{C}}{1{,}60 \cdot 10^{-19}\ \text{C}} = 25\,000$.

**b) Abstand $r$.** Grenzfall: Coulomb-Kraft gleich Gewichtskraft.

$$r = \sqrt{\frac{1}{4\pi\varepsilon_0} \cdot \frac{|Q_\text{T}| \cdot |Q_\text{B}|}{m \cdot g}} = \sqrt{8{,}99 \cdot 10^{9}\ \frac{\text{N}\,\text{m}^2}{\text{C}^2} \cdot \frac{(4{,}0 \cdot 10^{-15}\ \text{C})^2}{2{,}0 \cdot 10^{-12}\ \text{N}}} \approx 2{,}7 \cdot 10^{-4}\ \text{m}$$

Die Trommelstelle muss auf weniger als etwa **0,27 mm** herankommen. Tatsächlich ist der Spalt zwischen Walze und Trommel in Druckern nur wenige Zehntelmillimeter breit.

**c) Ladung $Q$.** Die Kraft des Papiers muss mindestens $1{,}4 \cdot 10^{-9}$ N betragen:

$$|Q_\text{P}| = \frac{4\pi\varepsilon_0 \cdot F \cdot r^2}{|Q_\text{T}|} = \frac{1{,}44 \cdot 10^{-9}\ \text{N} \cdot (2{,}0 \cdot 10^{-5}\ \text{m})^2}{8{,}99 \cdot 10^{9}\ \frac{\text{N}\,\text{m}^2}{\text{C}^2} \cdot 4{,}0 \cdot 10^{-15}\ \text{C}} \approx 1{,}6 \cdot 10^{-14}\ \text{C}$$

$Q_\text{P}$ ist **positiv**, damit es den negativen Toner anzieht. Faktor 4: Der Abstand ist doppelt so groß wie in a), die Kraft wäre bei gleicher Ladung also nur ein Viertel so groß. Damit sie trotzdem gleich groß bleibt, muss die Ladung viermal so groß sein.

---

## Abschluss

| Aufgabe | Kraft $F$ | Abstand $r$ | Ladung $Q$ |
|---|---|---|---|
| 1 | $F = \dfrac{1}{4\pi\varepsilon_0} \cdot \dfrac{2e^2}{r^2}$ | $r = \dfrac{1}{4\pi\varepsilon_0} \cdot \dfrac{2e^2}{m_\text{e} v^2}$ | $Q_\text{Kern} = \dfrac{4\pi\varepsilon_0 \cdot F \cdot r^2}{e}$ |
| 2 | $F = \dfrac{1}{4\pi\varepsilon_0} \cdot \dfrac{e^2}{r^2}$ | $r = \sqrt{\dfrac{1}{4\pi\varepsilon_0} \cdot \dfrac{e^2}{m_\text{p} g}}$ | $Q = \dfrac{4\pi\varepsilon_0 \cdot m_\text{p} g \cdot r^2}{e}$ |
| 3 | $F = \dfrac{1}{4\pi\varepsilon_0} \cdot \dfrac{Q_\text{T} Q_\text{B}}{r^2}$ (Beträge) | $r = \sqrt{\dfrac{1}{4\pi\varepsilon_0} \cdot \dfrac{Q_\text{T} Q_\text{B}}{m g}}$ (Beträge) | $Q_\text{P} = \dfrac{4\pi\varepsilon_0 \cdot F \cdot r^2}{Q_\text{T}}$ (Beträge) |

Gemeinsame Aussage: Verdoppelt man den Abstand, sinkt die Kraft auf ein **Viertel**. Damit die Kraft gleich bleibt, muss man eine Ladung **vervierfachen** (oder beide Ladungen verdoppeln).

---

## Hinweis für die Lehrkraft

- Jede Aufgabe verlangt einmal $F$, einmal $r$ und einmal $Q$. Die Teilaufgaben sind auf dem Arbeitsblatt entsprechend gekennzeichnet.
- In Aufgabe 1 c) kürzt sich ein $r$ heraus, deshalb ist dort keine Wurzel nötig. In Aufgabe 2 d) und 3 b) muss die Wurzel gezogen werden.
- Aufgabe 2 a) bis c) entspricht der klassischen Aufgabe zu den Protonen im Kern. Die Teile d) und e) verbinden sie mit der Gewichtskraft.
- Das Modell in Aufgabe 3 (Trommel und Papier als Punktladungen) ist stark vereinfacht. In realen Druckern ist die Trommel meist negativ geladen und wird an den Bildstellen vom Laser entladen. Für das Arbeitsblatt genügt das Modell aus dem Grundlagentext.
- Die Knobelaufgaben in der [Vertiefung](coulomb-gesetz-vertiefung.md) eignen sich für schnelle Gruppen.
