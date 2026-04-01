 # Full Adder Design using DSCH + Microwind

## 📌 Project Overview

This project demonstrates the design and implementation of a Full Adder using DSCH for schematic-level simulation and Microwind for CMOS layout and physical-level simulation.

---

## 🎯 Objective

* To design a Full Adder circuit
* To understand combinational logic implementation
* To verify functionality at both schematic and layout levels

---

## 🧠 Theory

A Full Adder is a combinational circuit that performs the addition of three binary inputs.

### Inputs:

* A
* B
* Cin (Carry input)

### Outputs:

* Sum
* Carry

### Logic:

* Sum = A ⊕ B ⊕ Cin
* Carry = (A · B) + (Cin · (A ⊕ B))

---

## 🛠 Tools Used

* DSCH (Digital Schematic Design)
* Microwind (CMOS Layout Design and Simulation)

---

## ⚙️ Implementation Steps

### Step 1: Design in DSCH

* Place XOR gates to generate Sum
* Use AND and OR gates to generate Carry
* Connect inputs and outputs properly

### Step 2: Simulation in DSCH

* Apply all possible input combinations
* Verify Sum and Carry outputs

### Step 3: Layout in Microwind

* Implement CMOS layout using PMOS and NMOS
* Arrange transistors properly
* Connect using metal and poly layers

### Step 4: Simulation in Microwind

* Run simulation
* Observe output waveforms
* Analyze delay

---

## 📊 Truth Table

| A | B | Cin | Sum | Carry |
| - | - | --- | --- | ----- |
| 0 | 0 | 0   | 0   | 0     |
| 0 | 0 | 1   | 1   | 0     |
| 0 | 1 | 0   | 1   | 0     |
| 0 | 1 | 1   | 0   | 1     |
| 1 | 0 | 0   | 1   | 0     |
| 1 | 0 | 1   | 0   | 1     |
| 1 | 1 | 0   | 0   | 1     |
| 1 | 1 | 1   | 1   | 1     |

---

## 📸 Results

* DSCH schematic simulation verified correct functionality
* Microwind layout implemented successfully
* Output matches expected Full Adder behavior

---

## ✅ Advantages

* Simple and efficient combinational circuit
* Fundamental building block in digital systems
* Easy to extend to multi-bit adders

---

## ⚠️ Limitations

* Delay increases when cascading multiple Full Adders
* Requires multiple logic gates
* Layout complexity increases with scaling

---

## 🚀 Applications

* Arithmetic circuits
* ALU (Arithmetic Logic Unit)
* Digital processors
* Binary addition operations

---

## 📌 Conclusion

The project successfully demonstrates the design and implementation of a Full Adder. It provides a clear understanding of digital logic design and CMOS layout using DSCH and Microwind.
done by
V.Venkata Harinath 
ECE DIPLOMA
SVGP TIRUPATI
...
