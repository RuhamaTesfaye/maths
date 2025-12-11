# Lesson 5: Multiplying Complex Numbers

Now that you understand complex numbers, let's learn how to multiply them!

## The Basic Rule

To multiply complex numbers, use the **distributive property** (just like multiplying binomials in algebra).

Remember: $i^2 = -1$ (this is crucial!)

## Method 1: The FOIL Method

FOIL stands for: **F**irst, **O**uter, **I**nner, **L**ast

$$(a + bi)(c + di)$$

- **F**irst: $a \times c$
- **O**uter: $a \times di$
- **I**nner: $bi \times c$
- **L**ast: $bi \times di$

Then combine and simplify using $i^2 = -1$.

### Example 1: $(2 + 3i)(4 + 5i)$

**Step by step:**

1. **First:** $2 \times 4 = 8$
2. **Outer:** $2 \times 5i = 10i$
3. **Inner:** $3i \times 4 = 12i$
4. **Last:** $3i \times 5i = 15i^2 = 15(-1) = -15$

**Combine:**
$$8 + 10i + 12i - 15 = (8 - 15) + (10 + 12)i = -7 + 22i$$

**Answer:** $-7 + 22i$

### Example 2: $(3 + 2i)(1 - 4i)$

**Step by step:**

1. **First:** $3 \times 1 = 3$
2. **Outer:** $3 \times (-4i) = -12i$
3. **Inner:** $2i \times 1 = 2i$
4. **Last:** $2i \times (-4i) = -8i^2 = -8(-1) = 8$

**Combine:**
$$3 - 12i + 2i + 8 = (3 + 8) + (-12 + 2)i = 11 - 10i$$

**Answer:** $11 - 10i$

### Example 3: $(5 - i)(2 + 3i)$

**Step by step:**

1. **First:** $5 \times 2 = 10$
2. **Outer:** $5 \times 3i = 15i$
3. **Inner:** $(-i) \times 2 = -2i$
4. **Last:** $(-i) \times 3i = -3i^2 = -3(-1) = 3$

**Combine:**
$$10 + 15i - 2i + 3 = (10 + 3) + (15 - 2)i = 13 + 13i$$

**Answer:** $13 + 13i$

## Method 2: The Box Method (Distributive Property)

You can also organize the multiplication in a box:

**Example:** $(2 + 3i)(4 + 5i)$

```
        |   4   |  5i
   -----|-------|-------
    2   |   8   | 10i
   -----|-------|-------
   3i   |  12i  | 15i²
```

Add all terms: $8 + 10i + 12i + 15i^2 = 8 + 22i + 15(-1) = 8 + 22i - 15 = -7 + 22i$

## Special Cases

### Multiplying by a Real Number

Simply distribute the real number to both parts:

**Example 1:** $3(4 + 5i) = 12 + 15i$

**Example 2:** $-2(3 - 7i) = -6 + 14i$

### Multiplying by a Pure Imaginary Number

**Example 1:** $2i(3 + 4i)$

$$2i(3 + 4i) = 6i + 8i^2 = 6i + 8(-1) = -8 + 6i$$

**Example 2:** $5i(2 - i)$

$$5i(2 - i) = 10i - 5i^2 = 10i - 5(-1) = 5 + 10i$$

### Multiplying by $i$

When you multiply by $i$, the real part becomes imaginary and the imaginary part becomes real (and changes sign):

- $(a + bi) \times i = ai + bi^2 = ai - b = -b + ai$

**Examples:**
- $(3 + 4i) \times i = -4 + 3i$
- $(5 - 2i) \times i = -(-2) + 5i = 2 + 5i$
- $7 \times i = 7i$

## Multiplying by the Conjugate

When you multiply a complex number by its conjugate, **the result is always real**!

**Formula:**
$$(a + bi)(a - bi) = a^2 - (bi)^2 = a^2 - b^2i^2 = a^2 - b^2(-1) = a^2 + b^2$$

This is a **difference of squares** pattern!

### Examples

**Example 1:** $(3 + 4i)(3 - 4i)$

$$= 3^2 + 4^2 = 9 + 16 = 25$$

**Example 2:** $(2 - 5i)(2 + 5i)$

$$= 2^2 + 5^2 = 4 + 25 = 29$$

**Example 3:** $(1 + i)(1 - i)$

$$= 1^2 + 1^2 = 1 + 1 = 2$$

**Why is this useful?** We'll use this property to divide complex numbers in the next lesson!

## More Complex Examples

### Example 1: $(1 + 2i)(3 + 4i)(1 - i)$

Do it step by step:

**Step 1:** Multiply the first two:
$$(1 + 2i)(3 + 4i) = 3 + 4i + 6i + 8i^2 = 3 + 10i - 8 = -5 + 10i$$

**Step 2:** Multiply the result by the third:
$$(-5 + 10i)(1 - i) = -5 + 5i + 10i - 10i^2 = -5 + 15i + 10 = 5 + 15i$$

**Answer:** $5 + 15i$

### Example 2: $(2 + i)^2$

Remember: $(2 + i)^2 = (2 + i)(2 + i)$

$$(2 + i)(2 + i) = 4 + 2i + 2i + i^2 = 4 + 4i - 1 = 3 + 4i$$

**Answer:** $3 + 4i$

### Example 3: $(3 - 2i)^2$

$$(3 - 2i)(3 - 2i) = 9 - 6i - 6i + 4i^2 = 9 - 12i - 4 = 5 - 12i$$

**Answer:** $5 - 12i$

## Pattern: $(a + bi)^2$

There's a shortcut formula (similar to $(x + y)^2 = x^2 + 2xy + y^2$):

$$(a + bi)^2 = a^2 + 2abi + (bi)^2 = a^2 + 2abi + b^2i^2 = a^2 - b^2 + 2abi$$

**Simplified:**
$$(a + bi)^2 = (a^2 - b^2) + (2ab)i$$

**Example:** $(4 + 3i)^2$
$$= (4^2 - 3^2) + (2 \times 4 \times 3)i = (16 - 9) + 24i = 7 + 24i$$

## Properties of Complex Multiplication

### 1. Commutative Property
Order doesn't matter:
$$(a + bi)(c + di) = (c + di)(a + bi)$$

**Example:** $(2 + 3i)(1 + i) = (1 + i)(2 + 3i)$ both equal $-1 + 5i$

### 2. Associative Property
Grouping doesn't matter:
$$[(a + bi)(c + di)](e + fi) = (a + bi)[(c + di)(e + fi)]$$

### 3. Distributive Property
$$(a + bi)[(c + di) + (e + fi)] = (a + bi)(c + di) + (a + bi)(e + fi)$$

### 4. Identity Element
Multiplying by 1 doesn't change the number:
$$(a + bi) \times 1 = a + bi$$

### 5. Zero Property
Multiplying by 0 gives 0:
$$(a + bi) \times 0 = 0$$

## Absolute Value of a Product

An important property:
$$|z_1 \times z_2| = |z_1| \times |z_2|$$

**Example:** $|(3 + 4i)(1 + i)|$

**Method 1 (multiply first):**
- $(3 + 4i)(1 + i) = 3 + 3i + 4i + 4i^2 = 3 + 7i - 4 = -1 + 7i$
- $|-1 + 7i| = \sqrt{(-1)^2 + 7^2} = \sqrt{1 + 49} = \sqrt{50} = 5\sqrt{2}$

**Method 2 (use property):**
- $|3 + 4i| = \sqrt{9 + 16} = 5$
- $|1 + i| = \sqrt{1 + 1} = \sqrt{2}$
- $|z_1 \times z_2| = 5 \times \sqrt{2} = 5\sqrt{2}$ ✓

Both methods give the same answer!

## Common Mistakes to Avoid

❌ **Mistake 1:** Forgetting that $i^2 = -1$
- Wrong: $(2 + i)(3 + i) = 6 + 5i + i^2 = 6 + 5i + 1$
- Right: $(2 + i)(3 + i) = 6 + 5i - 1 = 5 + 5i$

❌ **Mistake 2:** Not combining like terms correctly
- Wrong: $(1 + 2i)(3 + i) = 3 + 7i$
- Right: $(1 + 2i)(3 + i) = 3 + i + 6i + 2i^2 = 1 + 7i$

❌ **Mistake 3:** Sign errors with negatives
- Wrong: $(2 - i)(1 - 3i) = 2 - 6i - i - 3i^2 = 2 - 7i - 3$
- Right: $(2 - i)(1 - 3i) = 2 - 6i - i + 3i^2 = 2 - 7i - 3 = -1 - 7i$

## Practice Strategy

**3-Step Process:**
1. **FOIL** or distribute
2. **Replace** $i^2$ with $-1$
3. **Combine** like terms (real with real, imaginary with imaginary)

## Key Takeaways

1. Use **FOIL** or the **distributive property**
2. Always replace $i^2$ with $-1$
3. Combine **real parts** and **imaginary parts** separately
4. $(a + bi)(a - bi) = a^2 + b^2$ (always real!)
5. $(a + bi)^2 = (a^2 - b^2) + 2abi$
6. $|z_1 \times z_2| = |z_1| \times |z_2|$

## Next Steps

You've mastered multiplication! Now let's tackle the trickiest part: **dividing complex numbers**!

---

**Ready to practice?** Open `Exercise_5.md` to master complex multiplication!
