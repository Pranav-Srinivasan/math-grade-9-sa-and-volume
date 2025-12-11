# Surface Areas & Volumes - Final Problem Set

## Convention: π = 22/7

---

# PART A: INTERACTIVE VISUALIZATIONS

### A1: Cone Surface Area Explorer
- Drag height slider (0 → max)
- When h = 0: cone becomes flat circle, CSA = πr²
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
| Base Radius (r) | **21 mm** |
| Vertical Height (h) | **28 mm** |
| Slant Height (l) | **35 mm** |
| Wafer Thickness | **1 mm** |

*Verification: 21² + 28² = 441 + 784 = 1225 = 35²* ✓ (This is 3-4-5 scaled by 7!)

---

### Problem B1: Wafer Dough Volume

**Question:** Calculate the volume of dough (in mm³) required to produce one cone.

**Method:** Volume of dough ≈ Curved Surface Area × Thickness

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1. Slant height | l = √(21² + 28²) = √1225 | **35 mm** |
| 2. Curved Surface Area | CSA = πrl = (22/7) × 21 × 35 | **2310 mm²** |
| 3. Volume of dough | CSA × thickness = 2310 × 1 | **2310 mm³** |

**Answer: 2310 mm³ of dough per cone**

---

### Problem B2: Daily Dough Requirement

**Question:** The factory produces 10,000 cones daily. Dough comes in 23.1 liter containers. How many containers are needed?

**Note:** 1 liter = 1,000,000 mm³

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1. Total dough | 10,000 × 2310 mm³ | 23,100,000 mm³ |
| 2. Convert to liters | 23,100,000 ÷ 1,000,000 | 23.1 liters |
| 3. Containers needed | 23.1 ÷ 23.1 | **1 container** |

*Or with different container size (2.31 L):* 23.1 ÷ 2.31 = **10 containers**

**Answer: 10 containers (of 2.31 L each)**

---

# PART C: WAFFLE BASKET (Frustum)

## The Basket Specifications
| Parameter | Value |
|-----------|-------|
| Bottom Radius (r₁) | **21 mm** |
| Top Radius (r₂) | **42 mm** |
| Vertical Height (h) | **28 mm** |

**Key Insight:** Think of the frustum as a **BIG cone minus a SMALL cone**.

Since the radii are in ratio 21:42 = 1:2, the small cone is exactly half the size of the big cone!

**Finding the full cones:**
- The ratio of radii = 1:2 means ratio of heights = 1:2
- If small cone height = 28 mm, then big cone height = 56 mm
- Frustum height = 56 - 28 = 28 mm ✓

**Small Cone:** r = 21 mm, h = 28 mm
- Slant height = √(21² + 28²) = √1225 = **35 mm**

**Big Cone:** R = 42 mm, H = 56 mm
- Slant height = √(42² + 56²) = √(1764 + 3136) = √4900 = **70 mm**

---

### Problem C1: Surface Area of Waffle Basket

**Question:** Find the Total Surface Area of the basket (circular base + curved surface).

**Method:** Frustum CSA = Big Cone CSA − Small Cone CSA

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1. Big cone CSA | πRL = (22/7) × 42 × 70 = 22 × 6 × 70 | **9240 mm²** |
| 2. Small cone CSA | πrl = (22/7) × 21 × 35 = 22 × 3 × 35 | **2310 mm²** |
| 3. Frustum CSA | 9240 − 2310 | **6930 mm²** |
| 4. Circular base | πr₁² = (22/7) × 21 × 21 = 22 × 63 | **1386 mm²** |
| 5. **Total Surface Area** | 6930 + 1386 | **8316 mm²** |

**Answer: 8316 mm²**

---

### Problem C2: Volume of Waffle Basket

**Question:** Find the volume the basket can hold.

**Method:** Frustum Volume = Big Cone Volume − Small Cone Volume

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1. Big cone volume | ⅓πR²H = ⅓ × (22/7) × 42² × 56 | |
| | = ⅓ × (22/7) × 1764 × 56 | |
| | = (22 × 1764 × 56)/(7 × 3) | |
| | = (22 × 252 × 56)/3 = (22 × 14112)/3 | **103,488 mm³** |
| 2. Small cone volume | ⅓πr²h = ⅓ × (22/7) × 21² × 28 | |
| | = (22 × 441 × 28)/(7 × 3) | |
| | = (22 × 63 × 28)/3 = (22 × 1764)/3 | **12,936 mm³** |
| 3. **Frustum volume** | 103,488 − 12,936 | **90,552 mm³** |

*Alternative check: Big cone = 8 × Small cone (since linear scale = 2, volume scale = 2³ = 8)*
*So frustum = 8V - V = 7V = 7 × 12,936 = 90,552 mm³* ✓

**Answer: 90,552 mm³ (≈ 90.6 ml)**

---

# PART D: SPHERE SURFACE AREA

### D1: Formula Statement
> **Surface Area of Sphere = 4πr²**
>
> "The surface area equals 4 times the area of a circle with the same radius"

---

### Problem D2: Painting the Moon (Model)

**Context:** A theme park is building a giant scale model of the Moon.

**Given:**
- The model is a sphere with **radius = 21 meters**
- Paint layer thickness = **1 mm = 0.001 m**

**Question:** How many liters of paint are required?

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1. Surface Area | 4πr² = 4 × (22/7) × 21 × 21 | |
| | = 4 × 22 × 63 | **5544 m²** |
| 2. Paint volume | Surface Area × Thickness | |
| | = 5544 × 0.001 | **5.544 m³** |
| 3. Convert to liters | 5.544 × 1000 | **5544 liters** |

**Answer: 5544 liters of paint**

---

# PART E: SPHERE VOLUME

### E1: Formula Statement
> **Volume of Sphere = (4/3)πr³**
>
> **Volume of Hemisphere = (2/3)πr³**

---

### Problem E2: Volume of Ice Cream Scoop

**Question:** Calculate the volume of a spherical ice cream scoop with radius = 21 mm.

**Solution:**
| Step | Calculation | Result |
|------|-------------|--------|
| 1. Volume | V = (4/3)πr³ = (4/3) × (22/7) × 21³ | |
| | = (4/3) × (22/7) × 9261 | |
| | = (4 × 22 × 9261)/(3 × 7) | |
| | = (88 × 9261)/21 | |
| | = (88 × 441) | **38,808 mm³** |

**Answer: 38,808 mm³ (≈ 38.8 ml)**

---

# PART F: ICE CREAM COST PROBLEMS

## Setup (New cone for bigger servings)

**The Cone:**
| Parameter | Value |
|-----------|-------|
| Radius (r) | **21 mm** |
| Height (h) | **90 mm** |

**Cone Volume:**
V = ⅓πr²h = ⅓ × (22/7) × 21² × 90 = (22 × 441 × 90)/(7 × 3) = (22 × 63 × 90)/3 = **41,580 mm³**

**Ice Cream Scoop (Sphere r = 21 mm):** 38,808 mm³ (from E2)

**Hemisphere (r = 21 mm):** 38,808 ÷ 2 = **19,404 mm³**

---

## Cost Structure
| Item | Cost |
|------|------|
| Waffle cone | ₹5 (fixed) |
| Ice cream | ₹1 per 1000 mm³ (per ml) |
| Vanilla cream | ₹0.50 per 1000 mm³ |
| Premium ice cream | ₹2 per 1000 mm³ |
| Dark chocolate | ₹3 per 1000 mm³ |

---

### Problem F1: The "Classic" (Empty Cone + Sphere on Top)

**Configuration:** Empty waffle cone with a spherical scoop sitting on top.

**Solution:**
| Component | Volume | Rate | Cost |
|-----------|--------|------|------|
| Ice cream (sphere) | 38,808 mm³ | ₹1/1000 mm³ | ₹38.81 |
| Waffle cone | - | - | ₹5 |
| **Total** | | | **≈ ₹44** |

**Answer: ₹44 (approximately)**

---

### Problem F2: The "Fully Loaded" (Filled Cone + Hemisphere)

**Configuration:**
- Cone completely filled with Vanilla Cream
- Hemisphere of Premium Ice Cream on top

**Solution:**
| Component | Volume | Rate | Cost |
|-----------|--------|------|------|
| Vanilla cream (cone) | 41,580 mm³ | ₹0.50/1000 | ₹20.79 |
| Premium ice cream (hemisphere) | 19,404 mm³ | ₹2/1000 | ₹38.81 |
| Waffle cone | - | - | ₹5 |
| **Total** | | | **≈ ₹65** |

**Answer: ₹65 (approximately)**

---

### Problem F3: The "Secret Surprise" (Premium with 3 Layers)

**Configuration:**
1. **Bottom 30mm:** Dark chocolate (small cone)
2. **Middle:** Vanilla cream (frustum)
3. **Top:** Full spherical scoop

**Finding the chocolate cone dimensions:**
Using similar triangles: radius/height = 21/90 = 7/30
- At height 30mm: radius = (21/90) × 30 = **7 mm**

**Chocolate cone:** r = 7 mm, h = 30 mm
- Volume = ⅓πr²h = ⅓ × (22/7) × 49 × 30 = (22 × 49 × 30)/(7 × 3) = (22 × 7 × 30)/3 = **1540 mm³**

**Vanilla cream (frustum):** = Full cone − Chocolate cone = 41,580 − 1540 = **40,040 mm³**

**Solution:**
| Component | Volume | Rate | Cost |
|-----------|--------|------|------|
| Dark chocolate (bottom cone) | 1,540 mm³ | ₹3/1000 | ₹4.62 |
| Vanilla cream (frustum) | 40,040 mm³ | ₹0.50/1000 | ₹20.02 |
| Ice cream (sphere) | 38,808 mm³ | ₹1/1000 | ₹38.81 |
| Waffle cone | - | - | ₹5 |
| **Total** | | | **≈ ₹68** |

**Answer: ₹68 (approximately)**

---

### Problem F4: The "Cornetto" Style (Bonus)

**Configuration:**
1. **Bottom 30mm:** Dark chocolate cone (same as F3)
2. **Middle:** Vanilla cream (frustum)
3. **Top:** Thick chocolate disk sealing the cone

**Chocolate disk:** radius = 21 mm, thickness = 5 mm
- Volume = πr²t = (22/7) × 441 × 5 = 22 × 63 × 5 = **6930 mm³**

**Solution:**
| Component | Volume | Rate | Cost |
|-----------|--------|------|------|
| Dark chocolate (bottom cone) | 1,540 mm³ | ₹3/1000 | ₹4.62 |
| Vanilla cream (frustum) | 40,040 mm³ | ₹0.50/1000 | ₹20.02 |
| Dark chocolate (disk) | 6,930 mm³ | ₹3/1000 | ₹20.79 |
| Waffle cone | - | - | ₹5 |
| **Total** | | | **≈ ₹50** |

**Answer: ₹50 (approximately)**

---

# FINAL ANSWER SUMMARY

| Problem | Answer | Clean? |
|---------|--------|--------|
| B1: Wafer dough volume | **2310 mm³** | ✓ |
| B2: Daily containers | **10 containers** | ✓ |
| C1: Basket surface area | **8316 mm²** | ✓ |
| C2: Basket volume | **90,552 mm³** | ✓ |
| D2: Paint for Moon model | **5544 liters** | ✓ |
| E2: Scoop volume | **38,808 mm³** | ✓ |
| F1: Classic | **≈ ₹44** | ~ |
| F2: Fully Loaded | **≈ ₹65** | ~ |
| F3: Secret Surprise | **≈ ₹68** | ~ |
| F4: Cornetto | **≈ ₹50** | ~ |

---

## Notes

1. **All geometric calculations give clean integers** using r = 21 mm (a multiple of 7)

2. **The cost answers have decimals** because:
   - Sphere volume (38,808) ÷ 1000 = 38.808
   - This is inherent to the (4/3) factor in sphere formula

3. **The frustum approach** uses Big Cone − Small Cone for both surface area and volume (grade 9 friendly!)

4. **Key Pythagorean triples used:**
   - 21-28-35 (which is 3-4-5 × 7)
   - 42-56-70 (which is 3-4-5 × 14)

5. **Similar triangles** used in F3 to find the small chocolate cone radius

---

## Verification Checks

- Small cone CSA = 2310, Big cone CSA = 9240 → Ratio = 1:4 ✓ (since linear scale = 2, area scale = 4)
- Small cone Vol = 12,936, Big cone Vol = 103,488 → Ratio = 1:8 ✓ (volume scale = 8)
- Frustum = 7 × small cone volume = 7 × 12,936 = 90,552 ✓
