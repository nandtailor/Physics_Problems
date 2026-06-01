### **Topic: Spring-Mass Oscillator - Period, Spring Constant, and Uncertainty**

**1. Experimental Setup (Given Data)**

* **Mass ($m$):** Let's assume **0.5 kg**. The problem states this has **"Zero Uncertainty"** (meaning we treat it as exactly perfect, $\Delta m = 0$).
* **Oscillations:** We time 10 complete up-and-down cycles per trial.
* **Trials ($N$):** We repeat this process 10 separate times to reduce human reaction error.

---

**2. Step 1: Data Collection & Finding the Period ($T$)**
Assume we recorded the time for 10 oscillations ($t_{10}$) for each trial (e.g., 9.8 s, 10.1 s, 9.9 s).
To find the time for a single oscillation (called the **Period**, $T$), we divide the total time by 10:


$$T_i = \frac{t_{10}}{10}$$

---

**3. Step 2: Calculating the Mean Period ($\bar{T}$)**
Next, we find the average (mean) of all 10 individual periods.

* **Formula:** Sum all 10 values and divide by 10.

$$\bar{T} = \frac{T_1 + T_2 + ... + T_{10}}{10}$$



*(For this example, let's assume our calculated **Mean Period is 1.00 s**).*

---

**4. Step 3: Standard Deviation & Measurement Uncertainty**
We need to calculate how much our times varied due to human error.

* **Standard Deviation ($\sigma_T$):** This measures the spread of your data. Let's assume our calculation gives a standard deviation of **0.03 s**.
* **Measurement Uncertainty ($\Delta T$):** Because we took 10 trials ($N = 10$), our final uncertainty is reduced. This is called the "Standard Error of the Mean."
* **Formula:** Divide the standard deviation by the square root of $N$.

$$\Delta T = \frac{\sigma_T}{\sqrt{10}}$$


$$\Delta T = \frac{0.03}{3.16} \approx 0.01$$



So, our final recorded Period is: **1.00 ± 0.01 s**.

---

**5. Step 4: Calculate the Spring Constant ($k$)**
The spring constant ($k$) tells us how stiff the spring is. The basic physics formula for a spring's period is:


$$T = 2\pi \sqrt{\frac{m}{k}}$$

To isolate $k$, we square both sides and rearrange the formula:


$$k = \frac{4\pi^2m}{\bar{T}^2}$$

Now, plug in our example values (Mass = 0.5, Mean Period = 1.00):


$$k = \frac{4 \times (3.1415)^2 \times 0.5}{(1.00)^2}$$

$$k = \frac{4 \times 9.87 \times 0.5}{1}$$

$$k = 19.74$$


*(The unit for spring constant is N/m).*

---

**6. Step 5: Calculate the Uncertainty in the Spring Constant ($\Delta k$)**
This is the most crucial part! Where does the error in $k$ come from?
Since the mass has zero uncertainty, 100% of the error comes from our Period measurement.

Here we apply the **"Power Rule"** of error propagation. In our formula, $\bar{T}$ is squared ($\bar{T}^2$). When a variable is raised to a power, its fractional uncertainty is multiplied by that exact power.

Therefore, the fractional error of $k$ is **2 times** the fractional error of $T$:


$$\frac{\Delta k}{k} = 2 \times \left( \frac{\Delta T}{\bar{T}} \right)$$

Rearrange to solve for the absolute uncertainty ($\Delta k$):


$$\Delta k = k \times 2 \times \left( \frac{\Delta T}{\bar{T}} \right)$$

Plug in the numbers:


$$\Delta k = 19.74 \times 2 \times \left( \frac{0.01}{1.00} \right)$$

$$\Delta k = 19.74 \times 0.02$$

$$\Delta k \approx 0.39$$

---

### **Final Report & Conclusion:**

After rounding to match the precision of our uncertainty (usually 1 significant figure for the error), our final lab report values look like this:

* **Mean Period:** **1.00 ± 0.01 s**
* **Calculated Spring Constant ($k$):** **19.7 ± 0.4 N/m**
