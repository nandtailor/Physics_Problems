### QUESTION 1
The time it takes for a simple pendulum to complete one full swing (its **Period**, denoted by $T$) depends on only two factors:
1. **$L$**: The length of the string.
2. **$g$**: The acceleration due to gravity. 

The mass of the pendulum bob does not affect the period. The standard formula is:

$$T = 2\pi\sqrt{\frac{L}{g}}$$

---

### PART 1: What would the period be on the Moon?

**The Concept:** Gravity is weaker on the Moon, meaning there is less force pulling the pendulum down. Therefore, it will swing more slowly, resulting in a longer time period.

**The Easy Approach:** According to the formula, the period $T$ is inversely proportional to the square root of gravity ($T \propto \frac{1}{\sqrt{g}}$). 
If the gravity on the Moon is **1/6th** of Earth's gravity, the time period will increase by a factor of $\sqrt{6}$.

**Calculation:**
* Period on Earth ($T_E$) = **4 seconds**
* Period on Moon ($T_M$) = $T_E \times \sqrt{6}$
* The value of $\sqrt{6}$ is approximately **2.45**.

Therefore, the period on the Moon is:
$$T_M = 4 \times 2.45 = 9.8\text{ seconds}$$

**Answer:** The pendulum will have a period of approximately **9.8 seconds** on the Moon.

---

### PART 2: What is the required length for a period of exactly 1 second on Earth?

We need to find the length ($L$) that results in a time period ($T$) of exactly **1 second**.

**The Mathematical Trick (Approximation):**
On Earth, the acceleration due to gravity $g \approx 9.8\text{ m/s}^2$. 
In mathematics, the value of $\pi^2$ is approximately **9.87**. 
To make the mental math much easier without losing much accuracy, physicists often use the approximation **$g \approx \pi^2$**.

Here is how simple the calculation becomes:
$$T = 2\pi\sqrt{\frac{L}{g}}$$

Substitute $T = 1$ and $g = \pi^2$:
$$1 = 2\pi\sqrt{\frac{L}{\pi^2}}$$

The $\pi^2$ comes out of the square root as $\pi$:
$$1 = 2\pi \left(\frac{\sqrt{L}}{\pi}\right)$$

The $\pi$ values cancel out perfectly, leaving:
$$1 = 2\sqrt{L}$$

Isolate $\sqrt{L}$:
$$\sqrt{L} = \frac{1}{2}$$

Square both sides to find $L$:
$$L = \frac{1}{4}\text{ meters}$$


### QUESTION : 2
The oscillation of a mass attached to a spring is a classic example of **Simple Harmonic Motion (SHM)**. To solve this easily, we just need to compare the given equation with the standard SHM "blueprint" equation.



The standard equation for the position of an oscillating mass is:
$$x(t) = A \cos(\omega t)$$

The equation provided in your problem is:
$$x(t) = 0.2 \cos(10\pi t)$$

By simply comparing the two, we can directly extract the key variables:
* **$A$ (Amplitude):** The maximum displacement from the equilibrium position. Here, $A$ = **0.2 meters**.
* **$\omega$ (Angular Frequency):** The rate at which the system oscillates. Here, $\omega$ = **$10\pi\text{ rad/s}$**.
* **$m$ (Mass):** Given directly in the problem as $m$ = **10 kg**.

With these values identified, we can solve both parts of the problem.

---

### Part 1: What is the spring constant ($k$)?

The spring constant ($k$) represents the stiffness of the spring. The relationship between angular frequency, spring constant, and mass is given by the formula:
$$\omega = \sqrt{\frac{k}{m}}$$

To solve for $k$, we square both sides and rearrange the equation:
$$\omega^2 = \frac{k}{m}$$
$$k = m \cdot \omega^2$$

Now, substitute the known values:
$$k = 10 \cdot (10\pi)^2$$
$$k = 10 \cdot 100\pi^2$$
$$k = 1000\pi^2\text{ N/m}$$

*(Note for the professor: Using the common approximation $\pi^2 \approx 9.87$, this evaluates to exactly **9870 N/m**).*

**Answer:** The spring constant $k$ is **$1000\pi^2\text{ N/m}$**.

---

### Part 2: What is the total mechanical energy of the system?

The total mechanical energy ($E$) of a simple harmonic oscillator depends entirely on the stiffness of the spring ($k$) and the amplitude ($A$). 

The formula is:
$$E = \frac{1}{2} k A^2$$

Substitute the values we have gathered:
$$E = \frac{1}{2} \cdot (1000\pi^2) \cdot (0.2)^2$$

Since $(0.2)^2 = 0.04$:
$$E = 500\pi^2 \cdot 0.04$$
$$E = 20\pi^2\text{ Joules}$$

*(Using the $\pi^2 \approx 9.87$ approximation again, the energy evaluates to approximately **197.4 Joules**).*

**Answer:** The total mechanical energy of the system is **$20\pi^2\text{ Joules}$**.




**1/4 meter** is exactly **0.25 meters**, or **25 cm**.


### QUESTION 3
When a pendulum is pulled to the side and released, its gravitational potential energy at the highest point converts entirely into kinetic energy at the lowest point (the bottom of the swing). 

By equating Potential Energy ($PE$) and Kinetic Energy ($KE$):
$$mgh = \frac{1}{2}mv^2$$

The mass ($m$) cancels out on both sides, leaving a universal formula for the speed of an object falling from a height:
$$v = \sqrt{2gh}$$

To find the speed ($v$), we just need to calculate the vertical height ($h$) the pendulum bob dropped from its initial released position.

---

### Step 1: Calculate the vertical height ($h$)
Even though the string is 1.0 meter long, the bob does not drop a full meter. We must find the vertical distance between the release point at 15° and the bottom of the swing. The geometric formula for this is:
$$h = L(1 - \cos\theta)$$

Given values:
* Length ($L$) = **1.0 meter**
* Initial angle ($\theta$) = **15°**
* The value of $\cos(15^\circ)$ is approximately **0.966**.

Substitute the values:
$$h = 1.0 \cdot (1 - 0.966)$$
$$h = 0.034\text{ meters}$$

*(This means the bob was raised exactly 0.034 meters, or 3.4 cm, above its lowest resting point).*

---

### Step 2: Calculate the maximum speed ($v$)
Now that we have the height ($h$ = 0.034 meters), we can plug it directly into our derived energy formula. We will use the standard acceleration due to gravity on Earth ($g$ = 9.8 m/s²).

$$v = \sqrt{2gh}$$

Substitute the values:
$$v = \sqrt{2 \cdot 9.8 \cdot 0.034}$$
$$v = \sqrt{19.6 \cdot 0.034}$$
$$v = \sqrt{0.6664}$$

Taking the square root gives us approximately **0.816**.

**Answer:** The speed of the pendulum bob at the bottom of its swing is approximately **0.816 m/s**.


### QUESTION 4

### Part 1: Finding the Speed Before Collision (Conservation of Energy)

When the 0.5 kg block slides down the frictionless track, its initial gravitational potential energy is converted entirely into kinetic energy at the bottom. 

By equating Potential Energy ($PE$) and Kinetic Energy ($KE$):
$$mgh = \frac{1}{2}mv^2$$

The mass cancels out, leaving us with our standard kinematic formula for an object falling or sliding down a frictionless surface from a height ($h$):
$$v = \sqrt{2gh}$$

Given values:
* Height ($h$) = **3.0 m**
* Acceleration due to gravity ($g$) = **9.8 m/s²**

Substitute the values:
$$v_1 = \sqrt{2 \cdot 9.8 \cdot 3.0}$$
$$v_1 = \sqrt{58.8}$$
$$v_1 \approx 7.67\text{ m/s}$$

*(This means the 0.5 kg block is moving at approximately **7.67 m/s** right before it hits the second block).*

---

### Part 2: The Inelastic Collision (Conservation of Momentum)

When the two blocks collide and stick together, this is known as a **perfectly inelastic collision**. While kinetic energy is lost during the impact, the total momentum of the system is strictly conserved. 

**The Principle:** *(Total Momentum Before Collision) = (Total Momentum After Collision)*

**Before Collision:**
* Block 1: Mass ($m_1$) = **0.5 kg**, Velocity ($v_1$) = **7.67 m/s**
* Block 2: Mass ($m_2$) = **1.5 kg**, Velocity ($v_2$) = **0 m/s** (initially at rest)

**After Collision:**
* Since they stick together, their combined mass ($M$) = $m_1 + m_2 = 0.5 + 1.5$ = **2.0 kg**
* Let their new combined final velocity be **$V$**.

The momentum equation is:
$$m_1v_1 + m_2v_2 = M \cdot V$$

Substitute the known values:
$$(0.5 \cdot 7.67) + (1.5 \cdot 0) = 2.0 \cdot V$$
$$3.835 + 0 = 2.0 \cdot V$$

Now, isolate $V$ by dividing by 2.0:
$$V = \frac{3.835}{2.0}$$
$$V \approx 1.9175\text{ m/s}$$

**Answer:** The speed of the combined mass just after the collision is approximately **1.92 m/s**.

### QUESTION 5 

### Part 1: Finding the Final Speed (Conservation of Momentum)

When the runner jumps onto the cart and they move together, this is classified as a **perfectly inelastic collision**. In any isolated collision, the total momentum of the system is always conserved.

**The Principle:** *(Total Momentum Before Collision) = (Total Momentum After Collision)*

**Before the Collision:**
* Runner: Mass ($m_1$) = **70 kg**, Velocity ($v_1$) = **3 m/s**
* Cart: Mass ($m_2$) = **140 kg**, Velocity ($v_2$) = **0 m/s** (initially at rest)

**After the Collision:**
* Combined Mass ($M$) = $m_1 + m_2 = 70 + 140$ = **210 kg**
* Let the new combined final velocity be **$V$**.

The momentum equation is:
$$m_1v_1 + m_2v_2 = M \cdot V$$

Substitute the known values:
$$(70 \cdot 3) + (140 \cdot 0) = 210 \cdot V$$
$$210 + 0 = 210 \cdot V$$
$$210 = 210 \cdot V$$

Isolate $V$ by dividing both sides by 210:
$$V = \frac{210}{210}$$
$$V = 1\text{ m/s}$$

**Answer 1:** The final speed of the cart with the runner is **1 m/s**.

---

### Part 2: Is Kinetic Energy Conserved? 

To determine if kinetic energy (KE) is conserved, we must calculate the total kinetic energy of the system before and after the collision using the formula:
$$KE = \frac{1}{2}mv^2$$

**Initial Kinetic Energy (Before Collision):**
Since the cart is at rest, only the runner has kinetic energy.
$$KE_{\text{initial}} = \frac{1}{2} \cdot m_1 \cdot v_1^2$$
$$KE_{\text{initial}} = \frac{1}{2} \cdot 70 \cdot (3)^2$$
$$KE_{\text{initial}} = 35 \cdot 9$$
$$KE_{\text{initial}} = 315\text{ Joules}$$

**Final Kinetic Energy (After Collision):**
Now we calculate the energy of the combined mass moving together.
$$KE_{\text{final}} = \frac{1}{2} \cdot M \cdot V^2$$
$$KE_{\text{final}} = \frac{1}{2} \cdot 210 \cdot (1)^2$$
$$KE_{\text{final}} = 105 \cdot 1$$
$$KE_{\text{final}} = 105\text{ Joules}$$

**Conclusion & Explanation:**
**No**, kinetic energy is **not conserved** in this collision. 

The system started with **315 Joules** of kinetic energy but ended with only **105 Joules**. Exactly **210 Joules** of kinetic energy were "lost" ($\Delta KE = -210\text{ J}$). 

While the *total* energy in the universe is always conserved, in a perfectly inelastic collision, a significant portion of the macroscopic kinetic energy is transformed (dissipated) into other forms of energy. In the context of this physics problem, that missing 210 Joules was converted into internal energy: primarily the thermal energy (heat) generated by friction between the runner's shoes and the cart, the sound of the impact, and any minor physical deformation of the cart's suspension or surface.





**Answer:** To get a period of exactly 1 second on Earth, the pendulum's length must be approximately **25 cm**.

### QUESTION 6

When the tennis ball reaches the highest point of its bounce, its velocity is zero, meaning all of its mechanical energy is in the form of Gravitational Potential Energy ($PE$). 

The formula for Potential Energy is:
$$PE = mgh$$

Since the mass of the ball ($m$) and the acceleration due to gravity ($g$) remain constant, the maximum height ($h$) is **directly proportional** to the mechanical energy of the system. 
Therefore, if the ball loses 30% of its mechanical energy upon impact, it also loses 30% of its maximum bounce height. 

---

### Step-by-Step Calculation: The 70% Rule

If the ball loses 30% of its energy with each bounce, it retains exactly **70%** (or 0.70) of its energy for the next ascent. This means each successive bounce will reach 70% of the previous height.

* **Initial Height ($h_0$):** **2.0 meters**

**After the 1st Bounce:**
The ball reaches 70% of its initial height.
$$h_1 = h_0 \times 0.70$$
$$h_1 = 2.0 \times 0.70 = 1.4\text{ meters}$$

**After the 2nd Bounce:**
The ball reaches 70% of the new height ($h_1$).
$$h_2 = h_1 \times 0.70$$
$$h_2 = 1.4 \times 0.70 = 0.98\text{ meters}$$

---

### The Direct Mathematical Approach (Geometric Progression)

For a more advanced academic presentation, you can demonstrate that the height after $n$ bounces follows a geometric sequence:
$$h_n = h_0 \times (1 - \text{loss fraction})^n$$

Plugging in our values for the second bounce ($n = 2$):
$$h_2 = 2.0 \times (0.70)^2$$
$$h_2 = 2.0 \times 0.49 = 0.98\text{ meters}$$

**Answer:** After the second bounce, the tennis ball will rise to a height of exactly **0.98 meters** (or 98 cm).



### QUESTION 7

Because the 5 kg block is tethered to the wall, it remains stationary while the 10 kg block is pulled underneath it. This means the 10 kg block experiences kinetic friction from **two** different surfaces that oppose its motion:
1.  **Friction from the top:** Caused by the 5 kg block resting on it.
2.  **Friction from the bottom:** Caused by the ground.


---

### Step 1: Calculate the kinetic friction from the top block ($f_{k1}$)
The normal force exerted by the top block ($m_1$) depends only on its own mass.
* Mass ($m_1$) = **5 kg**
* Normal Force ($N_1$) = $m_1 g = 5 \cdot 9.8$ = **49 N**

Using the coefficient of kinetic friction ($\mu_k$ = 0.2):
$$f_{k1} = \mu_k \cdot N_1$$
$$f_{k1} = 0.2 \cdot 49 = 9.8\text{ N}$$
*(This is the force of the top block dragging against the 10 kg block).*

---

### Step 2: Calculate the kinetic friction from the ground ($f_{k2}$)
The normal force exerted by the ground must support the total weight of both blocks combined.
* Total Mass ($m_{\text{total}}$) = $5 + 10$ = **15 kg**
* Normal Force ($N_2$) = $m_{\text{total}} g = 15 \cdot 9.8$ = **147 N**

Using the same coefficient of kinetic friction ($\mu_k$ = 0.2):
$$f_{k2} = \mu_k \cdot N_2$$
$$f_{k2} = 0.2 \cdot 147 = 29.4\text{ N}$$
*(This is the force of the ground dragging against the 10 kg block).*

---

### Step 3: Calculate the Net Force ($F_{\text{net}}$)
Now we sum the forces acting on the 10 kg block in the horizontal direction. The applied force pulls it forward, while both frictional forces pull it backward.

* **Applied Force ($F_{\text{app}}$):** **45 N**
* **Total Opposing Friction ($f_{\text{total}}$):** $f_{k1} + f_{k2} = 9.8 + 29.4$ = **39.2 N**

$$F_{\text{net}} = F_{\text{app}} - f_{\text{total}}$$
$$F_{\text{net}} = 45 - 39.2 = 5.8\text{ N}$$

---

### Step 4: Calculate the Acceleration ($a$)
Using Newton's Second Law ($F = ma$), we can find the acceleration. We only use the mass of the bottom block ($m_2$ = 10 kg) because it is the only object actually accelerating.

$$a = \frac{F_{\text{net}}}{m_2}$$
$$a = \frac{5.8}{10}$$
$$a = 0.58\text{ m/s}^2$$

*(Alternative Note: If the curriculum prefers the approximation $g \approx 10\text{ m/s}^2$ for simplicity, the total friction is exactly **40 N**, leaving a net force of **5 N**, which results in an acceleration of exactly **0.5 m/s²**).*

**Answer:** Using $g = 9.8\text{ m/s}^2$, the acceleration of the 10 kg block is **0.58 m/s²**.

### QUESTION 8


### 1. The Equation of Motion and Its Solution

**Concept:** To find the equation of motion, we apply Newton's Second Law of Motion ($F = ma$) to the given restoring force. 
Acceleration ($a$) is the second derivative of position ($x$) with respect to time ($t$).

Equating the forces:
$$m \frac{d^2x}{dt^2} = -kx$$

Rearranging this gives us a second-order linear differential equation, which is the standard equation for Simple Harmonic Motion (SHM):
$$\frac{d^2x}{dt^2} + \frac{k}{m}x = 0$$

**Solution:** The general solution to this differential equation is a sinusoidal function:
$$x(t) = A \cos(\omega t + \phi)$$
*Where:*
* **$A$** is the amplitude (maximum displacement).
* **$\omega$** is the angular frequency, defined as $\omega = \sqrt{\frac{k}{m}}$.
* **$\phi$** is the phase constant (determined by initial conditions).

---

### 2. Work Done During Displacement ($0$ to $x_0$)

**Concept:** Because the force changes with position, we must integrate the force function over the displacement from $x = 0$ to $x = x_0$ to find the total work done ($W$) by the spring.

$$W = \int_{0}^{x_0} F(x) dx$$
$$W = \int_{0}^{x_0} (-kx) dx$$

Pulling out the constant ($-k$) and integrating $x$:
$$W = -k \left[ \frac{x^2}{2} \right]_{0}^{x_0}$$
$$W = -\frac{1}{2} k x_0^2$$

**Answer:** The work done by the spring force during this displacement is **$-\frac{1}{2} k x_0^2$**. The negative sign indicates that the restoring force acts in the opposite direction of the displacement.

---

### 3. Interpretation as Potential Energy

**Concept:** For a conservative force (like a spring force), the change in potential energy ($\Delta U$) is defined as the negative of the work done by that force.

$$\Delta U = -W$$
$$U(x_0) - U(0) = - \left( -\frac{1}{2} k x_0^2 \right)$$

If we establish our reference point such that the potential energy at equilibrium is zero ($U(0) = 0$), then the equation simplifies to:
$$U(x_0) = \frac{1}{2} k x_0^2$$

**Interpretation:** This shows that generalizing for any position $x$, the stored elastic potential energy in the system is represented by the formula **$U(x) = \frac{1}{2}kx^2$**. The work done against the spring is stored entirely as potential energy.

---

### 4. Verifying the Relationship $F = -\frac{dU}{dx}$

**Concept:** If $U(x)$ is the potential energy associated with a conservative force, taking the negative spatial derivative of $U(x)$ should yield the original force function $F(x)$. Let us verify this mathematically.

Given our derived potential energy: $U(x) = \frac{1}{2}kx^2$

Take the derivative with respect to $x$:
$$-\frac{dU}{dx} = -\frac{d}{dx} \left( \frac{1}{2} k x^2 \right)$$

Since $\frac{1}{2}$ and $k$ are constants, we differentiate $x^2$ to get $2x$:
$$-\frac{dU}{dx} = -\frac{1}{2} k \cdot (2x)$$

The 2s cancel out, leaving:
$$-\frac{dU}{dx} = -kx$$

This perfectly matches our original force, **$F(x) = -kx$**, successfully verifying the fundamental relationship between conservative forces and potential energy.

---

### 5. Graphical Representation of $F(x)$ and $U(x)$

![ Alt Text](file:///home/parrot_nand/Desktop/desmos-graph.png)

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


### QUESTION 12

No problem! Here is the formal English version. It presents the solution logically and follows standard calculus-based physics conventions, which is exactly what your professor will be looking for.



### The Core Concept: 2D Kinematics with Constant Force

Because the force acting on the particle is constant, the acceleration will also be constant. We can find the kinematic equations by applying Newton's Second Law and then integrating sequentially with respect to time ($t$).

**Given Parameters:**
* Mass ($m$) = **2 kg**
* Constant Force ($\vec{F}$) = $6\mathbf{\hat{i}} + 2\mathbf{\hat{j}}$ N
* Initial Velocity ($\vec{v}_0$) = $1\mathbf{\hat{i}} - 1\mathbf{\hat{j}}$ m/s *(at $t = 0$)*
* Initial Position ($\vec{r}_0$) = $0\mathbf{\hat{i}} + 0\mathbf{\hat{j}}$ m *(at $t = 0$)*

---

### Step 1: Determine the Acceleration ($\vec{a}(t)$)

Using Newton's Second Law ($\vec{F} = m\vec{a}$), we divide the force vector by the mass to find the acceleration.

$$a_x = \frac{F_x}{m} = \frac{6}{2} = 3$$
$$a_y = \frac{F_y}{m} = \frac{2}{2} = 1$$

**Answer 1:** $$\vec{a}(t) = 3\mathbf{\hat{i}} + 1\mathbf{\hat{j}}\text{ m/s}^2$$

---

### Step 2: Determine the Velocity ($\vec{v}(t)$)

Velocity is the integral of acceleration with respect to time: $\vec{v}(t) = \int \vec{a} dt + \vec{v}_0$.

* **X-direction:** $v_x(t) = \int 3 dt = 3t + v_{0x} = 3t + 1$
* **Y-direction:** $v_y(t) = \int 1 dt = t + v_{0y} = t - 1$

**Answer 2:** $$\vec{v}(t) = (3t + 1)\mathbf{\hat{i}} + (t - 1)\mathbf{\hat{j}}\text{ m/s}$$

---

### Step 3: Determine the Position ($\vec{r}(t)$)

Position is the integral of velocity with respect to time: $\vec{r}(t) = \int \vec{v}(t) dt + \vec{r}_0$. Since the particle starts at the origin, $\vec{r}_0 = 0$.

* **X-direction:** $x(t) = \int (3t + 1) dt = \frac{3}{2}t^2 + t = 1.5t^2 + t$
* **Y-direction:** $y(t) = \int (t - 1) dt = \frac{1}{2}t^2 - t = 0.5t^2 - t$

**Answer 3:** $$\vec{r}(t) = (1.5t^2 + t)\mathbf{\hat{i}} + (0.5t^2 - t)\mathbf{\hat{j}}\text{ m}$$

---

### Step 4: Draw/Describe the Trajectory


### Step 5: Calculate the Work Done at $t = 3$ s

Work ($W$) is defined as the dot product of the constant force and the displacement: $W = \vec{F} \cdot \Delta\vec{r}$.

First, find the displacement at exactly 3 seconds by plugging $t = 3$ into our position equation:
* $x(3) = 1.5(3)^2 + 3 = 1.5(9) + 3 = 13.5 + 3 = 16.5\text{ m}$
* $y(3) = 0.5(3)^2 - 3 = 0.5(9) - 3 = 4.5 - 3 = 1.5\text{ m}$
* $\Delta\vec{r} = 16.5\mathbf{\hat{i}} + 1.5\mathbf{\hat{j}}\text{ m}$

Now, calculate the dot product:
$$W = (F_x \cdot \Delta x) + (F_y \cdot \Delta y)$$
$$W = (6 \cdot 16.5) + (2 \cdot 1.5)$$
$$W = 99 + 3$$

**Answer 5:** The total work done by the force is **102 Joules**.

---

### Step 6: Check Consistency with the Work-Energy Theorem

The Work-Energy Theorem states that the net work done on an object equals its change in kinetic energy: $W = \Delta K = K_f - K_i$. 
Kinetic energy is given by $K = \frac{1}{2}mv^2$, where $v^2 = v_x^2 + v_y^2$.

**1. Initial Kinetic Energy ($K_i$ at $t = 0$):**
* $\vec{v}(0) = 1\mathbf{\hat{i}} - 1\mathbf{\hat{j}}$
* $v_0^2 = (1)^2 + (-1)^2 = 2$
* $K_i = \frac{1}{2} \cdot 2 \cdot 2 = 2\text{ Joules}$

**2. Final Kinetic Energy ($K_f$ at $t = 3$):**
First, find the velocity components at 3 seconds:
* $v_x(3) = 3(3) + 1 = 10$
* $v_y(3) = 3 - 1 = 2$
* $\vec{v}(3) = 10\mathbf{\hat{i}} + 2\mathbf{\hat{j}}$
* $v_f^2 = (10)^2 + (2)^2 = 100 + 4 = 104$
* $K_f = \frac{1}{2} \cdot 2 \cdot 104 = 104\text{ Joules}$

**3. Change in Kinetic Energy ($\Delta K$):**
$$\Delta K = K_f - K_i = 104 - 2 = 102\text{ Joules}$$

**Conclusion:** The calculated Work ($W = 102\text{ J}$) is exactly equal to the change in Kinetic Energy ($\Delta K = 102\text{ J}$). The relationship is fully consistent with the Work-Energy Theorem.
