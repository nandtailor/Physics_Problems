### The Core Concept
The time it takes for a simple pendulum to complete one full swing (its **Period**, denoted by $T$) depends on only two factors:
1. **$L$**: The length of the string.
2. **$g$**: The acceleration due to gravity. 

The mass of the pendulum bob does not affect the period. The standard formula is:

$$T = 2\pi\sqrt{\frac{L}{g}}$$

---

### Question 1: What would the period be on the Moon?

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

### Question 2: What is the required length for a period of exactly 1 second on Earth?

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

**1/4 meter** is exactly **0.25 meters**, or **25 cm**.

*(Note for the professor: If calculated using the exact value of $g = 9.8\text{ m/s}^2$, the length is roughly **24.8 cm**, proving the $\pi^2$ approximation is highly accurate for quick problem-solving).*

**Answer:** To get a period of exactly 1 second on Earth, the pendulum's length must be approximately **25 cm**.
