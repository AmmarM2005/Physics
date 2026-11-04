# JEE Modern Physics — Lesson 2

## Matter Waves & de Broglie Wavelength

---

## 1. The fundamental question

In Lesson 1, we learned that light, which we traditionally considered a wave, can also behave like a particle. Einstein demonstrated this through the photoelectric effect.

Now comes the reverse question:

> Can particles, which we traditionally consider solid objects, also behave like waves?

For example:

- An electron
- A proton
- A neutron
- Even a moving cricket ball!

In 1924, Louis de Broglie proposed that moving matter also has wave-like properties. This is called the **matter-wave hypothesis**.

---

## 2. Deriving the de Broglie equation

From Planck's quantum theory:

$$E = h\nu$$

From special relativity, for a photon:

$$E = pc$$

where $p$ is momentum and $c$ is the speed of light.

For a photon, we also know:

$$c = \nu\lambda$$

Substituting:

$$E = p\nu\lambda$$

But $E = h\nu$, so equating:

$$h\nu = p\nu\lambda$$

Cancelling the frequency:

$$\boxed{\lambda = \frac{h}{p}}$$

De Broglie extended this relationship to material particles. For a non-relativistic particle:

$$\boxed{\lambda = \frac{h}{mv}}$$

This is the **de Broglie wavelength equation**.

| Symbol | Meaning |
| ------ | ------- |
| $\lambda$ | Matter-wave wavelength |
| $h$ | Planck's constant |
| $m$ | Mass |
| $v$ | Velocity |
| $p$ | Momentum |

**Central idea:** greater momentum means smaller wavelength.

---

## 3. Why don't we observe waves in everyday objects?

Consider two objects.

**Electron**

- Mass $= 9.1 \times 10^{-31}\ \text{kg}$
- Matter-wave effects can be experimentally observed.

**Cricket ball**

- Mass $\approx 0.16\ \text{kg}$
- Its de Broglie wavelength is extraordinarily small at ordinary speeds.

Suppose the ball moves at $20\ \text{m/s}$:

$$\lambda = \frac{h}{mv} = \frac{6.626 \times 10^{-34}}{0.16 \times 20}$$

$$\boxed{\lambda = 2.07 \times 10^{-34}\ \text{m}}$$

This wavelength is far too small to observe with ordinary experimental methods. That's why everyday objects appear to behave like classical particles.

---

## 4. Important JEE formula: electron accelerated through a potential difference

This is extremely important for JEE numericals.

Suppose an electron starts from rest and is accelerated through a potential difference $V$. The electrical energy gained becomes kinetic energy:

$$eV = \frac{1}{2}mv^2$$

We know:

$$p = mv$$

Therefore:

$$p = \sqrt{2meV}$$

Using de Broglie's equation:

$$\boxed{\lambda = \frac{h}{\sqrt{2meV}}}$$

For an electron, the convenient formula is:

$$\boxed{\lambda = \frac{12.27}{\sqrt{V}}\ \mathring{A}}$$

where $V$ is in volts.

**Example:** An electron is accelerated through 150 V. Find its wavelength.

$$\lambda = \frac{12.27}{\sqrt{150}}$$

$$\boxed{\lambda = 1.002\ \mathring{A}}$$

Remember this formula.

---

## 5. How does the de Broglie wavelength change?

From $\lambda = \dfrac{h}{mv}$:

| Change | Wavelength |
| ------ | ---------- |
| Mass increases | Decreases |
| Velocity increases | Decreases |
| Momentum increases | Decreases |
| Momentum decreases | Increases |

For an electron accelerated through voltage $V$:

$$\lambda \propto \frac{1}{\sqrt{V}}$$

If the accelerating voltage becomes 4 times:

$$\lambda' = \frac{\lambda}{2}$$

---

## 6. Experimental verification: Davisson–Germer experiment

How do we know de Broglie's hypothesis is correct? It was verified by the **Davisson–Germer experiment**.

The experiment involved:

- Producing a beam of electrons
- Accelerating the electrons through a potential difference
- Directing them towards a nickel crystal
- Measuring the intensity of scattered electrons at different angles

The electrons showed **diffraction patterns**. Diffraction is a characteristic property of waves, so electrons exhibit wave-like behaviour. This experimentally confirmed de Broglie's hypothesis.

---

## 7. JEE practice test

**Q1.** An electron has momentum $p$. Its de Broglie wavelength is:

- (a) $hp$
- (b) $h/p$
- (c) $p/h$
- (d) $h/p^2$

**Q2.** If the velocity of a particle is doubled, keeping mass constant, its wavelength becomes:

- (a) $2\lambda$
- (b) $4\lambda$
- (c) $\lambda/2$
- (d) $\lambda/4$

**Q3.** An electron is accelerated through 100 V. Its de Broglie wavelength is approximately:

- (a) $0.1227\ \mathring{A}$
- (b) $1.227\ \mathring{A}$
- (c) $12.27\ \mathring{A}$
- (d) $122.7\ \mathring{A}$

**Q4.** If the accelerating voltage is increased from $V$ to $9V$, the electron wavelength becomes:

- (a) $3\lambda$
- (b) $\lambda/3$
- (c) $9\lambda$
- (d) $\lambda/9$

**Q5.** Which experiment verified the wave nature of electrons?

- (a) Millikan experiment
- (b) Rutherford experiment
- (c) Davisson–Germer experiment
- (d) Compton experiment

> [!note]- Answers
> 1. (b) $h/p$
> 2. (c) $\lambda/2$
> 3. (b) $1.227\ \mathring{A}$
> 4. (b) $\lambda/3$
> 5. (c) Davisson–Germer experiment

---

## 8. What you should remember

Five takeaways from today's lesson:

1. Matter particles also exhibit wave properties.
2. de Broglie wavelength: $\lambda = \dfrac{h}{p}$
3. Non-relativistic form: $\lambda = \dfrac{h}{mv}$
4. Electron accelerated through voltage $V$: $\lambda = \dfrac{h}{\sqrt{2meV}} = \dfrac{12.27}{\sqrt{V}}\ \mathring{A}$
5. The Davisson–Germer experiment experimentally verified electron diffraction.

**Next lesson:** Lesson 3 — Bohr's Atomic Model. We will derive the radius of electron orbits, velocity and energy levels, and understand why hydrogen produces a line spectrum.

**Self-check:**

1. Can you explain why increasing momentum decreases wavelength?
2. Can you derive the electron accelerating-voltage formula without looking?
3. Are you ready to move to Bohr's atomic model after attempting the test?
