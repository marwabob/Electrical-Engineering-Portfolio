
#  Off-Grid Solar PV System Design – Al Ain, UAE

<p align="center">
  <img src="off-grid.png" width="850"/>
</p>

<p align="center">
  <b>Engineering Design of a Standalone Solar PV System Based on Real Load Demand</b>
</p>

---

##  Project Overview

This project presents a **complete engineering design** of an off-grid solar PV system for a residential application in **Al Ain, UAE**.

 Load-based design (not assumption-based)  
 Optimized system sizing  
 Real solar resource integration  
 Balanced PV, inverter, and battery system  

---

##  Objectives

- Design a reliable **off-grid solar system**
- Accurately calculate **daily energy demand**
- Optimize **PV system size**
- Select appropriate **inverter and battery bank**
- Ensure **system efficiency and stability**

---

##  System Configuration

<p align="center">
  <img src="diagram2.png" width="700"/>
</p>

---

##  Load Analysis

###  Load Breakdown

| Appliance | Power (W) | Qty | Hours | Total Power (W) | Energy (Wh/day) |
|----------|----------|-----|-------|-----------------|-----------------|
| Lamps    | 10       | 5   | 6     | 50              | 300             |
| Fan      | 150      | 2   | 4     | 300             | 1200            |
| Fridge   | 250      | 1   | 8     | 250             | 2000            |
| LCD      | 150      | 1   | 4     | 150             | 600             |
| AC       | 1200     | 1   | 6     | 1200            | 7200            |
| Laptop   | 65       | 1   | 5     | 65              | 325             |

---

##  Total Demand

- **Peak Load:** 2.0 kW  
-  **Daily Energy Consumption:** 11.6 kWh/day  

---

##  Solar Resource (Al Ain)

- Peak Sun Hours (PSH): **4.65 h/day**  
- System Efficiency: **65%**

<p align="center">
  <img src="Radiation data.png" width="700"/>
</p>

<p align="center">
  <i>Figure: Solar radiation profile for Al Ain (UAE)</i>
</p>

---

##  PV System Sizing

### Formula
```

PV Power = Energy / (PSH × Efficiency)

```

### Calculation
```

PV Power = 11.6 / (4.65 × 0.65)
PV Power ≈ 3.8 kW

```

### Final Selection
- **4.2 kW (with safety margin)**

---

## PV Module Selection

- Module Rating: **450 W**

```

4200 / 450 ≈ 9.3 modules

```

###  Final Configuration
- **10 × 450W → 4.5 kW Total**

---

## Inverter Sizing

```

Inverter = 1.3 × Peak Load
1.3 × 2.0 = 2.6 kW

```

###  Selected
- **3 kW Off-Grid Inverter**

---

##  Battery Bank Design

### Formula
```

Battery (Ah) = Energy / (Voltage × DoD)

```

### Assumptions
- Energy = 11.6 kWh  
- Voltage = 48V  
- DoD = 80%

### Calculation
```

11600 / (48 × 0.8) ≈ 302 Ah

```

###  Final Selection
- **48V, 300–350Ah Battery Bank**

---

##  System Optimization

 No oversizing (avoids unnecessary cost)  
 Matches real solar conditions in UAE  
 Balanced energy generation & storage  
 Designed for reliability  

---

## Final System Summary

| Component | Specification |
|----------|-------------|
| PV Array | 4.5 kW (10 × 450W) |
| Inverter | 3 kW Off-grid |
| Battery  | 48V ~300Ah |
| System Type | Off-grid |
| Location | Al Ain, UAE |

---

## Results Visualization


---

##  Key Engineering Insight

A **4.5 kW PV system** is sufficient to reliably supply:

 **~11.6 kWh/day**  
 Under real environmental conditions in UAE  
 With proper safety and efficiency margins  

---

##  Tools & Methods Used

- Manual Engineering Calculations  
- Solar Resource Data (PSH)  
- PV System Design Principles  
- Load-Based Optimization  

---

##  Author

**Marwa Abdelkareem**

