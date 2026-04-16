### QUESTION 10


To solve this problem, we follow a sequential chain of derivatives and fundamental physics formulas. Given the parametric equations for the particle's position and its mass ($m = 0.5\text{ kg}$), we can derive all the required vector quantities with respect to time ($t$).

**Initial Position Vector:**
$$\mathbf{r}(t) = (5t^2 - t)\mathbf{\hat{i}} + (2t^3)\mathbf{\hat{j}} + (-3t + 2)\mathbf{\hat{k}}$$

---

### Step 1: The Particle's Velocity ($\mathbf{v}$)

Velocity is the first derivative of the position vector with respect to time: $\mathbf{v}(t) = \frac{d\mathbf{r}}{dt}$.
We differentiate each component individually:
* $v_x = \frac{d}{dt}(5t^2 - t) = 10t - 1$
* $v_y = \frac{d}{dt}(2t^3) = 6t^2$
* $v_z = \frac{d}{dt}(-3t + 2) = -3$

**Answer (Velocity):** $$\mathbf{v}(t) = (10t - 1)\mathbf{\hat{i}} + (6t^2)\mathbf{\hat{j}} - 3\mathbf{\hat{k}}$$

---

### Step 2: The Particle's Momentum ($\mathbf{p}$)

Linear momentum is the product of the particle's mass and its velocity vector: $\mathbf{p}(t) = m\mathbf{v}(t)$.
By substituting $m = 0.5\text{ kg}$:
* $p_x = 0.5(10t - 1) = 5t - 0.5$
* $p_y = 0.5(6t^2) = 3t^2$
* $p_z = 0.5(-3) = -1.5$

**Answer (Momentum):** $$\mathbf{p}(t) = (5t - 0.5)\mathbf{\hat{i}} + (3t^2)\mathbf{\hat{j}} - 1.5\mathbf{\hat{k}}$$

---

### Step 3: The Particle's Acceleration ($\mathbf{a}$)

Acceleration is the first time derivative of the velocity vector: $\mathbf{a}(t) = \frac{d\mathbf{v}}{dt}$.
We differentiate the velocity components found in Step 1:
* $a_x = \frac{d}{dt}(10t - 1) = 10$
* $a_y = \frac{d}{dt}(6t^2) = 12t$
* $a_z = \frac{d}{dt}(-3) = 0$

**Answer (Acceleration):** $$\mathbf{a}(t) = 10\mathbf{\hat{i}} + 12t\mathbf{\hat{j}} + 0\mathbf{\hat{k}}$$

---

### Step 4: The Force Acting on the Particle ($\mathbf{F}$)

According to Newton's Second Law, the net force is the product of mass and acceleration: $\mathbf{F}(t) = m\mathbf{a}(t)$.
By substituting $m = 0.5\text{ kg}$:
* $F_x = 0.5(10) = 5$
* $F_y = 0.5(12t) = 6t$
* $F_z = 0.5(0) = 0$

**Answer (Force):** $$\mathbf{F}(t) = 5\mathbf{\hat{i}} + 6t\mathbf{\hat{j}} + 0\mathbf{\hat{k}}$$

---

### Step 5: The Power Transferred to the Particle ($P$)

Mechanical power is defined as the dot product of the force vector and the velocity vector: $P(t) = \mathbf{F} \cdot \mathbf{v}$.
To find the dot product, we multiply the corresponding components and sum them up:
$$P(t) = (F_x v_x) + (F_y v_y) + (F_z v_z)$$
$$P(t) = [5 \cdot (10t - 1)] + [6t \cdot (6t^2)] + [0 \cdot (-3)]$$
$$P(t) = (50t - 5) + (36t^3) + 0$$

Rearranging into standard polynomial order:

**Answer (Power):**
$$P(t) = 36t^3 + 50t - 5$$
