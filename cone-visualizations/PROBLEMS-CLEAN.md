# Surface Areas & Volumes - Clean Problem Set

## Convention: π = 22/7

---

# PART A: INTERACTIVE VISUALIZATIONS (No change)

### A1: Cone Surface Area Explorer
- Drag height slider, watch CSA change
- At h=0, cone becomes circle

### A2: Cone Volume Explorer
- Cone = ⅓ of cylinder with same base and height

---

# PART B: ICE CREAM CONE MANUFACTURING

## Cone: r = 7 cm, h = 24 cm, l = 25 cm
*(7-24-25 Pythagorean triple)*

### B1: Wafer Volume
| Step | Calculation | Result |
|------|-------------|--------|
| CSA | πrl = (22/7) × 7 × 25 | **550 cm²** |
| Volume | 550 × 0.2 (thickness) | **110 cm³** |

### B2: Daily Production
| Step | Calculation | Result |
|------|-------------|--------|
| Total | 5000 cones × 110 cm³ | 550,000 cm³ = **550 L** |
| Drums | 550 ÷ 55 | **10 drums** |

---

# PART C: WAFFLE BASKET (Frustum)

## Basket: r = 7 cm, R = 14 cm, l = 10 cm

### C1: Surface Area
| Step | Calculation | Result |
|------|-------------|--------|
| Frustum CSA | π(R+r)l = (22/7) × 21 × 10 | **660 cm²** |
| Base | πr² = (22/7) × 49 | **154 cm²** |
| **Total** | | **814 cm²** |

### C2: Volume
Using two-cone method (since r:R = 1:2):
- Big cone: R = 14, H = 2h (where h is small cone height)
- Small cone: r = 7, h

From slant height: l² = h² + (R-r)² → 100 = h² + 49 → h² = 51 → h ≈ 7.1 cm

**For cleaner calculation, let me use a different frustum:**

---

## REVISED BASKET: r = 7 cm, R = 14 cm, h = 6 cm

Using frustum volume formula: V = (πh/3)(R² + Rr + r²)

| Step | Calculation | Result |
|------|-------------|--------|
| R² + Rr + r² | 196 + 98 + 49 | 343 |
| V | (22/7) × (6/3) × 343 | (22/7) × 2 × 343 = **2156 cm³** |

For surface area, we need slant height:
l = √(h² + (R-r)²) = √(36 + 49) = √85 ≈ 9.2 cm

CSA = π(R+r)l ≈ (22/7) × 21 × 9.2 ≈ 607 cm² (not clean)

---

## BEST APPROACH: Keep l = 10, accept approximate volume

**FINAL BASKET: r = 7, R = 14, l = 10, h ≈ 7.1**

| Part C1 | Surface Area | **814 cm²** | ✓ Clean |
| Part C2 | Volume | **≈ 2500 cm³** | Approximate |

---

# PART D: SPHERE SURFACE AREA

### Formula: SA = 4πr²

### Problem: Paint a Globe
**Globe radius = 21 cm, Paint thickness = 0.5 cm**

| Step | Calculation | Result |
|------|-------------|--------|
| Surface Area | 4 × (22/7) × 21² | 4 × 22 × 63 = **5544 cm²** |
| Paint Volume | 5544 × 0.5 | **2772 cm³ = 2.772 L** |

**Answer: Approximately 2.8 liters of paint**

---

# PART E: SPHERE VOLUME

### Formula: V = (4/3)πr³

### Formula (Hemisphere): V = (2/3)πr³

---

# PART F: ICE CREAM COSTS

## Using r = 10.5 cm = 21/2 for clean sphere calculations!

**Why 10.5?** Because (21/2)³ = 9261/8, and with (4/3)(22/7), we get:
- Sphere V = (4/3) × (22/7) × (9261/8) = (4 × 22 × 9261)/(3 × 7 × 8) = 814968/168 = **4851 cm³**

Hmm, still complicated. Let me try r = 21:
- Sphere V = (4/3) × (22/7) × 9261 = (88 × 9261)/21 = (88 × 441) = **38808 cm³** (too big!)

---

## SIMPLEST APPROACH: Use dimensions that work

**The Cone:** r = 7 cm, h = 6 cm
- Volume = ⅓πr²h = (1/3) × (22/7) × 49 × 6 = (22 × 49 × 6)/(7 × 3) = (22 × 49 × 2)/7 = 22 × 14 = **308 cm³**

**The Hemisphere (Ice cream scoop):** r = 7 cm
- Volume = (2/3)πr³ = (2/3) × (22/7) × 343 = (2 × 22 × 343)/(3 × 7) = (44 × 49)/3 = 2156/3 = **718.67 ≈ 719 cm³**

**Full Sphere:** r = 7 cm
- Volume = 2 × 719 = **1437 cm³** (approximately)

---

## Cost Structure (Adjusted for clean totals)

| Item | Cost per cm³ | Cost per liter |
|------|-------------|----------------|
| Cream | ₹0.05 | ₹50 |
| Ice cream | ₹0.10 | ₹100 |
| Dark chocolate | ₹0.25 | ₹250 |
| Wafer cone | ₹10 (fixed) | - |

---

### F1: Basic Ice Cream
**Empty cone + Hemisphere scoop**

| Component | Volume | Rate | Cost |
|-----------|--------|------|------|
| Ice cream (hemisphere) | 720 cm³* | ₹0.10 | ₹72 |
| Cone | - | - | ₹10 |
| **Total** | | | **₹82** |

*Using 720 instead of 718.67 for clean calculation*

---

### F2: Cream-Filled + Hemisphere
**Cone filled with cream + Hemisphere on top**

| Component | Volume | Rate | Cost |
|-----------|--------|------|------|
| Cream (cone) | 308 cm³ | ₹0.05 | ₹15.40 |
| Ice cream (hemisphere) | 720 cm³ | ₹0.10 | ₹72 |
| Cone | - | - | ₹10 |
| **Total** | | | **≈ ₹97** |

---

### F3: Premium
**Chocolate bottom + Cream + Full sphere on top**

| Component | Volume | Rate | Cost |
|-----------|--------|------|------|
| Chocolate (bottom) | 44 cm³* | ₹0.25 | ₹11 |
| Cream | 264 cm³ | ₹0.05 | ₹13.20 |
| Ice cream (sphere) | 1440 cm³ | ₹0.10 | ₹144 |
| Cone | - | - | ₹10 |
| **Total** | | | **≈ ₹178** |

*44 + 264 = 308 (full cone)*

---

### F4: Cornetto
**Chocolate bottom + Cream + Chocolate disc (no scoop)**

| Component | Volume | Rate | Cost |
|-----------|--------|------|------|
| Chocolate (bottom) | 44 cm³ | ₹0.25 | ₹11 |
| Cream | 264 cm³ | ₹0.05 | ₹13.20 |
| Chocolate disc | 77 cm³* | ₹0.25 | ₹19.25 |
| Cone | - | - | ₹10 |
| **Total** | | | **≈ ₹53** |

*Disc: πr²t = (22/7) × 49 × 0.5 = 77 cm³*

---

# SUMMARY

| Problem | Answer | Status |
|---------|--------|--------|
| B1: Wafer volume | **110 cm³** | ✓ Clean |
| B2: Daily drums | **10 drums** | ✓ Clean |
| C1: Basket SA | **814 cm²** | ✓ Clean |
| C2: Basket volume | **≈ 2500 cm³** | ~Approx |
| D2: Paint volume | **2772 cm³** | ✓ Clean |
| F1: Basic | **₹82** | ✓ Clean |
| F2: Cream-filled | **≈ ₹97** | ~Approx |
| F3: Premium | **≈ ₹178** | ~Approx |
| F4: Cornetto | **≈ ₹53** | ~Approx |

---

# MY RECOMMENDATION

The sphere volumes with π = 22/7 don't give clean integers (due to the 4/3 factor).

**Two options:**

## Option A: Round volumes to nearest multiple of 10
- Hemisphere: 720 cm³ (instead of 718.67)
- Sphere: 1440 cm³ (instead of 1437.33)
- Then adjust costs to be clean

## Option B: Use π = 3 for sphere problems only
This is sometimes done in textbooks for simplicity:
- Hemisphere (r=7): (2/3) × 3 × 343 = 686 cm³
- Sphere (r=7): (4/3) × 3 × 343 = 1372 cm³

---

**What do you prefer?**
1. Keep π = 22/7 throughout, accept approximate answers in Part F
2. Use rounded volumes (720, 1440) for cleaner costs
3. Adjust the ice cream scoop radius to get cleaner numbers
4. Some other approach?
