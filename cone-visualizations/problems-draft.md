# Surface Areas & Volumes - Problem Set Draft

## Mathematical Convention
**We use: 32π = 100, which means π = 100/32 = 3.125**

This gives us:
- π ≈ 3.125
- 8π = 25
- 16π = 50
- 64π = 200
- 128π = 400

---

## SECTION 1: CONE VISUALIZATIONS (Interactive)

### 1.1 Surface Area of Cone
- Interactive slider for height (0 to 20 cm)
- Shows how CSA changes
- When h = 0, cone becomes circle (CSA = πr²)
- Formula: CSA = πrl, where l = √(r² + h²)

### 1.2 Volume of Cone
- Interactive visualization
- Shows cone is ⅓ of cylinder
- Formula: V = ⅓πr²h

---

## SECTION 2: ICE CREAM CONE MANUFACTURING

### Problem 2.1: Volume of Wafer (Cone Shell)

**Context:** You're the production engineer at Creamistry Ice Cream Factory.

**Given:**
- Cone height (h) = 12 cm
- Cone radius (r) = 4 cm
- Wafer thickness (t) = 0.5 cm

**Method:** Volume of thin shell ≈ Surface Area × Thickness

**Solution:**
1. Find slant height: l = √(r² + h²) = √(16 + 144) = √160 = 4√10 ≈ 12.65 cm

   *Let me recalculate with better numbers...*

**REVISED - Using nicer numbers:**
- Cone height (h) = 12 cm
- Cone radius (r) = 5 cm
- Wafer thickness (t) = 0.4 cm

1. Slant height: l = √(25 + 144) = √169 = **13 cm** ✓ (perfect!)
2. Curved Surface Area = πrl = π × 5 × 13 = 65π cm²
3. Base Area = πr² = 25π cm²
4. Total Surface Area = 65π + 25π = 90π cm²

   Hmm, 90π doesn't give a nice number with 32π = 100...

**REVISED AGAIN - Optimizing for 32π = 100:**

Let's choose r and l such that πrl is a multiple of 32π:
- If r = 4, l = 8 → πrl = 32π = 100 cm² ✓
- Need h = √(l² - r²) = √(64 - 16) = √48 ≈ 6.93 (not nice)

Let's try:
- r = 3, l = 5 → h = √(25-9) = 4 ✓
- πrl = 15π (not great)

Let's try:
- r = 6, l = 10 → h = √(100-36) = 8 ✓
- πrl = 60π (not a multiple of 32)

Let's try:
- r = 8, l = 10 → h = √(100-64) = 6 ✓
- πrl = 80π = 250 cm² ✓

**FINAL CHOICE for Cone:**
- **Radius (r) = 8 cm**
- **Height (h) = 6 cm**
- **Slant height (l) = 10 cm** (since 8² + 6² = 64 + 36 = 100 = 10²)

**Calculations:**
- Curved Surface Area = πrl = π × 8 × 10 = 80π = **250 cm²**
- Base Area = πr² = 64π = **200 cm²**
- Total Surface Area = 80π + 64π = 144π = **450 cm²**

**With thickness = 0.4 cm:**
- Volume of wafer = Surface Area × thickness = 450 × 0.4 = **180 cm³**

---

### Problem 2.2: Daily Production

**Given:**
- Volume per cone = 180 cm³
- Daily production = 5000 cones
- Dough comes in 30-liter containers

**Solution:**
1. Total dough needed = 180 × 5000 = 900,000 cm³
2. Convert to liters = 900,000 ÷ 1000 = 900 liters
3. Containers needed = 900 ÷ 30 = **30 containers**

---

## SECTION 3: PREMIUM WAFFLE BASKET (Frustum)

### Problem 3.1: Surface Area of Waffle Basket

**Shape:** Frustum (truncated cone) with circular base

**Given:**
- Bottom radius (r) = 4 cm
- Top radius (R) = 8 cm
- Slant height of frustum (l) = 8 cm

**Note:** The frustum is like a big cone with a smaller cone cut off from the top.

**Solution:**

*Finding the complete cone dimensions:*
Since the radii are in ratio 4:8 = 1:2, the small cone is half the size of the big cone.
- If frustum slant height = 8 cm, then small cone slant height = 8 cm, big cone slant height = 16 cm
- Small cone: r = 4 cm, l = 8 cm
- Big cone: R = 8 cm, L = 16 cm

**Method: Frustum CSA = Big Cone CSA - Small Cone CSA**

1. Big cone CSA = πRL = π × 8 × 16 = 128π = **400 cm²**
2. Small cone CSA = πrl = π × 4 × 8 = 32π = **100 cm²**
3. Frustum CSA = 128π - 32π = 96π = **300 cm²**

*Alternative formula: CSA = π(R + r)l = π(8 + 4) × 8 = 96π = 300 cm²* ✓

4. Base area (circular bottom) = πr² = π × 4² = 16π = **50 cm²**

5. **Total Surface Area = 300 + 50 = 350 cm²**

---

### Problem 3.2: Volume of Waffle Basket

**Method: Frustum Volume = Big Cone Volume - Small Cone Volume**

*Finding heights:*
- Small cone: r = 4, l = 8 → h = √(64-16) = √48 = 4√3 ≈ 6.93 (not nice)

**Let me rechoose numbers for nice heights too...**

**REVISED FRUSTUM DIMENSIONS:**

Using 3-4-5 right triangle scaling:
- Small cone: r = 3 cm, h = 4 cm, l = 5 cm
- Big cone: R = 6 cm, H = 8 cm, L = 10 cm
- Frustum: bottom r = 3 cm, top R = 6 cm, height = 4 cm, slant height = 5 cm

**Surface Area:**
1. Big cone CSA = π × 6 × 10 = 60π
2. Small cone CSA = π × 3 × 5 = 15π
3. Frustum CSA = 60π - 15π = 45π

Hmm, 45π doesn't give nice integer with 32π = 100...

**REVISED AGAIN with 32π = 100 in mind:**

Let's use:
- Small cone: r = 4 cm, h = 3 cm, l = 5 cm (3-4-5 triangle)
- Big cone: R = 8 cm, H = 6 cm, L = 10 cm (scaled by 2)
- Frustum height = 6 - 3 = 3 cm
- Frustum slant height = 10 - 5 = 5 cm

**Surface Area Check:**
1. Big cone CSA = π × 8 × 10 = 80π = 250 cm²
2. Small cone CSA = π × 4 × 5 = 20π = 62.5 cm²  (not nice)

**Let me try different approach - work backwards from nice answers:**

For 32π = 100:
- 32π = 100
- 64π = 200
- 96π = 300
- 128π = 400

For frustum CSA = π(R+r)l to equal 96π = 300:
- (R+r)l = 96
- Options: (R+r)=12, l=8 or (R+r)=16, l=6 or (R+r)=8, l=12

Let's try (R+r) = 12, l = 8, with R = 8, r = 4:
- Need to verify this is geometrically valid
- The ratio of radii = 8:4 = 2:1
- So big cone L = 16, small cone l = 8
- Frustum slant height = 16 - 8 = 8 ✓

For heights (using R/L = r/l for similar triangles):
- Big cone: R = 8, L = 16, so H = √(256-64) = √192 = 8√3 ≈ 13.86 (not nice)

**FINAL APPROACH - Accept some non-integer intermediates:**

**FINAL WAFFLE BASKET DIMENSIONS:**
- Bottom radius (r) = 4 cm
- Top radius (R) = 8 cm
- Slant height of frustum (l) = 8 cm
- Frustum height (h) = √(l² - (R-r)²) = √(64 - 16) = √48 ≈ 6.93 cm

**Surface Area (main focus):**
1. Frustum CSA = π(R + r) × l = π × 12 × 8 = 96π = **300 cm²**
2. Base area = πr² = 16π = **50 cm²**
3. **Total Surface Area = 350 cm²** ✓

**Volume:**
- Frustum volume = (πh/3)(R² + Rr + r²) = (π × 6.93/3)(64 + 32 + 16) = (2.31π)(112)

This is getting messy. Let me use whole numbers by adjusting.

**SIMPLEST APPROACH - Use approximation:**

Let's just state frustum height = 7 cm (approximately) for calculations.

Volume = (π × 7/3)(64 + 32 + 16) = (7π/3)(112) = 784π/3 ≈ 261.3π

Still messy. Let me redesign completely.

---

## COMPLETE REDESIGN WITH CLEAN NUMBERS

### Convention: π = 3.125, so 32π = 100

### THE ICE CREAM CONE (Used throughout)

**Dimensions:**
- Radius (r) = 4 cm
- Height (h) = 3 cm
- Slant height (l) = 5 cm (since 3² + 4² = 5²) ✓

**Calculated values:**
- Curved Surface Area = πrl = π × 4 × 5 = 20π = **62.5 cm²**
- Base Area = πr² = 16π = **50 cm²**
- Total Surface Area = 36π = **112.5 cm²**
- Volume = ⅓πr²h = ⅓ × 16π × 3 = 16π = **50 cm³**

Hmm, 62.5 is not an integer...

**Let me try r = 8, h = 6, l = 10:**
- CSA = π × 8 × 10 = 80π = 250 cm²
- Base = 64π = 200 cm²
- Volume = ⅓ × 64π × 6 = 128π = 400 cm³ ✓

This works! Let's scale down for realistic ice cream:

**FINAL ICE CREAM CONE:**
- Radius (r) = 4 cm
- Height (h) = 3 cm
- Slant height (l) = 5 cm

With 32π = 100 (π = 3.125):
- CSA = 20π = 20 × 3.125 = **62.5 cm²**
- Base = 16π = **50 cm²**
- Volume = 16π = **50 cm³**

The 62.5 isn't ideal. Let me try once more...

**ALTERNATIVE: Use 8π = 25 as base unit**

With π = 25/8 = 3.125:
- 8π = 25
- 16π = 50
- 24π = 75
- 32π = 100
- 40π = 125
- 48π = 150
- 64π = 200
- 80π = 250
- 96π = 300
- 128π = 400

For CSA = πrl to be nice, need rl to be multiple of 8:
- r=4, l=2 → rl=8 → CSA=8π=25 ✓
- r=4, l=4 → rl=16 → CSA=16π=50 ✓
- r=4, l=6 → rl=24 → CSA=24π=75 ✓
- r=4, l=8 → rl=32 → CSA=32π=100 ✓
- r=8, l=4 → rl=32 → CSA=32π=100 ✓

For r=4, l=8: h = √(64-16) = √48 ≈ 6.93 (not nice)
For r=8, l=10: h = √(100-64) = 6 ✓

**FINAL CONE DIMENSIONS:**
- **r = 8 cm, h = 6 cm, l = 10 cm**
- CSA = 80π = **250 cm²**
- Volume = ⅓ × 64π × 6 = 128π = **400 cm³**

---

# FINAL PROBLEM SET

## Convention: 32π = 100 (i.e., π ≈ 3.125)
## Mention: "For easier calculation, we use 32π = 100"

---

## PART A: CONE BASICS (Interactive Visualizations)

### A1: Surface Area Explorer
*Interactive - drag height, see CSA change*

### A2: Volume Explorer
*Shows cone = ⅓ cylinder*

---

## PART B: ICE CREAM CONE MANUFACTURING

### THE CONE SPECIFICATIONS:
- **Radius = 8 cm**
- **Height = 6 cm**
- **Slant height = 10 cm** (verify: 8² + 6² = 64 + 36 = 100 = 10²) ✓
- **Wafer thickness = 0.4 cm**

---

### Problem B1: Wafer Volume for One Cone

**Question:** How much wafer dough is needed to make one ice cream cone?

**Given:**
- Cone: r = 8 cm, h = 6 cm, l = 10 cm
- Thickness = 0.4 cm

**Solution:**
For a thin shell, Volume ≈ Surface Area × Thickness

1. Curved Surface Area = πrl = π × 8 × 10 = 80π = **250 cm²**
2. Base is open (no wafer at bottom for ice cream cone)
3. Volume = 250 × 0.4 = **100 cm³**

**Answer: 100 cm³ of dough per cone**

---

### Problem B2: Daily Dough Requirement

**Question:** The factory produces 5,000 cones daily. Dough comes in 50-liter drums. How many drums are needed?

**Solution:**
1. Dough per cone = 100 cm³
2. Total daily = 100 × 5000 = 500,000 cm³
3. In liters = 500,000 ÷ 1000 = 500 liters
4. Drums needed = 500 ÷ 50 = **10 drums**

**Answer: 10 drums per day**

---

## PART C: PREMIUM WAFFLE BASKET (Frustum)

### THE BASKET SPECIFICATIONS:
- Bottom radius (r) = 4 cm
- Top radius (R) = 8 cm
- Slant height (l) = 8 cm
- Has a circular base at the bottom

*Visual: Show the frustum as difference of two similar cones*

---

### Problem C1: Surface Area of Waffle Basket

**Question:** Find the total surface area of the waffle basket.

**Key Insight:**
- The radii ratio is 4:8 = 1:2
- So the small cone (cut off) has slant height 8 cm
- The big cone has slant height 16 cm

**Solution:**

Method: Frustum CSA = Large Cone CSA − Small Cone CSA

1. Large cone CSA = π × R × L = π × 8 × 16 = 128π = **400 cm²**
2. Small cone CSA = π × r × l = π × 4 × 8 = 32π = **100 cm²**
3. Frustum CSA = 128π − 32π = 96π = **300 cm²**

4. Circular base area = πr² = π × 4² = 16π = **50 cm²**

5. **Total Surface Area = 300 + 50 = 350 cm²**

---

### Problem C2: Volume of Waffle Basket

**Question:** Find the volume of ice cream the basket can hold.

**Given (additional):**
- Large cone height H = √(16² - 8²) = √(256-64) = √192 ≈ 13.86 cm
- Small cone height h = √(8² - 4²) = √(64-16) = √48 ≈ 6.93 cm

*Note: Heights aren't nice, but volumes will work out*

**Solution:**

Method: Frustum Volume = Large Cone Volume − Small Cone Volume

1. Large cone volume = ⅓πR²H = ⅓ × π × 64 × 13.86 = ⅓ × 887.04π
2. Small cone volume = ⅓πr²h = ⅓ × π × 16 × 6.93 = ⅓ × 110.88π
3. Frustum volume = ⅓π(887.04 - 110.88) = ⅓ × 776.16π

This is messy. Let me use the direct formula instead:

**Frustum Volume Formula:** V = (πh/3)(R² + Rr + r²)

where h = height of frustum = H - small h = 13.86 - 6.93 = 6.93 cm

V = (π × 6.93/3)(64 + 32 + 16) = (2.31π)(112) = 258.72π

Still messy.

**REDESIGN FRUSTUM FOR NICE VOLUME:**

Let me choose frustum dimensions that give nice volume.

For V = (πh/3)(R² + Rr + r²) to be nice multiple of 32π:

If R = 8, r = 4, then R² + Rr + r² = 64 + 32 + 16 = 112

Need (h/3) × 112 to be multiple of 32:
- h = 6: (6/3) × 112 = 2 × 112 = 224 (not multiple of 32)
- h = 12: (12/3) × 112 = 4 × 112 = 448 = 14 × 32 ✓

So with h = 12, Volume = 448π = 14 × 100 = **1400 cm³**

But wait, need to check if h=12 is consistent with slant height.
Frustum slant height² = h² + (R-r)² = 144 + 16 = 160
l = √160 ≈ 12.65 (not nice)

**TRY: R = 6, r = 3**
R² + Rr + r² = 36 + 18 + 9 = 63

Hmm, 63 doesn't factor nicely with 32.

**TRY: R = 8, r = 2**
R² + Rr + r² = 64 + 16 + 4 = 84

**TRY: R = 6, r = 2**
R² + Rr + r² = 36 + 12 + 4 = 52

**TRY: R = 4, r = 2**
R² + Rr + r² = 16 + 8 + 4 = 28

If h = 12: (12/3) × 28 = 4 × 28 = 112 → Volume = 112π = 350 cm³ ✓

Check geometry:
- Ratio of radii = 2:4 = 1:2
- If small cone l = L, big cone l = 2L
- Frustum slant = L
- For similar cones with r=2: small cone h₁, and R=4: big cone h₂=2h₁
- Frustum height = 2h₁ - h₁ = h₁ = 12
- So small cone h = 12, big cone H = 24
- Small cone: r=2, h=12, l = √(4+144) = √148 ≈ 12.17
- Big cone: R=4, H=24, L = √(16+576) = √592 ≈ 24.33
- Frustum slant = 24.33 - 12.17 = 12.16 ≈ 12 (close enough, can use 12)

Actually for clean slant height, let me try 3-4-5:
- Small cone: r=3, h=4, l=5
- Big cone: R=6, H=8, L=10
- Frustum: h=4, slant l=5, r=3, R=6

R² + Rr + r² = 36 + 18 + 9 = 63
Volume = (π×4/3)(63) = (4/3)(63)π = 84π = 262.5 cm³ (not integer!)

Ugh. Let me try:
- Small cone: r=4, h=3, l=5
- Big cone: R=8, H=6, L=10
- Frustum: h=3, slant l=5, r=4, R=8

R² + Rr + r² = 64 + 32 + 16 = 112
Volume = (π×3/3)(112) = 112π = **350 cm³** ✓✓✓

And slant height l = √(3² + 4²) = 5 ✓ (using (R-r)=4, h=3)

**FINAL WAFFLE BASKET:**
- Bottom radius r = 4 cm
- Top radius R = 8 cm
- Height h = 3 cm
- Slant height l = 5 cm

**Verification:**
- Frustum slant² = h² + (R-r)² = 9 + 16 = 25 = 5² ✓

**For the two-cones visualization:**
- Radii ratio = 4:8 = 1:2
- So heights ratio = 1:2 → small cone h=3, big cone H=6
- Small cone: r=4, h=3, l=5
- Big cone: R=8, H=6, L=10

**CSA calculation:**
1. Big cone CSA = π × 8 × 10 = 80π = 250 cm²
2. Small cone CSA = π × 4 × 5 = 20π = 62.5 cm²
3. Frustum CSA = 80π - 20π = 60π = **187.5 cm²**

Hmm, 187.5 is not integer. But 60π isn't a multiple of 8π...

**ALTERNATIVE: Use π(R+r)l directly:**
CSA = π × (8+4) × 5 = 60π = 187.5 cm²

Let me try to get both CSA and Volume as integers...

For CSA = π(R+r)l to be multiple of 8π: (R+r)l must be multiple of 8
- (8+4)×5 = 60 (not multiple of 8)
- (6+2)×4 = 32 ✓
- (8+4)×4 = 48 = 6×8 ✓ → CSA = 48π = 150 cm²

For (8+4)×4: R=8, r=4, l=4
Frustum slant = 4, (R-r) = 4
h = √(16-16) = 0 ???

That's flat! Let me try (6+2)×4 = 32:
R=6, r=2, l=4
(R-r) = 4, so h = √(16-16) = 0 again!

The issue is when (R-r) = l, height becomes 0.

Need (R-r) < l.

**(R+r)l = 48 with (R-r) < l:**
- R=7, r=5, l=4: (R-r)=2 < 4 ✓, h=√(16-4)=√12≈3.46
- R=10, r=2, l=4: (R-r)=8 > 4 ✗
- R=8, r=4, l=6: (R-r)=4 < 6 ✓, h=√(36-16)=√20≈4.47

Let's try (R+r)l = 64 (so CSA = 64π = 200):
- R=8, r=8, l=4: that's a cylinder!
- R=12, r=4, l=4: (R-r)=8>4 ✗
- R=10, r=6, l=4: (R-r)=4=l → h=0 ✗
- R=9, r=7, l=4: (R-r)=2<4, h=√(16-4)=√12
- R=8, r=4, l=8: (R-r)=4<8, h=√(64-16)=√48≈6.93

Okay none of these give nice heights.

---

## FINAL DECISION: Accept some half-integer answers

Let's use the 3-4-5 based frustum and accept answers like 187.5 and 350:

**WAFFLE BASKET FINAL:**
- r = 4 cm, R = 8 cm, h = 3 cm, l = 5 cm
- CSA = 60π = **187.5 cm²** (or express as 187½ cm²)
- Base = 16π = **50 cm²**
- Total SA = 76π = **237.5 cm²**
- Volume = 112π = **350 cm³**

Actually, let me just rescale everything by 2:

**WAFFLE BASKET (SCALED):**
- r = 8 cm, R = 16 cm, h = 6 cm, l = 10 cm
- CSA = π(R+r)l = π × 24 × 10 = 240π = **750 cm²**
- Base = π × 64 = 64π = **200 cm²**
- Total SA = 304π = **950 cm²**
- Volume = (πh/3)(R² + Rr + r²) = (6π/3)(256+128+64) = 2π × 448 = 896π = **2800 cm³**

These are clean! But the basket is quite large (16 cm top radius = 32 cm diameter!).

---

# SIMPLIFIED FINAL APPROACH

Let me keep calculations simpler and just ensure the FINAL answers are nice.

## FINAL PROBLEM SET v2

### Convention: 32π = 100

---

## PART B: ICE CREAM CONE

**Cone dimensions: r = 8 cm, h = 6 cm, l = 10 cm**

### B1: Wafer Volume
- CSA = 80π = 250 cm²
- Thickness = 0.4 cm
- **Volume = 100 cm³** ✓

### B2: Daily Production
- 5000 cones × 100 cm³ = 500,000 cm³ = 500 L
- 50 L drums → **10 drums** ✓

---

## PART C: WAFFLE BASKET

**Basket dimensions: r = 4 cm, R = 8 cm, h = 3 cm, l = 5 cm**

### C1: Surface Area
- Frustum CSA = 60π = 187.5 cm²
- Base = 16π = 50 cm²
- **Total = 237.5 cm²** (Accept this)

### C2: Volume
- **Volume = 112π = 350 cm³** ✓

---

## PART D: SPHERE BASICS

### D1: Surface Area Formula (Statement only)
**Surface Area of Sphere = 4πr²**

### D2: Painting the Moon Problem

**Question:** The Moon has a radius of 1,600 km. We want to paint it with blue paint that is 1 mm thick. How many liters of paint do we need?

**Solution:**
1. Moon surface area = 4πr² = 4π × (1600)² km² = 4π × 2,560,000 km²
2. Converting: 1 km² = 10⁶ m² = 10¹² mm²
3. So surface area = 4π × 2,560,000 × 10¹² mm² = 10.24 × 10¹⁸ × π mm²
4. Volume of paint = Area × thickness = 10.24 × 10¹⁸ × π × 1 mm³

Hmm, this is getting into very large numbers. Let me simplify.

**SIMPLIFIED MOON PROBLEM:**

**Question:** A spherical ball has radius 40 cm. We paint it with a 0.5 cm thick coat. Find the volume of paint used.

**Solution:**
1. Surface area = 4πr² = 4π × 40² = 4π × 1600 = 6400π = **20,000 cm²**
2. Volume of paint = 20,000 × 0.5 = **10,000 cm³ = 10 liters** ✓

Even better, let's use radius = 20 cm:
- Surface area = 4π × 400 = 1600π = 5000 cm²
- With 0.2 cm paint: Volume = 5000 × 0.2 = **1000 cm³ = 1 liter** ✓

**FINAL MOON-PAINT PROBLEM:**
- Sphere radius = 20 cm
- Paint thickness = 0.2 cm (2 mm)
- Surface area = 1600π = **5000 cm²**
- Paint volume = **1000 cm³ = 1 liter** ✓

---

## PART E: SPHERE VOLUME

### E1: Volume Formula (Statement + Visual)
**Volume of Sphere = (4/3)πr³**

---

## PART F: ICE CREAM COST PROBLEMS

**Setup:**
- Ice cream cone: r = 4 cm, h = 3 cm (smaller, realistic cone)
  - l = 5 cm (3-4-5 triangle)
  - Volume = ⅓π × 16 × 3 = 16π = **50 cm³**

- Costs:
  - Cream: ₹0.10 per cm³
  - Ice cream: ₹0.05 per cm³
  - Dark chocolate: ₹0.20 per cm³
  - Wafer cone: ₹2 per cone (fixed)

Let me verify 16π = 50 with 32π = 100: 16π = 100/2 = 50 ✓

### F1: Empty Cone + Spherical Scoop

**Question:** An empty wafer cone has a spherical scoop of ice cream on top. The scoop just fits on the cone opening (radius = 4 cm). Find the cost.

**Solution:**
1. Sphere radius = 4 cm
2. Sphere volume = (4/3)πr³ = (4/3)π × 64 = (256/3)π = 85.33π

Hmm, 256/3 doesn't give nice number...

**Let me use r = 3 cm for scoop:**
- Volume = (4/3)π × 27 = 36π = **112.5 cm³**

Still not integer. The issue is the 4/3 in sphere formula.

**For (4/3)πr³ to give multiple of 8π:**
(4/3)r³ must be multiple of 8
4r³/3 = 8k
r³ = 6k

For k=1: r³=6 (not perfect cube)
For k=4: r³=24 (not perfect cube)
For k=9: r³=54 (not perfect cube)
For k=36: r³=216=6³ ✓ → r=6

So r=6: Volume = (4/3)π×216 = 288π = **900 cm³** ✓

**ADJUSTED DIMENSIONS:**
- Cone: r = 6 cm (opening), h = 8 cm
  - l = 10 cm (6-8-10 is 3-4-5 scaled by 2) ✓
  - Cone volume = ⅓π × 36 × 8 = 96π = **300 cm³** ✓

- Ice cream scoop: r = 6 cm
  - Volume = 288π = **900 cm³** ✓

- Hemisphere: r = 6 cm
  - Volume = (2/3)π × 216 = 144π = **450 cm³** ✓

**PRICING (adjusted for reasonable costs):**
- Cream: ₹0.02 per cm³ (₹20 per liter)
- Ice cream: ₹0.04 per cm³ (₹40 per liter)
- Dark chocolate: ₹0.10 per cm³ (₹100 per liter)
- Wafer cone: ₹5 per cone

---

### F1: Empty Cone + Full Spherical Scoop

**Question:** An empty cone with a spherical scoop of ice cream on top. Find the cost.

**Given:**
- Cone (empty): r = 6 cm, h = 8 cm
- Scoop (sphere): r = 6 cm
- Ice cream cost: ₹0.04/cm³
- Cone cost: ₹5

**Solution:**
1. Ice cream volume = 288π = 900 cm³
2. Ice cream cost = 900 × 0.04 = **₹36**
3. Cone cost = ₹5
4. **Total = ₹41**

---

### F2: Cream-filled Cone + Hemisphere Scoop

**Question:** Cone filled with cream, plus a hemispherical ice cream scoop on top.

**Given:**
- Cone volume: 96π = 300 cm³ (filled with cream)
- Hemisphere: 144π = 450 cm³ (ice cream)
- Cream cost: ₹0.02/cm³
- Ice cream cost: ₹0.04/cm³
- Cone cost: ₹5

**Solution:**
1. Cream cost = 300 × 0.02 = **₹6**
2. Ice cream cost = 450 × 0.04 = **₹18**
3. Cone cost = ₹5
4. **Total = ₹29**

---

### F3: Premium Ice Cream

**Question:** Premium cone with:
- Dark chocolate at the bottom (small cone, r=3 cm, h=4 cm)
- Cream in the remaining cone space
- Full spherical scoop on top

**Given:**
- Small chocolate cone: r=3, h=4 → Volume = ⅓π×9×4 = 12π = **37.5 cm³**

Hmm, 12π = 37.5, not integer. Let me adjust.

**For chocolate cone volume to be nice:**
⅓πr²h should give multiple of 8π
r²h/3 = 8k
r²h = 24k

Options:
- r=2, h=6: r²h=24 ✓ → Volume = 8π = 25 cm³ ✓
- r=3, h=8: r²h=72 → Volume = 24π = 75 cm³ ✓
- r=4, h=6: r²h=96 → Volume = 32π = 100 cm³ ✓

Let me use:
- **Main cone: r=6, h=8** (Volume = 96π = 300 cm³)
- **Chocolate mini-cone at bottom: r=3, h=4** (this is similar, half-scale)
  - Volume = (1/8) × 300 = 37.5 cm³... still not nice

Actually for similar cones, if linear scale = 1/2, volume scale = 1/8.
So chocolate cone = 300/8 = 37.5 cm³

Let me just accept 37.5 or round to 38 cm³.

**OR use different chocolate portion:**

What if chocolate is just a small hemisphere at the bottom?
- Hemisphere r=3: Volume = (2/3)π×27 = 18π = 56.25 cm³ (not nice)

What if chocolate fills bottom 2 cm of the cone?
- That's a smaller similar cone with h=2 (vs original h=8, so scale=1/4)
- Volume = (1/4)³ × 300 = 300/64 = 4.69 cm³ (too small anyway)

**SIMPLEST APPROACH:** Use chocolate as a fixed amount

- Chocolate: 50 cm³ (we just specify this)
- Cream: fills remaining cone = 300 - 50 = 250 cm³
- Ice cream sphere: 900 cm³

**Solution:**
1. Chocolate cost = 50 × 0.10 = **₹5**
2. Cream cost = 250 × 0.02 = **₹5**
3. Ice cream cost = 900 × 0.04 = **₹36**
4. Cone cost = ₹5
5. **Total = ₹51**

---

### F4: Cornetto Style (Bonus)

**Question:** Cornetto with:
- Dark chocolate at the bottom (50 cm³)
- Circular chocolate disc on top (seals the cone, radius 6 cm, thickness 0.5 cm)
- Cream filling the cone (between chocolate bottom and disc top)

**Given:**
- Cone: r=6, h=8, Volume=300 cm³
- Chocolate bottom: 50 cm³
- Cream: 300 - 50 = 250 cm³
- Chocolate disc: πr²t = π×36×0.5 = 18π = 56.25 cm³

Hmm, 18π = 56.25. Let me use thickness = 4/9 cm ≈ 0.44 cm to get 16π = 50 cm³.

Actually let me use thickness = 0.4 cm:
- Disc volume = π×36×0.4 = 14.4π = 45 cm³ (close to 50, ok)

**Use thickness = 32/36 = 8/9 cm to get exactly 32π = 100 cm³:**
- Disc volume = π×36×(8/9) = 32π = 100 cm³ ✓

So disc is about 0.89 cm ≈ 9mm thick (reasonable for chocolate disc).

**F4 Solution:**
1. Chocolate bottom: 50 × 0.10 = **₹5**
2. Chocolate disc: 100 × 0.10 = **₹10**
3. Cream filling: 250 × 0.02 = **₹5**
4. Cone cost: **₹5**
5. **Total = ₹25**

Wait, this is cheaper than F3 because there's no ice cream scoop! Let me re-read the problem...

Oh, Cornetto-style doesn't have ice cream on top - it's all inside with cream and chocolate.

**But for fairness with F3, let me add that Cornetto is smaller portion:**

Actually the comparison is:
- F3 (Premium): Has 900 cm³ ice cream on top → ₹51
- F4 (Cornetto): No ice cream on top, all inside → ₹25

That makes sense! Cornetto is cheaper because it's smaller total volume.

---

# SUMMARY OF ALL PROBLEMS

## Convention: 32π = 100

## Part B: Ice Cream Cone Manufacturing
**Cone: r = 8 cm, h = 6 cm, l = 10 cm**

| Problem | Given | Answer |
|---------|-------|--------|
| B1: Wafer volume | CSA=250cm², t=0.4cm | **100 cm³** |
| B2: Daily drums | 5000 cones, 50L drums | **10 drums** |

## Part C: Waffle Basket
**Basket: r=4cm, R=8cm, h=3cm, l=5cm**

| Problem | Method | Answer |
|---------|--------|--------|
| C1: Surface Area | Frustum CSA + Base | **237.5 cm²** |
| C2: Volume | Frustum formula | **350 cm³** |

## Part D: Sphere Surface Area
| Problem | Given | Answer |
|---------|-------|--------|
| D1: Formula | - | SA = 4πr² |
| D2: Paint volume | r=20cm, t=0.2cm | **1000 cm³ = 1 liter** |

## Part E: Sphere Volume
| Problem | Given | Answer |
|---------|-------|--------|
| E1: Formula | - | V = (4/3)πr³ |

## Part F: Ice Cream Costs
**Cone: r=6cm, h=8cm | Scoop: r=6cm**
**Costs: Cream ₹0.02/cm³, Ice cream ₹0.04/cm³, Chocolate ₹0.10/cm³, Cone ₹5**

| Problem | Contents | Volume | Cost |
|---------|----------|--------|------|
| F1: Basic | Empty cone + sphere scoop | 0 + 900 | **₹41** |
| F2: Cream-filled | Cream cone + hemisphere | 300 + 450 | **₹29** |
| F3: Premium | Chocolate(50) + cream(250) + sphere | 50+250+900 | **₹51** |
| F4: Cornetto | Chocolate(50) + cream(250) + choc disc(100) | 50+250+100 | **₹25** |

---

**Note:**
- C1 answer (237.5) is not an integer - acceptable?
- All other answers are integers ✓
- Should I adjust C1 dimensions to get integer surface area?
