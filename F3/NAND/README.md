NAND Gate Implementation

### 1. Gate Equation
$$Y = \overline{A \cdot B}$$

### 2. Transistor-Level Design (Static CMOS)
* **PMOS Network (Pull-up):** 2 PMOS in parallel
* **NMOS Network (Pull-down):** 2 NMOS in series
* **Total:** **4 Transistors** (2 PMOS + 2 NMOS)

### 3. Truth Table

| A | B | Y = (A·B)' |
|---|---|-----------|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |
