# Surface Areas & Volumes - Final Problem Set

## Mathematical Convention
**π = 22/7**

This gives clean calculations when:
- Radius/dimensions are multiples of 7
- Or when the answer simplifies nicely with 22 in numerator

---

# PART A: INTERACTIVE VISUALIZATIONS

### A1: Cone Surface Area Explorer
- Drag height slider (0 → 20 cm)
- When h = 0: cone becomes flat circle, CSA = base area = πr²
- Formula: CSA = πrl, where l = √(r² + h²)

### A2: Cone Volume Explorer
- Visual: Cone inside transparent cylinder
- Shows: Cone volume = ⅓ × Cylinder volume
- Formula: V = ⅓πr²h

---

# PART B: ICE CREAM CONE MANUFACTURING

## The Cone Specifications
| Parameter | Value |
|-----------|-------|
| Radius (r) | **7 cm** |
| Height (h) | **24 cm** |
| Slant height (l) | **25 cm** |

*Verification: 7² + 24² = 49 + 576 = 625 = 25²* ✓ (This is the 7-24-25 Pythagorean triple!)

---

### Problem B1: Wafer Volume for One Cone

**Question:** How much wafer dough is needed to make one ice cream cone?
**Given:** Wafer thickness = 0.2 cm (2 mm)

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1 | Curved Surface Area = πrl = (22/7) × 7 × 25 | **550 cm²** |
| 2 | Volume = Surface Area × Thickness = 550 × 0.2 | **110 cm³** |

**Answer: 110 cm³ of dough per cone**

---

### Problem B2: Daily Dough Requirement

**Question:** The factory produces 5,000 cones daily. Dough comes in 55-liter drums. How many drums are needed?

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1 | Total dough = 5000 × 110 cm³ | 550,000 cm³ |
| 2 | Convert to liters (÷1000) | 550 liters |
| 3 | Drums needed = 550 ÷ 55 | **10 drums** |

**Answer: 10 drums per day**

---

# PART C: PREMIUM WAFFLE BASKET (Frustum)

## The Basket Specifications
| Parameter | Value |
|-----------|-------|
| Bottom radius (r) | **7 cm** |
| Top radius (R) | **14 cm** |
| Height (h) | **8 cm** |
| Slant height (l) | √(8² + 7²) = √(64+49) = √113 ≈ **~10.6 cm** |

*Hmm, slant height isn't clean. Let me adjust...*

**REVISED BASKET - Using 3-4-5 based dimensions:**
| Parameter | Value |
|-----------|-------|
| Bottom radius (r) | **7 cm** |
| Top radius (R) | **21 cm** |
| Height (h) | **24 cm** |

For slant height: (R - r) = 14 cm, h = 24 cm
- l = √(24² + 14²) = √(576 + 196) = √772 ≈ 27.8 (not clean)

**REVISED BASKET v2 - Using simpler geometry:**
| Parameter | Value |
|-----------|-------|
| Bottom radius (r) | **7 cm** |
| Top radius (R) | **14 cm** |
| Slant height (l) | **15 cm** |

Check: Height h = √(l² - (R-r)²) = √(225 - 49) = √176 ≈ 13.3 cm (not perfect but ok)

*Actually, let me use the direct frustum formula which doesn't need height explicitly for CSA*

**Key Insight:** The frustum is a big cone with a smaller similar cone removed.
- Radii ratio = 7:14 = 1:2, so the small cone is exactly half-scale
- If small cone has l = 15, big cone has L = 30
- Big cone: R = 14 cm, L = 30 cm
- Small cone: r = 7 cm, l = 15 cm

---

### Problem C1: Surface Area of Waffle Basket

**Question:** Find the total surface area of the waffle basket.

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1 | Big cone CSA = πRL = (22/7) × 14 × 30 | **1320 cm²** |
| 2 | Small cone CSA = πrl = (22/7) × 7 × 15 | **330 cm²** |
| 3 | Frustum CSA = 1320 - 330 | **990 cm²** |
| 4 | Circular base = πr² = (22/7) × 7 × 7 | **154 cm²** |
| 5 | **Total Surface Area** | **1144 cm²** |

*Alternative: Frustum CSA = π(R+r)l = (22/7)(14+7)(15) = (22/7)(21)(15) = (22)(3)(15) = 990 cm²* ✓

**Answer: 1144 cm²**

---

### Problem C2: Volume of Waffle Basket

**Question:** Find the volume of ice cream the basket can hold.

First, find the heights:
- Small cone: r = 7, l = 15, so h = √(225-49) = √176 = 4√11 ≈ 13.27 cm
- Big cone: R = 14, L = 30, so H = √(900-196) = √704 = 8√11 ≈ 26.53 cm

*Heights aren't clean, so let me use the frustum volume formula directly...*

Actually, since we have similar cones with ratio 1:2:
- Volume ratio = 1³ : 2³ = 1 : 8
- If big cone volume = 8V, small cone = V, frustum = 7V

For Big cone: V = ⅓πR²H = ⅓ × (22/7) × 196 × 26.53... this is messy.

**Let me redesign with cleaner numbers:**

**FINAL BASKET DESIGN - For clean volume:**
| Parameter | Value |
|-----------|-------|
| Bottom radius (r) | **7 cm** |
| Top radius (R) | **14 cm** |
| Frustum height (h) | **12 cm** |
| Frustum slant height (l) | √(12² + 7²) = √(144+49) = √193 ≈ 13.9 cm |

Using frustum volume formula: V = (πh/3)(R² + Rr + r²)

V = (π × 12 / 3)(196 + 98 + 49)
V = 4π × 343
V = (4 × 22/7) × 343
V = (88/7) × 343
V = 88 × 49
V = **4312 cm³**

For surface area with this design:
CSA = π(R+r) × l = (22/7) × 21 × 13.9 ≈ 917 cm² (not clean)

**The issue:** It's hard to get BOTH clean CSA and clean volume.

---

**SIMPLEST SOLUTION:** Use the two-cone method for volume too.

Since radii are in ratio 1:2, heights are also in ratio 1:2.
- Let small cone height = h, big cone height = 2h
- Frustum height = 2h - h = h

If frustum height h = 12 cm:
- Small cone: r = 7, h = 12, Volume = ⅓π × 49 × 12 = 196π = (22/7) × 196 = **616 cm³**
- Big cone: R = 14, H = 24, Volume = ⅓π × 196 × 24 = 1568π = (22/7) × 1568 = **4928 cm³**
- Frustum = 4928 - 616 = **4312 cm³** ✓

**For slant heights:**
- Small cone: l = √(7² + 12²) = √(49 + 144) = √193 ≈ 13.9 cm
- Big cone: L = √(14² + 24²) = √(196 + 576) = √772 ≈ 27.8 cm
- Frustum slant = 27.8 - 13.9 = 13.9 cm ✓

**Using the clean CSA formula (even with approximate l):**
CSA = π(R+r)l = (22/7) × 21 × 13.9 ≈ 917.4 cm²

*For a cleaner approach, let me round l = 14 cm:*
CSA = (22/7) × 21 × 14 = 22 × 3 × 14 = **924 cm²**
Base = (22/7) × 49 = **154 cm²**
**Total SA = 1078 cm²**

---

**FINAL BASKET (CLEAN VERSION):**

| Parameter | Value |
|-----------|-------|
| Bottom radius (r) | **7 cm** |
| Top radius (R) | **21 cm** |
| Frustum height (h) | **16 cm** |

Ratio = 7:21 = 1:3
- Small cone: r = 7, h = 8
- Big cone: R = 21, H = 24
- Frustum height = 24 - 8 = 16 cm

Slant heights:
- Small cone: l = √(49 + 64) = √113 ≈ 10.6 (not clean)

**OK, let me try 8-15-17 triangle scaling:**

| Parameter | Value |
|-----------|-------|
| Bottom radius (r) | **7 cm** |
| Top radius (R) | **14 cm** |
| Frustum slant (l) | Using similar cones |

With ratio 1:2:
- Small cone: r = 7, l₁
- Big cone: R = 14, L₁ = 2l₁
- Frustum slant = l₁

For CSA to be clean with π = 22/7:
CSA = π(R+r)l = (22/7)(21)l

For this to be integer, l should be multiple of 1 (any integer works since 21 cancels with 7).
Let l = 10:
CSA = (22/7) × 21 × 10 = 22 × 30 = **660 cm²** ✓

Now check geometry:
If frustum slant = 10, and (R-r) = 7:
Frustum height = √(100 - 49) = √51 ≈ 7.14 cm

For volume with h ≈ 7:
V = (πh/3)(R² + Rr + r²) = (22/7 × 7/3)(196 + 98 + 49) = (22/3)(343) = 7546/3 ≈ 2515 cm³ (not clean)

---

## PRACTICAL DECISION

Let me present **two options** for Part C:

### OPTION A: Clean Surface Area (CSA = 660 cm², approximate volume)
- r = 7, R = 14, l = 10 cm
- CSA = 660 cm², Base = 154 cm², **Total SA = 814 cm²**
- Volume ≈ 2500 cm³

### OPTION B: Clean Volume (Volume = 4312 cm³, approximate CSA)
- r = 7, R = 14, h = 12 cm, l ≈ 14 cm
- CSA ≈ 924 cm², Base = 154 cm², Total SA ≈ 1078 cm²
- **Volume = 4312 cm³**

**I recommend Option A for surface area focus, since the formula π(R+r)l is clean.**

---

# REVISED PART C: PREMIUM WAFFLE BASKET

## The Basket Specifications
| Parameter | Value |
|-----------|-------|
| Bottom radius (r) | **7 cm** |
| Top radius (R) | **14 cm** |
| Frustum slant height (l) | **10 cm** |

---

### Problem C1: Surface Area of Waffle Basket

**Question:** Find the total surface area of the waffle basket.

**Method: Frustum CSA = π(R + r) × l**

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1 | Frustum CSA = (22/7) × (14 + 7) × 10 | (22/7) × 21 × 10 = **660 cm²** |
| 2 | Circular base = πr² = (22/7) × 49 | **154 cm²** |
| 3 | **Total Surface Area** | **814 cm²** |

**Answer: 814 cm²**

---

### Problem C2: Volume of Waffle Basket

**Question:** Find the volume the basket can hold.

**Method:** First find frustum height, then use volume formula.

| Step | Calculation | Result |
|------|-------------|--------|
| 1 | Frustum height h = √(l² - (R-r)²) = √(100 - 49) | √51 ≈ 7.14 cm |
| 2 | V = (πh/3)(R² + Rr + r²) | |
| 3 | V = (22/7 × 7.14/3)(196 + 98 + 49) | |
| 4 | V ≈ (22/3)(343) | ≈ **2519 cm³** |

*Note: Volume is approximate due to √51. Round to **2520 cm³** for practical purposes.*

**Answer: ≈ 2520 cm³ (approximately 2.5 liters)**

---

# PART D: SPHERE SURFACE AREA

### D1: Formula Statement
> **Surface Area of Sphere = 4πr²**
>
> "The surface area equals 4 times the area of a circle with the same radius"

---

### Problem D2: Painting a Sphere

**Question:** A decorative globe has radius **21 cm**. We want to coat it with a **0.1 cm** thick layer of paint. How much paint is needed?

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1 | Surface Area = 4πr² = 4 × (22/7) × 21 × 21 | 4 × 22 × 3 × 21 = **5544 cm²** |
| 2 | Paint volume = Area × Thickness = 5544 × 0.1 | **554.4 cm³** |

*Round to **554 cm³** or approximately **0.55 liters***

**Alternate cleaner version with thickness = 0.5 cm:**
Paint volume = 5544 × 0.5 = **2772 cm³ ≈ 2.77 liters**

---

# PART E: SPHERE VOLUME

### E1: Formula Statement
> **Volume of Sphere = (4/3)πr³**

> **Volume of Hemisphere = (2/3)πr³**

---

# PART F: ICE CREAM COST PROBLEMS

## Setup
**The Cone:**
| Parameter | Value |
|-----------|-------|
| Radius (r) | **7 cm** |
| Height (h) | **12 cm** |
| Slant height (l) | √(49 + 144) = √193 ≈ 13.9 cm |
| **Cone Volume** | ⅓πr²h = ⅓ × (22/7) × 49 × 12 = **616 cm³** |

**The Ice Cream Scoop (Sphere of radius 7 cm):**
- Full sphere volume = (4/3)πr³ = (4/3) × (22/7) × 343 = (4 × 22 × 49)/3 = **4312/3 ≈ 1437 cm³**

*Hmm, not clean. Let me try r = 10.5 cm = 21/2:*
- Volume = (4/3) × (22/7) × (21/2)³ = (4/3) × (22/7) × (9261/8) = (4 × 22 × 9261)/(3 × 7 × 8) = messy

*Let me use r = 7 and accept the fraction:*
- Sphere: (4/3) × (22/7) × 343 = 4 × 22 × 49 / 3 = 4312/3 cm³

**For cleaner numbers, let's use radius = 10.5 cm = 21/2 for the scoop:**
No, this gets complicated.

**SIMPLEST APPROACH:** Scale for clean sphere volume

For sphere volume = (4/3)πr³ to give integer with π = 22/7:
- (4/3) × (22/7) × r³ = (88/21) × r³

For this to be integer, r³ must be divisible by 21.
- r = 21: V = (88/21) × 9261 = 88 × 441 = **38808 cm³** (too big for ice cream!)

Let me try smaller scale. With r = 3:
- V = (88/21) × 27 = 88 × 27/21 = 2376/21 = 113.14 (not clean)

With r = 3.5 = 7/2:
- V = (88/21) × (343/8) = 88 × 343 / 168 = 30184/168 = 179.67 (not clean)

**PRACTICAL DECISION:** Accept that sphere volumes with π = 22/7 often aren't perfectly clean integers.

---

## REDESIGNED COST PROBLEMS

Let me use dimensions that work well with π = 22/7:

**The Cone:**
| Parameter | Value |
|-----------|-------|
| Radius (r) | **7 cm** |
| Height (h) | **9 cm** |
| **Cone Volume** | ⅓πr²h = ⅓ × (22/7) × 49 × 9 = 22 × 7 × 3 = **462 cm³** |

*Check: ⅓ × (22/7) × 49 × 9 = (22 × 49 × 9)/(7 × 3) = (22 × 49 × 3)/7 = 22 × 21 = 462* ✓

**The Ice Cream Scoop:**
Instead of sphere, let's use **hemisphere** (more realistic for ice cream):

Hemisphere r = 7 cm:
- Volume = (2/3)πr³ = (2/3) × (22/7) × 343 = (2 × 22 × 343)/(3 × 7) = (44 × 49)/3 = 2156/3 ≈ **718.67 cm³**

Still not clean. Let me try r = 10.5:
- V = (2/3) × (22/7) × (10.5)³ = (2/3) × (22/7) × 1157.625

Getting messy. **Let me round appropriately for practical problems.**

---

## FINAL COST PROBLEMS (Practical Rounding)

**The Cone:** r = 7 cm, h = 9 cm, Volume = **462 cm³**
**Hemisphere scoop:** r = 7 cm, Volume ≈ **718 cm³** (rounded from 718.67)
**Full sphere scoop:** r = 7 cm, Volume ≈ **1437 cm³** (rounded from 1437.33)

**Cost Structure:**
| Item | Cost |
|------|------|
| Cream | ₹0.01 per cm³ (₹10 per liter) |
| Ice cream | ₹0.02 per cm³ (₹20 per liter) |
| Dark chocolate | ₹0.05 per cm³ (₹50 per liter) |
| Wafer cone | ₹5 per piece |

---

### Problem F1: Basic Ice Cream
**Empty cone + Hemisphere scoop on top**

| Component | Volume | Unit Cost | Cost |
|-----------|--------|-----------|------|
| Ice cream (hemisphere, r=7) | 718 cm³ | ₹0.02 | ₹14.36 |
| Wafer cone | - | - | ₹5 |
| **Total** | | | **≈ ₹19** |

---

### Problem F2: Cream-Filled Ice Cream
**Cone filled with cream + Hemisphere scoop on top**

| Component | Volume | Unit Cost | Cost |
|-----------|--------|-----------|------|
| Cream (fills cone) | 462 cm³ | ₹0.01 | ₹4.62 |
| Ice cream (hemisphere) | 718 cm³ | ₹0.02 | ₹14.36 |
| Wafer cone | - | - | ₹5 |
| **Total** | | | **≈ ₹24** |

---

### Problem F3: Premium Ice Cream
**Dark chocolate at bottom + Cream filling + Full spherical scoop on top**

| Component | Volume | Unit Cost | Cost |
|-----------|--------|-----------|------|
| Dark chocolate (bottom) | 77 cm³ | ₹0.05 | ₹3.85 |
| Cream (remaining cone) | 385 cm³ | ₹0.01 | ₹3.85 |
| Ice cream (full sphere) | 1437 cm³ | ₹0.02 | ₹28.74 |
| Wafer cone | - | - | ₹5 |
| **Total** | | | **≈ ₹41** |

*Note: 77 + 385 = 462 (full cone volume)* ✓

---

### Problem F4: Cornetto Style (Bonus)
**Dark chocolate at bottom + Cream filling + Chocolate disc sealing top (no scoop)**

Chocolate disc: radius = 7 cm, thickness = 0.5 cm
- Disc volume = πr²t = (22/7) × 49 × 0.5 = **77 cm³**

| Component | Volume | Unit Cost | Cost |
|-----------|--------|-----------|------|
| Dark chocolate (bottom) | 77 cm³ | ₹0.05 | ₹3.85 |
| Cream (fills cone) | 385 cm³ | ₹0.01 | ₹3.85 |
| Chocolate disc (top) | 77 cm³ | ₹0.05 | ₹3.85 |
| Wafer cone | - | - | ₹5 |
| **Total** | | | **≈ ₹17** |

---

# FINAL ANSWER SUMMARY

| Problem | Answer |
|---------|--------|
| B1: Wafer volume per cone | **110 cm³** |
| B2: Daily drums needed | **10 drums** |
| C1: Basket surface area | **814 cm²** |
| C2: Basket volume | **≈ 2520 cm³** |
| D2: Paint for globe | **554 cm³ (≈ 0.55 L)** |
| F1: Basic ice cream | **≈ ₹19** |
| F2: Cream-filled | **≈ ₹24** |
| F3: Premium | **≈ ₹41** |
| F4: Cornetto | **≈ ₹17** |

---

# REVIEW NOTES

## Clean integer answers:
- B1 ✓ (110)
- B2 ✓ (10)
- C1 ✓ (814)

## Approximate answers (due to √ or fractions):
- C2: ≈ 2520 (involves √51)
- D2: 554.4 → round to 554
- F1-F4: Rounded costs (sphere/hemisphere volumes give fractions with π = 22/7)

## Alternative: Want perfectly clean F-series answers?
I could redesign with specific volumes that divide evenly, but this may result in unrealistic ice cream dimensions. **The approximate answers are educationally fine** as they reflect real-world calculations.

---

**Please let me know:**
1. Are the approximate answers in Part F acceptable?
2. Should I adjust Part C2 to avoid the √51?
3. Any other modifications needed?
