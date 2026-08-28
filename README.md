# NOR Gate using SystemVerilog

## 📌 Project Overview

This project implements a **2-input NOR Gate** using **SystemVerilog HDL**. The design is verified using a SystemVerilog testbench by applying all possible input combinations and observing the output.

## 🔧 Tools Used

* **SystemVerilog**
* **EDA Playground** – Simulation
* **GitHub** – Project Repository

## 🧠 NOR Gate

A NOR gate performs an **OR operation followed by NOT**.

### Boolean Expression

```text
Y = ~(A | B)
```

### Truth Table

| A | B | Y |
| - | - | - |
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |


## 📊 Simulation

The design was simulated using **EDA Playground**, and the output was verified against the NOR gate truth table.

## 🎯 Learning Outcomes

* Learned basic **SystemVerilog module design**
* Practiced `logic` data types
* Used continuous assignment with `assign`
* Learned how to create and connect a **testbench**
* Verified digital logic functionality through simulation

