

### Step 1: The Core Logic
The total electric potential at the center is simply the algebraic sum of the potentials created by each of the four individual charges. 

The formula for the electric potential of a single point charge is:
$$V = k\frac{q}{r}$$
Where:
* **$k$** = Coulomb's constant ($9 \times 10^9\text{ N}\cdot\text{m}^2/\text{C}^2$)
* **$q$** = The value of the charge (with its + or - sign)
* **$r$** = The distance from the charge to the center

---

### Step 2: Find the Distance ($r$)
The square has a side length of **1.0 m**. The distance from any corner to the exact center is the same for all four charges.
* The full diagonal of a square is calculated as $\text{side} \times \sqrt{2}$. So, the diagonal is $\sqrt{2}\text{ m}$.
* The center is exactly half of the diagonal:
$$r = \frac{\sqrt{2}}{2} = \frac{1}{\sqrt{2}}\text{ m}$$

---

### Step 3: Calculate Total Potential ($V_{\text{total}}$)
Since the total potential is the sum of all individual potentials, we can write:
$$V_{\text{total}} = V_1 + V_2 + V_3 + V_4$$

Because both $k$ and $r$ are identical for all four charges, we can factor them out to make the math incredibly easy:
$$V_{\text{total}} = \frac{k}{r} (q_1 + q_2 + q_3 + q_4)$$

Now, plug in the charge values with their respective signs (+1, -2, +3, -4):
$$V_{\text{total}} = \frac{k}{r} (1 - 2 + 3 - 4)$$
$$V_{\text{total}} = \frac{k}{r} (-2)$$

---

### Step 4: Final Calculation
Now, just substitute the known values of $k$ and $r$ into our simplified equation:
* $k = 9 \times 10^9$
* $r = \frac{1}{\sqrt{2}}$
* Sum of charges = $-2$

$$V_{\text{total}} = \frac{9 \times 10^9}{1/\sqrt{2}} \times (-2)$$

The $\sqrt{2}$ in the denominator moves to the numerator:
$$V_{\text{total}} = -18\sqrt{2} \times 10^9\text{ V}$$

If your professor prefers the answer in standard decimal format (using $\sqrt{2} \approx 1.414$):
$$V_{\text{total}} \approx -18 \times 1.414 \times 10^9$$
$$V_{\text{total}} \approx -25.45 \times 10^9\text{ V}$$

**Final Answer:**
The total electric potential at the center of the square is **$-25.45 \times 10^9\text{ Volts}$**.
