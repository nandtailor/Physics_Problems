# Math & Logic Problems: Step-by-Step Solutions

## 1. Vector Algebra
**Question:** Given two vectors in 3D space: $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$. Calculate: magnitude, dot product, cross product, and angle.

**Solution:**
* **a) Magnitudes:**
  $|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{14} \approx 3.74$
  $|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{21} \approx 4.58$
* **b) Dot Product ($\vec{a} \cdot \vec{b}$):**
  $\vec{a} \cdot \vec{b} = (2 \times 4) + (1 \times -2) + (-3 \times 1) = 8 - 2 - 3 = 3$
* **c) Cross Product ($\vec{a} \times \vec{b}$):**
  $\vec{a} \times \vec{b} = [-5, -14, -8]$ (Solved using the determinant method)
* **d) Angle ($\theta$):**
  $\cos \theta = \frac{3}{\sqrt{14} \times \sqrt{21}} \approx 0.175$
  $\theta = \arccos(0.175) \approx 79.92^\circ$

---

## 2. Systems of Equations
**Question:** Find $x$ and $y$ for: $2x + 3y = 12$ and $x - y = 1$.

**Solution (Substitution Method):**
1. From the second equation: $x = 1 + y$
2. Put this into the first equation:
   $$2(1 + y) + 3y = 12$$
   $$2 + 2y + 3y = 12$$
   $$5y = 10 \implies y = 2$$
3. Find $x$: 
   $$x = 1 + 2 \implies x = 3$$
**Answer:** $x = 3$, $y = 2$

---

## 3. Proportionality (Gravitation)
**Question:** $F = \frac{G m_1 m_2}{r^2}$. What happens if $r$ is doubled and both masses are halved?

**Solution:**
1. **Masses halved:** $(\frac{1}{2} m_1) \times (\frac{1}{2} m_2) = \frac{1}{4}$ of the original mass product. Force decreases by a factor of $4$.
2. **Distance doubled:** $(2r)^2 = 4r^2$. Since it's in the denominator, force decreases by another factor of $4$.
3. **Total Change:** $\frac{1}{4} \times \frac{1}{4} = \frac{1}{16}$
**Answer:** The force becomes $\frac{1}{16}$ of its original value (16 times weaker).

---

## 4. Rearranging Formulas
**Question:** Rearrange $T = 2\pi \sqrt{\frac{L}{g}}$ to solve for $g$.

**Solution:**
1. Move $2\pi$: $\frac{T}{2\pi} = \sqrt{\frac{L}{g}}$
2. Square both sides to remove the root: $\frac{T^2}{4\pi^2} = \frac{L}{g}$
3. Cross-multiply: $g \times T^2 = L \times 4\pi^2$
4. Isolate $g$: 
   $$g = \frac{4\pi^2 L}{T^2}$$

---

## 5. Trigonometry
**Question:** Vector $\vec{A}$ has magnitude $15$ and angle $\theta = 60^\circ$. Find horizontal and vertical components.

**Solution:**
* **Horizontal Component ($A_x$):**
  $$A_x = A \cos \theta = 15 \times \cos(60^\circ) = 15 \times 0.5 = 7.5$$
* **Vertical Component ($A_y$):**
  $$A_y = A \sin \theta = 15 \times \sin(60^\circ) = 15 \times \frac{\sqrt{3}}{2} \approx 12.99$$

---

## 6. Function Analysis
**Question:** Find local maxima or minima for $f(x) = 3x^2 - 12x + 7$.

**Solution:**
1. Find the first derivative: $f'(x) = 6x - 12$
2. Set to $0$ to find the critical point: 
   $$6x - 12 = 0 \implies x = 2$$
3. Find the $y$-value at $x = 2$: 
   $$f(2) = 3(2)^2 - 12(2) + 7 = 12 - 24 + 7 = -5$$
4. **Conclusion:** Since the curve is a "smile" (positive $x^2$ coefficient), $(2, -5)$ is a **Local Minima**.

---

## 7. Logic & Series (Bicycle and Fly)
**Question:** Bicycle is $10$m away, moving at $1$ m/s. Fly flies back and forth at $2$ m/s until crushed. Total distance?

**Solution:**
1. **Time taken:** The bicycle travels $10$ meters at $1$ m/s.
   $$Time = \frac{Distance}{Speed} = \frac{10}{1} = 10 \text{ seconds}$$
2. **Fly's distance:** The fly flies continuously for those $10$ seconds at $2$ m/s.
   $$Distance = Speed \times Time = 2 \times 10 = 20 \text{ meters}$$
**Answer:** The fly travels exactly $20$ meters.

---

## 8. Definite Integrals
**Question:** Area under $f(x) = \sin(x)$ from $x = 0$ to $x = \pi$.

**Solution:**
1. Set up the integral: $\int_{0}^{\pi} \sin(x) \, dx$
2. Integrate: The anti-derivative of $\sin(x)$ is $-\cos(x)$.
3. Apply limits: $[-\cos(x)]_{0}^{\pi} = (-\cos(\pi)) - (-\cos(0))$
4. Calculate: $(-(-1)) - (-(1)) = 1 + 1 = 2$
**Answer:** The area is exactly $2$ square units.

---

## 9. Optimization Problem
**Question:** Dimensions of the maximum area rectangle under $y = 3 - x^2$ in the first quadrant.

**Solution:**
1. Area formula: $A = x \cdot y$
2. Substitute $y$: $A = x(3 - x^2) = 3x - x^3$
3. Find derivative and set to $0$:
   $$A'(x) = 3 - 3x^2 = 0 \implies 3x^2 = 3 \implies x^2 = 1$$
   So, $x = 1$ (width).
4. Find $y$: $y = 3 - (1)^2 = 2$ (height).
**Answer:** Width = $1$ unit, Height = $2$ units.

---

## 10. Infinite Series (Ant's Journey)
**Question:** Ant moves: 1m East, 1/2m North, 1/3m West, 1/4m South, 1/5m East... Find final position.

**Solution:**
* **X-axis (East/West):** Moves are $1, -\frac{1}{3}, \frac{1}{5}, -\frac{1}{7} \dots$
  This is the Leibniz series for Pi. 
  $$x = \frac{\pi}{4}$$
* **Y-axis (North/South):** Moves are $\frac{1}{2}, -\frac{1}{4}, \frac{1}{6}, -\frac{1}{8} \dots$
  Factoring out $\frac{1}{2}$, we get the alternating harmonic series $\ln(2)$.
  $$y = \frac{\ln(2)}{2}$$
**Answer:** Final Position is $(x, y) = \left( \frac{\pi}{4}, \frac{\ln(2)}{2} \right)$.
