### QUESTION 11

**Given Parameters:**
* Mass ($m$) = **3 kg**
* Force ($\mathbf{F}(t)$) = $(15t)\mathbf{\hat{i}} + (3t - 12)\mathbf{\hat{j}} - (6t^2)\mathbf{\hat{k}}\text{ N}$
* Initial Velocity ($\mathbf{v}_0$) = $2\mathbf{\hat{i}} + 0\mathbf{\hat{j}} + 1\mathbf{\hat{k}}\text{ m/s}$ *(at $t = 0$)*
* Initial Position ($\mathbf{r}_0$) = $5\mathbf{\hat{i}} + 2\mathbf{\hat{j}} - 3\mathbf{\hat{k}}\text{ m}$ *(at $t = 0$)*

---

### Step 1: Find the Acceleration ($\mathbf{a}$)

According to Newton's Second Law, $\mathbf{a}(t) = \frac{\mathbf{F}(t)}{m}$. We simply divide each component of the force vector by the mass (3 kg):

* $a_x = \frac{15t}{3} = 5t$
* $a_y = \frac{3t - 12}{3} = t - 4$
* $a_z = \frac{-6t^2}{3} = -2t^2$

**Acceleration Vector:**
$$\mathbf{a}(t) = (5t)\mathbf{\hat{i}} + (t - 4)\mathbf{\hat{j}} - (2t^2)\mathbf{\hat{k}}$$

---

### Step 2: Find the Velocity ($\mathbf{v}$)

Velocity is the integral of acceleration with respect to time: $\mathbf{v}(t) = \int \mathbf{a}(t) dt$. 
When integrating, the constants of integration ($C$) correspond to the initial velocity components ($v_{0x}, v_{0y}, v_{0z}$).

**Integrating component by component:**
* **X-direction:** $v_x(t) = \int 5t dt = \frac{5}{2}t^2 + C_x$. 
    Since $v_{0x} = 2$, we get: $v_x(t) = 2.5t^2 + 2$
* **Y-direction:** $v_y(t) = \int (t - 4) dt = \frac{1}{2}t^2 - 4t + C_y$. 
    Since $v_{0y} = 0$, we get: $v_y(t) = 0.5t^2 - 4t$
* **Z-direction:** $v_z(t) = \int -2t^2 dt = -\frac{2}{3}t^3 + C_z$. 
    Since $v_{0z} = 1$, we get: $v_z(t) = -\frac{2}{3}t^3 + 1$

**Answer 1 (Time dependence of Velocity):**
$$\mathbf{v}(t) = (2.5t^2 + 2)\mathbf{\hat{i}} + (0.5t^2 - 4t)\mathbf{\hat{j}} + \left(1 - \frac{2}{3}t^3\right)\mathbf{\hat{k}}$$

---

### Step 3: Find the Position ($\mathbf{r}$)

Position is the integral of velocity with respect to time: $\mathbf{r}(t) = \int \mathbf{v}(t) dt$. 
The new constants of integration correspond to the initial position components ($r_{0x}, r_{0y}, r_{0z}$).

**Integrating component by component:**
* **X-direction:** $x(t) = \int (2.5t^2 + 2) dt = \frac{2.5}{3}t^3 + 2t + C_x$. *(Note: $\frac{2.5}{3} = \frac{5}{6}$)*. 
    Since $r_{0x} = 5$, we get: $x(t) = \frac{5}{6}t^3 + 2t + 5$
* **Y-direction:** $y(t) = \int (0.5t^2 - 4t) dt = \frac{0.5}{3}t^3 - \frac{4}{2}t^2 + C_y$. *(Note: $\frac{0.5}{3} = \frac{1}{6}$)*. 
    Since $r_{0y} = 2$, we get: $y(t) = \frac{1}{6}t^3 - 2t^2 + 2$
* **Z-direction:** $z(t) = \int \left(1 - \frac{2}{3}t^3\right) dt = t - \frac{2}{12}t^4 + C_z$. *(Note: $\frac{2}{12} = \frac{1}{6}$)*. 
    Since $r_{0z} = -3$, we get: $z(t) = -\frac{1}{6}t^4 + t - 3$

**Answer 2 (Time dependence of Position):**
$$\mathbf{r}(t) = \left(\frac{5}{6}t^3 + 2t + 5\right)\mathbf{\hat{i}} + \left(\frac{1}{6}t^3 - 2t^2 + 2\right)\mathbf{\hat{j}} + \left(-\frac{1}{6}t^4 + t - 3\right)\mathbf{\hat{k}}$$

