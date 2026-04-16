

#  Off-Grid Solar PV System Design – Al Ain (Recalculated)

---

##  Load Calculation

### Load Breakdown

| Item   | Power (W) | Qty | Hours | Total Power (W) | Energy (Wh/day) |
| ------ | --------- | --- | ----- | --------------- | --------------- |
| Lamps  | 10        | 5   | 6     | 50              | 300             |
| Fan    | 150       | 2   | 4     | 300             | 1200            |
| Fridge | 250       | 1   | 8     | 250             | 2000            |
| LCD    | 150       | 1   | 4     | 150             | 600             |
| AC     | 1200      | 1   | 6     | 1200            | 7200            |
| Laptop | 65        | 1   | 5     | 65              | 325             |

---

### Total Demand

* **Peak Load = 2015 W ≈ 2.0 kW**
* **Daily Energy = 11,625 Wh/day ≈ 11.6 kWh/day**

---

##  Solar Resource (Al Ain)

* Peak Sun Hours (PSH) ≈ **4.65 h/day**
* System efficiency ≈ **65%**

---

##  Required PV Array Size (Correct Design Step)

Formula:

> PV Power = Energy / (PSH × Efficiency)

Calculation:

* PV Power = 11.6 / (4.65 × 0.65)
* PV Power ≈ 3.8 kW

---

##  Final PV Size (with safety margin)

To ensure reliability (temperature losses, dust, aging):

 **Selected PV System = 4.2 kW**

---

## PV Module Selection

* Module size = 450 W

Calculation:

* 4200 / 450 ≈ 9.3 modules

✔ Final selection:

> **10 × 450 W = 4.5 kW system**

---

##  Inverter Sizing

Formula:

> Inverter = 1.3 × Peak Load

* 1.3 × 2.0 kW = 2.6 kW

✔ Final selection:

> **3 kW Off-grid Inverter**

---

##  System Voltage Selection

* Load ≈ 2 kW

✔ Recommended:

> **24V or 48V system → Selected: 48V (better efficiency)**

---

##  Battery Bank Sizing

Formula:

> Battery (Ah) = Energy / (Voltage × DoD)

Assumptions:

* Energy = 11.6 kWh
* Voltage = 48V
* DoD = 80%

Calculation:

* 11,600 Wh / (48 × 0.8)
* ≈ 302 Ah

✔ Final selection:

> **48V, ~300–350Ah Battery Bank (1 day autonomy)**

---

##  Final Optimized System

PV Array: **4.5 kW (10 × 450W modules)**
Inverter: **3 kW off-grid inverter**
 Battery: **48V ~300Ah**
 System Type: Off-grid residential
Location: Al Ain, UAE

---

##  Key Engineering Insight

This system is now:

*  Based strictly on real load demand
*  Not oversized (no unnecessary 5kW assumption)
*  Matched to solar resource in Al Ain
*  Properly balanced between PV, inverter, and battery

---

## Important Conclusion

> A 4.5 kW PV system is sufficient to reliably supply ~11.6 kWh/day in Al Ain, while maintaining system stability and allowing margin for real-world losses.

--
