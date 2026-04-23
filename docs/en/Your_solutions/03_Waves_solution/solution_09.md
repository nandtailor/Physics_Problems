---

### 1. General Solution and Classification of Cases

The system is described by the second-order linear differential equation for a damped harmonic oscillator:
$$m\frac{d^2x}{dt^2} + b\frac{dx}{dt} + kx = 0$$

Where:
* **$m$** = Mass of the oscillator
* **$k$** = Spring constant (restoring force factor)
* **$b$** = Damping coefficient (frictional/drag force factor)

The behavior of the system is determined by the roots of its characteristic equation, which depends on the relationship between the damping parameter ($b$) and the critical damping threshold ($4mk$). There are three distinct cases:

**Case 1: Underdamped ($b^2 < 4mk$)**
* **Physical Behavior:** The damping is weak. The system oscillates with a gradually decreasing amplitude over time.
* **General Solution:** $$x(t) = e^{-\frac{bt}{2m}} \left( A \cos(\omega_d t) + B \sin(\omega_d t) \right)$$
    *(Where $\omega_d$ is the damped angular frequency).*

**Case 2: Critically Damped ($b^2 = 4mk$)**
* **Physical Behavior:** The damping is perfectly balanced. The system returns to its equilibrium position as quickly as possible without oscillating. (This is how car suspensions are ideally designed).
* **General Solution:** $$x(t) = (A + Bt)e^{-\frac{bt}{2m}}$$

**Case 3: Overdamped ($b^2 > 4mk$)**
* **Physical Behavior:** The damping is very strong (e.g., moving through thick oil). The system does not oscillate, but it returns to equilibrium much slower than in the critically damped case.
* **General Solution:** $$x(t) = A e^{r_1 t} + B e^{r_2 t}$$

---

### 2. Numerical Solution via RK4 (Runge-Kutta 4th Order)

To solve this numerically, we must reduce the second-order differential equation into a system of two first-order differential equations:
1.  **Velocity:** $\frac{dx}{dt} = v$
2.  **Acceleration:** $\frac{dv}{dt} = -\frac{b}{m}v - \frac{k}{m}x$

The RK4 method iteratively evaluates the slopes of these functions at four different points within a small time step ($dt$) and takes a weighted average to highly accurately predict the next state of $x$ and $v$.

---

### 3. Investigation of Parameter $b$ and Phase Portraits



While the $x(t)$ graph plots Position vs. Time, a **Phase Portrait** plots Velocity vs. Position ($v$ vs $x$). Investigating the parameter $b$ reveals different phase trajectories:
* **When Underdamped:** The phase portrait forms an inward-spiraling trajectory (a spiral sink) that eventually settles at the origin $(0,0)$.
* **When Critically/Overdamped:** The phase portrait does not spiral. It curves directly into the origin, indicating a return to rest without overshooting the equilibrium position.

---
