# Surface Areas & Volumes - Problem Set for Review

## Mathematical Convention
**32π = 100** (so π ≈ 3.125)

This makes: 8π = 25, 16π = 50, 64π = 200, 80π = 250, 96π = 300, 128π = 400

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
| Radius (r) | 8 cm |
| Height (h) | 6 cm |
| Slant height (l) | 10 cm |

*Verification: 8² + 6² = 64 + 36 = 100 = 10²* ✓

---

### Problem B1: Wafer Volume for One Cone

**Question:** How much wafer dough is needed to make one ice cream cone?
**Given:** Wafer thickness = 0.4 cm

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1 | Curved Surface Area = πrl = π × 8 × 10 | 80π = **250 cm²** |
| 2 | Volume = Surface Area × Thickness | 250 × 0.4 = **100 cm³** |

**Answer: 100 cm³ of dough per cone**

---

### Problem B2: Daily Dough Requirement

**Question:** The factory produces 5,000 cones daily. Dough comes in 50-liter drums. How many drums are needed?

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1 | Total dough = 5000 × 100 cm³ | 500,000 cm³ |
| 2 | Convert to liters | 500 liters |
| 3 | Drums needed = 500 ÷ 50 | **10 drums** |

**Answer: 10 drums per day**

---

# PART C: PREMIUM WAFFLE BASKET (Frustum)

## The Basket Specifications
| Parameter | Value |
|-----------|-------|
| Bottom radius (r) | 4 cm |
| Top radius (R) | 8 cm |
| Height (h) | 3 cm |
| Slant height (l) | 5 cm |

*Verification: l² = h² + (R-r)² → 25 = 9 + 16* ✓

**Key Insight:** The frustum is a big cone with a smaller similar cone removed.
- Radii ratio = 4:8 = 1:2, so the small cone is exactly half-scale
- Big cone: R = 8 cm, H = 6 cm, L = 10 cm
- Small cone: r = 4 cm, h = 3 cm, l = 5 cm

---

### Problem C1: Surface Area of Waffle Basket

**Question:** Find the total surface area of the waffle basket.

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1 | Big cone CSA = π × 8 × 10 = 80π | 250 cm² |
| 2 | Small cone CSA = π × 4 × 5 = 20π | 62.5 cm² |
| 3 | Frustum CSA = 80π - 20π = 60π | 187.5 cm² |
| 4 | Circular base = π × 4² = 16π | 50 cm² |
| 5 | **Total Surface Area** | **237.5 cm²** |

*Alternative: Frustum CSA = π(R+r)l = π(8+4)(5) = 60π = 187.5 cm²*

---

### Problem C2: Volume of Waffle Basket

**Question:** Find the volume of ice cream the basket can hold.

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1 | Big cone volume = ⅓ × π × 8² × 6 = 128π | 400 cm³ |
| 2 | Small cone volume = ⅓ × π × 4² × 3 = 16π | 50 cm³ |
| 3 | **Frustum volume** = 128π - 16π = 112π | **350 cm³** |

*Alternative: V = (πh/3)(R² + Rr + r²) = (3π/3)(64+32+16) = 112π = 350 cm³*

**Answer: 350 cm³**

---

# PART D: SPHERE SURFACE AREA

### D1: Formula (No interaction, just statement)
> **Surface Area of Sphere = 4πr²**
>
> "The surface area equals 4 times the area of a circle with the same radius"

---

### Problem D2: Painting a Sphere

**Question:** A decorative globe has radius 20 cm. We want to coat it with a 2 mm (0.2 cm) thick layer of paint. How many liters of paint are needed?

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1 | Surface Area = 4πr² = 4 × π × 20² = 4 × π × 400 | 1600π = **5000 cm²** |
| 2 | Paint volume = Area × Thickness = 5000 × 0.2 | **1000 cm³** |
| 3 | Convert to liters | **1 liter** |

**Answer: 1 liter of paint**

---

# PART E: SPHERE VOLUME

### E1: Formula (With visual)
> **Volume of Sphere = (4/3)πr³**

---

# PART F: ICE CREAM COST PROBLEMS

## Setup
**The Cone:**
| Parameter | Value |
|-----------|-------|
| Radius (r) | 6 cm |
| Height (h) | 8 cm |
| Slant height (l) | 10 cm |
| **Cone Volume** | ⅓π × 36 × 8 = 96π = **300 cm³** |

*Verification: 6² + 8² = 36 + 64 = 100 = 10²* ✓

**The Ice Cream Scoop (Sphere of radius 6 cm):**
- Full sphere volume = (4/3)π × 6³ = (4/3)π × 216 = 288π = **900 cm³**
- Hemisphere volume = 144π = **450 cm³**

**Cost Structure:**
| Item | Cost |
|------|------|
| Cream | ₹0.02 per cm³ (₹20 per liter) |
| Ice cream | ₹0.04 per cm³ (₹40 per liter) |
| Dark chocolate | ₹0.10 per cm³ (₹100 per liter) |
| Wafer cone | ₹5 per piece |

---

### Problem F1: Basic Ice Cream
**Empty cone + Full spherical scoop on top**

| Component | Volume | Unit Cost | Cost |
|-----------|--------|-----------|------|
| Ice cream (sphere) | 900 cm³ | ₹0.04 | ₹36 |
| Wafer cone | - | - | ₹5 |
| **Total** | | | **₹41** |

---

### Problem F2: Cream-Filled Ice Cream
**Cone filled with cream + Hemisphere scoop on top**

| Component | Volume | Unit Cost | Cost |
|-----------|--------|-----------|------|
| Cream (fills cone) | 300 cm³ | ₹0.02 | ₹6 |
| Ice cream (hemisphere) | 450 cm³ | ₹0.04 | ₹18 |
| Wafer cone | - | - | ₹5 |
| **Total** | | | **₹29** |

---

### Problem F3: Premium Ice Cream
**Dark chocolate at bottom + Cream filling + Full spherical scoop on top**

| Component | Volume | Unit Cost | Cost |
|-----------|--------|-----------|------|
| Dark chocolate (bottom) | 50 cm³ | ₹0.10 | ₹5 |
| Cream (middle) | 250 cm³ | ₹0.02 | ₹5 |
| Ice cream (sphere) | 900 cm³ | ₹0.04 | ₹36 |
| Wafer cone | - | - | ₹5 |
| **Total** | | | **₹51** |

---

### Problem F4: Cornetto Style (Bonus)
**Dark chocolate at bottom + Cream filling + Chocolate disc on top (no ice cream scoop)**

The chocolate disc seals the top of the cone:
- Disc radius = 6 cm, thickness = 0.8 cm (approx 8mm)
- Disc volume = πr²t = π × 36 × 0.8 = 28.8π ≈ **90 cm³** (let's use **100 cm³** with t ≈ 0.9 cm)

| Component | Volume | Unit Cost | Cost |
|-----------|--------|-----------|------|
| Dark chocolate (bottom) | 50 cm³ | ₹0.10 | ₹5 |
| Cream (middle) | 250 cm³ | ₹0.02 | ₹5 |
| Chocolate disc (top) | 100 cm³ | ₹0.10 | ₹10 |
| Wafer cone | - | - | ₹5 |
| **Total** | | | **₹25** |

*Note: Cornetto is cheaper because it has no ice cream scoop - it's a compact, sealed cone!*

---

# ANSWER SUMMARY

| Problem | Answer |
|---------|--------|
| B1: Wafer volume | **100 cm³** |
| B2: Daily drums | **10 drums** |
| C1: Basket surface area | **237.5 cm²** |
| C2: Basket volume | **350 cm³** |
| D2: Paint volume | **1 liter** |
| F1: Basic ice cream | **₹41** |
| F2: Cream-filled | **₹29** |
| F3: Premium | **₹51** |
| F4: Cornetto | **₹25** |

---

# QUESTIONS FOR YOUR REVIEW

1. **C1 gives 237.5 cm²** (not integer) - Is this acceptable, or should I redesign?

2. **The 50 cm³ chocolate at bottom in F3/F4** - I specified it directly rather than calculating from a smaller cone shape. Should I derive it geometrically?

3. **Cone sizes**:
   - Manufacturing cone: r=8, h=6 (larger, for factory problems)
   - Ice cream cone: r=6, h=8 (smaller, for cost problems)

   Is it confusing to have two different cones? Should I unify them?

4. **Any additional problems you'd like to add?**

5. **The Cornetto disc thickness (0.9 cm = 9mm)** - Is this realistic for a chocolate disc?
