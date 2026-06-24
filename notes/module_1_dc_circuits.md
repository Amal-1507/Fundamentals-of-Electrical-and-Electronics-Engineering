# Module 1: Fundamentals of DC Circuits

## 1. Core Electrical Quantities

### 1.1 Electrical Potential

The amount of work needed to move a unit charge from a reference point to a specific point against an electric field.

$$\text{Electrical Potential} = \frac{W}{Q} \quad \text{[Volts (V)]}$$

Where:
- $W$ = Electrical Potential Energy (Joules)
- $Q$ = Charge (Coulombs)

**Unit:** Joules/Coulomb = Volts (V)

---

### 1.2 Electrical Potential Difference (Voltage)

The difference in electrical potential between two points.

$$V = \frac{dw}{dq} \quad \text{[Volts (V)]}$$

Where:
- $dw$ = Change in work (Joules)
- $dq$ = Change in charge (Coulombs)

---

### 1.3 Electric Current

The rate of flow of electric charge through a conductor.

$$I = \frac{dq}{dt} \quad \text{[Amperes (A)]}$$

Where:
- $dq$ = Change in charge (Coulombs)
- $dt$ = Change in time (Seconds)

**Unit:** Coulombs/Second = Amperes (A)

---

### 1.4 Electrical Power

Energy supplied or absorbed per unit time.

$$P = \frac{dw}{dt} = VI = I^2R \quad \text{[Watts (W)]}$$

Where:
- $V$ = Voltage (Volts)
- $I$ = Current (Amperes)
- $R$ = Resistance (Ohms)

**Unit Relationship:**
$$1 \text{ Watt} = \frac{1 \text{ Joule}}{1 \text{ Second}}$$

#### Passive Sign Convention for Power

| Power Type | Sign |
|---|---|
| Power Produced (Generated) | Negative (−) |
| Power Consumed (Absorbed) | Positive (+) |

---

## 2. Electrical Energy & Utility Standards

### 2.1 Energy Measurement

Electric power utility companies measure energy consumed in:
- **Watt-hours (Wh)**
- **Kilowatt-hours (kWh)**

**Conversion:**
$$1 \text{ Wh} = \left[\frac{\text{Joule}}{\text{Second}}\right] \times [3600 \text{ Seconds}] = 3600 \text{ Joules}$$

### 2.2 Common Terms

| Quantity | Unit |
|---|---|
| Power Consumed | Watts (W) |
| Energy Consumed | Watt-hours (Wh) or Kilowatt-hours (kWh) |

### 2.3 Indian Power Supply Standards

| Parameter | Value |
|---|---|
| Voltage | 240 V |
| Frequency | 50 Hz |

---

## 3. Linear Electric Components

All elements dealt with at this level are **linear components**, meaning they follow specific properties:

### 3.1 Properties of Linear Components

1. **Principle of Superposition** *(to be learned later)*
2. **Principle of Homogeneity**

### 3.2 Principle of Homogeneity

It states that the relationship between input and output must be linear. For a linear component, this is represented by its current-voltage ($I$-$V$) characteristic.

**Definition:** When the input current $I$ is scaled by a factor of $k$, the output voltage $V$ is also scaled by the same factor $k$.

**Mathematical Representation:**

$$V = IR$$

If we scale the input current by factor $k$:
$$I_1 = kI \implies V_1 = (kI)R = k(IR) = kV$$

This demonstrates the linear relationship between voltage and current through Ohm's Law.

---

## 4. Solved Problem: Factory Energy Consumption

### 4.1 Problem Statement

A factory has a **240 V supply** from which the following loads are connected:

**Loads:**
- **Lighting:** 
  - 300 lamps of 150 W each
  - 400 lamps of 100 W each
  - 500 lamps of 60 W each
- **Heating:** 100 kW
- **Motors:** 74.76 kW (60 b.h.p.) with average efficiency of 75%
- **Miscellaneous:** Various loads drawing 40 A current

**Operating Schedule (5-day week):**
- Lighting: 4 hours/day
- Heating: 10 hours/day
- Motors & Miscellaneous: 2 hours/day

**Find:** Weekly energy consumption in kWh

---

### 4.2 Solution

#### Step 1: Calculate Total Power for Each Load

**Lighting:**
$$P_{\text{Lighting}} = \frac{(300 \times 150) + (400 \times 100) + (500 \times 60)}{1000}$$
$$P_{\text{Lighting}} = \frac{45000 + 40000 + 30000}{1000} = \frac{115000}{1000} = 115 \text{ kW}$$

**Heating:**
$$P_{\text{Heating}} = 100 \text{ kW}$$

**Miscellaneous:**
$$P_{\text{Misc}} = \frac{VI}{1000} = \frac{240 \times 40}{1000} = \frac{9600}{1000} = 9.6 \text{ kW}$$

**Motors:**
$$P_{\text{Motors}} = \frac{P_{\text{Output}}}{\text{Efficiency}} = \frac{74.76}{0.75} = 99.68 \text{ kW}$$

---

#### Step 2: Calculate Daily Energy Consumption

| Load Type | Power (kW) | Hours/Day | Daily Energy (kWh) |
|---|---|---|---|
| Lighting | 115 | 4 | $115 \times 4 = 460$ |
| Heating | 100 | 10 | $100 \times 10 = 1000$ |
| Miscellaneous | 9.6 | 2 | $9.6 \times 2 = 19.2$ |
| Motors | 99.68 | 2 | $99.68 \times 2 = 199.36$ |

**Total Daily Energy Consumption:**
$$E_{\text{Daily}} = 460 + 1000 + 19.2 + 199.36 = 1678.56 \text{ kWh/day}$$

---

#### Step 3: Calculate Weekly Energy Consumption

$$E_{\text{Weekly}} = E_{\text{Daily}} \times \text{Number of Days}$$
$$E_{\text{Weekly}} = 1678.56 \times 5 = \boxed{8392.8 \text{ kWh}}$$

**Answer:** The factory consumes **8392.8 kWh** per week.

---

## References

- Basic concepts of electrical potential, current, and power
- Principle of homogeneity in linear circuits
- Energy calculation and utility standards
