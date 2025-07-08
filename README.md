

# RLC Circuit Simulation

This project demonstrates the simulation of a **series RLC circuit** using CircuitLab.

---

## 🔧 **Components Used**

* **Resistor (R1):** 100 Ω
* **Inductor (L1):** 10 mH
* **Capacitor (C1):** 100 μF
* **DC Voltage Source (V1):** 10 V

---

## ⚡ **Objective**

To analyze the **transient response** of a series RLC circuit when a DC voltage is applied.

---

## 📝 **Procedure**

1. **Circuit Design** using [CircuitLab](https://www.circuitlab.com/editor/):

   * Arranged the DC voltage source, resistor, inductor, and capacitor in **series**.
   * Connected a **ground node** at the negative terminal of the voltage source for proper operation.

2. **Component Configuration**:

   * Resistor: 100 Ω
   * Inductor: 10 mH
   * Capacitor: 100 μF
   * Voltage Source: 10 V DC

3. **Simulation Setup** (Time Domain - Transient Analysis):

   * Simulation Stop Time: 0.1 seconds
   * Time Step: automatic or manually set to 1 μs

4. **Observed Waveforms**:

   * **Voltage across the capacitor (C1.v)**
   * **Current through the resistor (R1.i)**

---

## 🔍 **Key Observations**

* The **capacitor voltage** gradually increases and stabilizes at the supply voltage (10 V).
* The **inductor current** ramps up smoothly, resisting abrupt changes due to its inductive nature.
* Once the system reaches **steady-state**, the capacitor becomes fully charged and blocks DC, while the inductor behaves like a short circuit.

---

## 📷 **Circuit Diagram**

![Circuit Diagram](circuit.png)

---

## 📈 **Simulation Output**

![Simulation Graph](simulation.png)

---

## 💡 **Key Takeaways**

* Understanding the **transient dynamics** of RLC circuits under DC excitation.
* Visualizing how capacitors charge and how inductors resist changes in current.
* Gaining hands-on experience with CircuitLab for electronic circuit simulation.

---

## 🔗 **Resources**

* [CircuitLab Simulator](https://www.circuitlab.com/editor/)
* [Series RLC Circuit Theory – Electronics Tutorials](https://www.electronics-tutorials.ws/accircuits/series-rlc-circuit.html)

---

### ✨ **Created by**

👤 **sharanya**


