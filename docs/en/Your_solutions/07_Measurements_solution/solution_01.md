### **Topic: Calculating Volume and Uncertainty of a Sphere**

**1. Given Data:**
From the recorded measurement $r = 6.20 \pm 0.05\text{ cm}$, we identify two components:

* **Measured Radius ($r$):** $6.20\text{ cm}$
* **Absolute Uncertainty in Radius ($\Delta r$):** $0.05\text{ cm}$

**2. Step 1: Calculate the Base Volume ($V$)**
First, calculate the volume using the standard formula for a sphere, ignoring the uncertainty for now.

* **Formula:** $V = \frac{4}{3}\pi r^3$
* **Calculation:** 
$$V = \frac{4}{3} \pi (6.20)^3$$


$$V = \frac{4}{3} \pi (238.328)$$


$$V \approx 998.3\text{ cm}^3$$



**3. Step 2: Apply the Power Rule for Uncertainty**
When a measured value is raised to a power (in this case, $r^3$), its **fractional uncertainty** is multiplied by that exact power.

* **The Rule:** Because the radius is cubed, the fractional uncertainty of the volume is exactly $3$ times the fractional uncertainty of the radius.
* **Formula:** $\frac{\Delta V}{V} = 3 \left( \frac{\Delta r}{r} \right)$

**4. Step 3: Calculate the Absolute Uncertainty in Volume ($\Delta V$)**
Rearrange the formula to solve for $\Delta V$ and substitute the known values:

* **Calculation:**

$$\Delta V = 3 \times \left( \frac{\Delta r}{r} \right) \times V$$


$$\Delta V = 3 \times \left( \frac{0.05}{6.20} \right) \times 998.3$$


$$\Delta V = 3 \times (0.00806) \times 998.3$$


$$\Delta V \approx 24.14\text{ cm}^3$$



**5. Final Answer:**
Rounding the base volume and the uncertainty to appropriate whole numbers (to match the precision context), the final result is written as:
**Volume = $998 \pm 24\text{ cm}^3$**
