### **Step 1: Circuit Breakdown & Assumptions**

Before writing any equations, we need to define the three branches of the circuit and their total resistances:

* **Left Branch:** Contains battery $\mathcal{E}_1 = 4.5\text{ V}$, an internal resistance $r_w = 1\,\Omega$, and resistor $R_1 = 20\,\Omega$.
* *Total Resistance* = $21\,\Omega$.


* **Right Branch:** Contains battery $\mathcal{E}_2 = 9\text{ V}$ and its internal resistance $r_w = 1\,\Omega$.
* *Total Resistance* = $1\,\Omega$.


* **Middle Branch:** Contains the shared resistor $R_2 = 10\,\Omega$.

---

### **Step 2: Kirchhoff's Current Law (KCL) - The Node Equation**

First, we must assume a direction for the currents. Let's assume currents flow *out* of the positive terminals of both batteries and meet at the top-middle node.

* Let **$I_1$** be the current flowing up the left branch.
* Let **$I_3$** be the current flowing up the right branch.
* Let **$I_2$** be the combined current flowing down through the middle branch.

According to KCL (Current In = Current Out) at the top node:


$$I_1 + I_3 = I_2 \quad \text{--- (Equation 1)}$$

---

### **Step 3: Kirchhoff's Voltage Law (KVL) - The Loop Equations**

Now, we apply KVL, which states that the sum of voltages around any closed loop must equal zero.

**1. The Left Loop (Clockwise path):**
Starting from the bottom-left and moving clockwise:

* Gain voltage from battery: $+4.5\text{ V}$
* Voltage drop across left resistors ($21\,\Omega$ total): $-21 I_1$
* Voltage drop across middle resistor ($10\,\Omega$): $-10 I_2$

$$4.5 - 21 I_1 - 10 I_2 = 0$$



Rearranging:

$$21 I_1 + 10 I_2 = 4.5 \quad \text{--- (Equation 2)}$$



**2. The Right Loop (Counter-Clockwise path):**
Starting from the bottom-right and moving counter-clockwise:

* Gain voltage from battery: $+9\text{ V}$
* Voltage drop across right internal resistor ($1\,\Omega$): $-1 I_3$
* Voltage drop across middle resistor ($10\,\Omega$): $-10 I_2$

$$9 - 1 I_3 - 10 I_2 = 0$$



Rearranging:

$$I_3 + 10 I_2 = 9 \quad \text{--- (Equation 3)}$$



---

### **Step 4: Solving the System of Equations**

We have three equations. The easiest method is to express $I_1$ and $I_3$ in terms of $I_2$, and then substitute them into Equation 1.

From Equation 2:


$$I_1 = \frac{4.5 - 10 I_2}{21}$$

From Equation 3:


$$I_3 = 9 - 10 I_2$$

Substitute these into Equation 1 ($I_2 = I_1 + I_3$):


$$I_2 = \left( \frac{4.5 - 10 I_2}{21} \right) + (9 - 10 I_2)$$

To eliminate the fraction, multiply the entire equation by 21:


$$21 I_2 = (4.5 - 10 I_2) + 21(9 - 10 I_2)$$

$$21 I_2 = 4.5 - 10 I_2 + 189 - 210 I_2$$

Combine like terms:


$$21 I_2 + 10 I_2 + 210 I_2 = 193.5$$

$$241 I_2 = 193.5$$

$$I_2 = \frac{193.5}{241}$$


**$I_2 \approx 0.803\text{ A}$**

Now, plug the value of $I_2$ back in to find $I_3$ and $I_1$:

* $$I_3 = 9 - 10(0.803) = 9 - 8.03$$



**$I_3 = 0.970\text{ A}$**
* $$I_1 = \frac{4.5 - 10(0.803)}{21} = \frac{4.5 - 8.03}{21} = \frac{-3.53}{21}$$



**$I_1 \approx -0.168\text{ A}$**

---

### **Step 5: Final Results & Physical Interpretation**

* **Current through $R_2$ ($I_2$):** $0.803\text{ A}$ flowing downwards.
* **Current through the right branch ($I_3$):** $0.970\text{ A}$ flowing upwards.
* **Current through $R_1$ ($I_1$):** $-0.168\text{ A}$.

