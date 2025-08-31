## ❓ Question 5  

**A resistor with certain color bands is placed in series with an LED connected to a 5V supply.**  

👉 Is this resistor suitable for limiting current to a typical **red LED** (forward voltage ≈ 2V, desired current ≈ 12mA)?  

![LED Circuit](<../src/LED-Circuit.jpg>)  

---

### ✅ Solution & Learning  

**Correct Option:**  
👉 **1) Yes, it limits the current correctly**  

---

### 🔎 Step-by-Step Calculation  

1. **Decode the resistor:**  
   - Bands: Red, Red, Brown = **220 Ω**  
   - Gold = **±5% tolerance**  

2. **Voltage across resistor:**  
   - Supply voltage = **5V**  
   - LED forward drop = **2V**  
   - $ V_R = 5V - 2V = 3V $  

3. **Current through circuit (Ohm’s Law):**  
   $$
   I = \frac{V_R}{R} = \frac{3V}{220Ω} \approx 13.6 \, mA
   $$  

   ✅ Safe for a **standard red LED** (typical limit ~20mA).  

---

### 📐 Power Calculation (for resistor)  

$$
P = V_R \times I = 3V \times 0.0136A \approx 0.041W
$$  

- A **¼ W (0.25W) resistor** is safe here.  

![Resistor Current Calculation](<../src/Resistor-Current-Calculation.jpg>)  

*Where:*  
- **VF = Forward Voltage of LED**  
- **VR = Voltage across Resistor**  

---

### 💡 Why This Is Important  
- **Current-limiting resistors** prevent LEDs from burning out.  
- Reinforces practical application of **Ohm’s Law**.  
- Essential for:  
  - Indicator LEDs  
  - Sensor circuits  
  - Display elements  

---

🔗 [← Previous (Q4)](<../1. Resistor Basics/Question.4.md>) | [Restart Quiz](<../1. Resistor Basics/Question.1.md>)  
