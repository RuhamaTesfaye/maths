# Lesson 6: Dividing Complex Numbers

Welcome to the final operation: **division**! This is where the conjugate becomes incredibly useful.

## The Challenge

How do we divide complex numbers?

$$\frac{2 + 3i}{4 + 5i} = ?$$

We can't just divide the parts separately (that doesn't work). We need a clever trick!

## The Key Idea: Rationalize the Denominator

**Goal:** Make the denominator a real number (no imaginary part).

**Method:** Multiply both numerator and denominator by the **conjugate** of the denominator.

Remember from Lesson 5: $(a + bi)(a - bi) = a^2 + b^2$ (always real!)

## The Division Formula

$$\frac{a + bi}{c + di} = \frac{a + bi}{c + di} \times \frac{c - di}{c - di}$$

This is multiplying by 1 (in a clever way), so we don't change the value.

**Steps:**
1. Find the conjugate of the denominator
2. Multiply numerator and denominator by this conjugate
3. Simplify the numerator using FOIL
4. Simplify the denominator (it becomes $c^2 + d^2$)
5. Write in standard form $a + bi$

## Example 1: $\frac{2 + 3i}{1 - i}$

**Step 1:** Conjugate of denominator $(1 - i)$ is $(1 + i)$

**Step 2:** Multiply:
$$\frac{2 + 3i}{1 - i} \times \frac{1 + i}{1 + i}$$

**Step 3:** Simplify numerator:
$$(2 + 3i)(1 + i) = 2 + 2i + 3i + 3i^2 = 2 + 5i - 3 = -1 + 5i$$

**Step 4:** Simplify denominator:
$$(1 - i)(1 + i) = 1^2 + 1^2 = 1 + 1 = 2$$

**Step 5:** Combine:
$$\frac{-1 + 5i}{2} = \frac{-1}{2} + \frac{5}{2}i = -\frac{1}{2} + \frac{5}{2}i$$

**Answer:** $-\frac{1}{2} + \frac{5}{2}i$

## Example 2: $\frac{3 + 2i}{4 - 3i}$

**Step 1:** Conjugate of $(4 - 3i)$ is $(4 + 3i)$

**Step 2:** Multiply:
$$\frac{3 + 2i}{4 - 3i} \times \frac{4 + 3i}{4 + 3i}$$

**Step 3:** Simplify numerator:
$$(3 + 2i)(4 + 3i) = 12 + 9i + 8i + 6i^2 = 12 + 17i - 6 = 6 + 17i$$

**Step 4:** Simplify denominator:
$$(4 - 3i)(4 + 3i) = 4^2 + 3^2 = 16 + 9 = 25$$

**Step 5:** Combine:
$$\frac{6 + 17i}{25} = \frac{6}{25} + \frac{17}{25}i$$

**Answer:** $\frac{6}{25} + \frac{17}{25}i$

## Example 3: $\frac{5 + 4i}{2 + i}$

**Step 1:** Conjugate of $(2 + i)$ is $(2 - i)$

**Step 2:** Multiply:
$$\frac{5 + 4i}{2 + i} \times \frac{2 - i}{2 - i}$$

**Step 3:** Simplify numerator:
$$(5 + 4i)(2 - i) = 10 - 5i + 8i - 4i^2 = 10 + 3i + 4 = 14 + 3i$$

**Step 4:** Simplify denominator:
$$(2 + i)(2 - i) = 2^2 + 1^2 = 4 + 1 = 5$$

**Step 5:** Combine:
$$\frac{14 + 3i}{5} = \frac{14}{5} + \frac{3}{5}i$$

**Answer:** $\frac{14}{5} + \frac{3}{5}i$ or $2.8 + 0.6i$

## Special Cases

### Dividing by a Real Number

Simply divide both parts:

**Example 1:** $\frac{6 + 8i}{2} = \frac{6}{2} + \frac{8}{2}i = 3 + 4i$

**Example 2:** $\frac{10 - 15i}{5} = \frac{10}{5} - \frac{15}{5}i = 2 - 3i$

### Dividing by a Pure Imaginary Number

**Example:** $\frac{3 + 4i}{2i}$

Conjugate of $2i$ (which is $0 + 2i$) is $-2i$ (which is $0 - 2i$)

$$\frac{3 + 4i}{2i} \times \frac{-2i}{-2i} = \frac{(3 + 4i)(-2i)}{-4i^2} = \frac{-6i - 8i^2}{4} = \frac{-6i + 8}{4} = \frac{8 - 6i}{4} = 2 - \frac{3}{2}i$$

**Shortcut:** Multiply numerator and denominator by $i$, then use $i^2 = -1$

$$\frac{3 + 4i}{2i} \times \frac{i}{i} = \frac{3i + 4i^2}{2i^2} = \frac{3i - 4}{-2} = \frac{-4 + 3i}{-2} = 2 - \frac{3}{2}i$$

### Dividing by $i$

When dividing by $i$, multiply by $\frac{-i}{-i}$:

$$\frac{a + bi}{i} = \frac{a + bi}{i} \times \frac{-i}{-i} = \frac{-ai - bi^2}{-i^2} = \frac{-ai + b}{1} = b - ai$$

**Examples:**
- $\frac{3 + 4i}{i} = 4 - 3i$
- $\frac{5 - 2i}{i} = -2 - 5i$

## Complex Examples

### Example 1: $\frac{1 + i}{1 - i} + \frac{1 - i}{1 + i}$

**Part 1:** $\frac{1 + i}{1 - i} \times \frac{1 + i}{1 + i} = \frac{(1 + i)^2}{2} = \frac{1 + 2i + i^2}{2} = \frac{1 + 2i - 1}{2} = \frac{2i}{2} = i$

**Part 2:** $\frac{1 - i}{1 + i} \times \frac{1 - i}{1 - i} = \frac{(1 - i)^2}{2} = \frac{1 - 2i + i^2}{2} = \frac{1 - 2i - 1}{2} = \frac{-2i}{2} = -i$

**Add:** $i + (-i) = 0$

**Answer:** $0$

### Example 2: $\frac{2}{3 + 4i}$

Conjugate of $(3 + 4i)$ is $(3 - 4i)$

$$\frac{2}{3 + 4i} \times \frac{3 - 4i}{3 - 4i} = \frac{2(3 - 4i)}{9 + 16} = \frac{6 - 8i}{25} = \frac{6}{25} - \frac{8}{25}i$$

**Answer:** $\frac{6}{25} - \frac{8}{25}i$

### Example 3: $\frac{(2 + i)(3 - i)}{1 + 2i}$

**Step 1:** Multiply the numerator first:
$$(2 + i)(3 - i) = 6 - 2i + 3i - i^2 = 6 + i + 1 = 7 + i$$

**Step 2:** Divide:
$$\frac{7 + i}{1 + 2i} \times \frac{1 - 2i}{1 - 2i} = \frac{7 - 14i + i - 2i^2}{1 + 4} = \frac{7 - 13i + 2}{5} = \frac{9 - 13i}{5}$$

**Answer:** $\frac{9}{5} - \frac{13}{5}i$ or $1.8 - 2.6i$

## Reciprocal of a Complex Number

The reciprocal of $z = a + bi$ is $\frac{1}{z}$:

$$\frac{1}{a + bi} = \frac{1}{a + bi} \times \frac{a - bi}{a - bi} = \frac{a - bi}{a^2 + b^2}$$

**Example:** Reciprocal of $3 + 4i$

$$\frac{1}{3 + 4i} = \frac{3 - 4i}{9 + 16} = \frac{3 - 4i}{25} = \frac{3}{25} - \frac{4}{25}i$$

**Verification:** $(3 + 4i) \times \frac{3 - 4i}{25} = \frac{9 + 16}{25} = \frac{25}{25} = 1$ ✓

## Properties of Complex Division

### 1. Absolute Value of a Quotient

$$\left|\frac{z_1}{z_2}\right| = \frac{|z_1|}{|z_2|}$$

**Example:** $\left|\frac{3 + 4i}{1 + i}\right|$

$$\frac{|3 + 4i|}{|1 + i|} = \frac{\sqrt{9 + 16}}{\sqrt{1 + 1}} = \frac{5}{\sqrt{2}} = \frac{5\sqrt{2}}{2}$$

### 2. Conjugate of a Quotient

$$\overline{\left(\frac{z_1}{z_2}\right)} = \frac{\overline{z_1}}{\overline{z_2}}$$

**Example:** $\overline{\left(\frac{2 + 3i}{1 - i}\right)} = \frac{\overline{2 + 3i}}{\overline{1 - i}} = \frac{2 - 3i}{1 + i}$

## Why Does This Work?

The conjugate trick works because:

1. Multiplying by $\frac{\overline{z}}{\overline{z}} = 1$ doesn't change the value
2. $(a + bi)(a - bi) = a^2 + b^2$ eliminates the imaginary part from the denominator
3. We end up with a real denominator, making it easy to separate into real and imaginary parts

## Common Mistakes to Avoid

❌ **Mistake 1:** Dividing parts separately
- Wrong: $\frac{4 + 6i}{2 + 3i} = \frac{4}{2} + \frac{6i}{3i} = 2 + 2$ (NEVER do this!)
- This only works when dividing by a real number!

❌ **Mistake 2:** Using the wrong conjugate
- Wrong conjugate: If denominator is $(3 - 2i)$, don't use $(3 + 2i)$ ❌
- Right conjugate: Use $(3 + 2i)$ ✓ (flip the sign of imaginary part)

❌ **Mistake 3:** Forgetting $i^2 = -1$ in the numerator
- Wrong: $\frac{(1 + i)(1 - i)}{1 + 1}$ and getting $\frac{1 - i^2}{2} = \frac{1 - 1}{2} = 0$
- Right: $i^2 = -1$, so $\frac{1 - (-1)}{2} = 1$

❌ **Mistake 4:** Sign errors when expanding
- Be extra careful with negative signs!
- $(3 - 2i)(3 + 2i) = 9 - 4i^2 = 9 + 4 = 13$ ✓

## Step-by-Step Division Strategy

**For $\frac{a + bi}{c + di}$:**

1. ✏️ **Write** the problem
2. 🔄 **Find** conjugate of denominator: $(c - di)$
3. ✖️ **Multiply** top and bottom by conjugate
4. 🧮 **Expand** numerator using FOIL
5. 🧮 **Calculate** denominator: $c^2 + d^2$
6. 🔢 **Replace** all $i^2$ with $-1$
7. ➕ **Combine** like terms
8. ✂️ **Separate** into real and imaginary parts
9. ✅ **Simplify** fractions if possible

---

## Complete Example: $\frac{-10 + 9i}{3i - 4}$

Let's solve this step by step!

### **Step 1: Understand What a Conjugate Is**

**What is a Conjugate?**
The **conjugate** of a complex number is the same number but with the **opposite sign** in the imaginary part.

- If you have $(a + bi)$, the conjugate is $(a - bi)$
- If you have $(a - bi)$, the conjugate is $(a + bi)$

**Examples:**
- Conjugate of $(3 + 4i)$ is $(3 - 4i)$
- Conjugate of $(5 - 2i)$ is $(5 + 2i)$
- Conjugate of $(-4 + 3i)$ is $(-4 - 3i)$

**Why do we use conjugates?**
When you multiply a complex number by its conjugate, the imaginary parts cancel out, leaving only a real number! This is the magic trick that lets us divide complex numbers.

**For our problem:**
- Denominator: $(3i - 4)$ which is the same as $(-4 + 3i)$
- **Conjugate:** $(-4 - 3i)$

---

### **Step 2: Multiply Top and Bottom by the Conjugate**

$$\frac{-10 + 9i}{-4 + 3i} \times \frac{-4 - 3i}{-4 - 3i}$$

**Why?** This equals multiplying by 1, so it doesn't change the value—just the form!

---

### **Step 3: Multiply the Numerator**

$$(-10 + 9i)(-4 - 3i)$$

Use **FOIL** (First, Outer, Inner, Last):
- **F**: $(-10)(-4) = 40$
- **O**: $(-10)(-3i) = 30i$
- **I**: $(9i)(-4) = -36i$
- **L**: $(9i)(-3i) = -27i^2 = -27(-1) = 27$ (remember $i^2 = -1$!)

Combine: $40 + 30i - 36i + 27 = 67 - 6i$

---

### **Step 4: Multiply the Denominator**

$$(-4 + 3i)(-4 - 3i)$$

This is a **difference of squares**: $(a + b)(a - b) = a^2 - b^2$

$$(-4)^2 - (3i)^2 = 16 - 9i^2 = 16 - 9(-1) = 16 + 9 = 25$$

**Why conjugates work:** The $i$ disappears! We get a real number.

---

### **Step 5: Simplify**

$$\frac{67 - 6i}{25} = \frac{67}{25} - \frac{6}{25}i$$

---

### **Final Answer:**
$$\frac{67}{25} - \frac{6}{25}i$$

Or in decimal form: **2.68 - 0.24i**

---

### **Key Points from This Example:**

1. **Conjugate**: Change the sign between real and imaginary parts
   - Always keep the real part the same
   - Flip the sign of the imaginary part

2. **$i^2 = -1$**: Always replace $i^2$ with $-1$

3. **Why multiply by conjugate?**: It eliminates $i$ from the denominator

4. **Standard form**: Write answer as $a + bi$ (or $a - bi$)

5. **Check your work**: Multiply your answer by the original denominator to verify!

---

## Example with Addition: $-4 + \frac{31}{-2i + 5}$

This problem combines **addition** with **division**. Let's solve it step by step!

### **Step 1: Focus on the Division First**

We need to simplify $\frac{31}{-2i + 5}$ before we can add $-4$.

Rewrite denominator in standard form: $\frac{31}{5 - 2i}$

### **Step 2: Find the Conjugate**

Denominator: $(5 - 2i)$  
**Conjugate:** $(5 + 2i)$

### **Step 3: Multiply by the Conjugate**

$$\frac{31}{5 - 2i} \times \frac{5 + 2i}{5 + 2i}$$

### **Step 4: Multiply the Numerator**

$$31(5 + 2i) = 155 + 62i$$

### **Step 5: Multiply the Denominator**

$$(5 - 2i)(5 + 2i) = 5^2 - (2i)^2 = 25 - 4i^2 = 25 - 4(-1) = 25 + 4 = 29$$

### **Step 6: Simplify the Fraction**

$$\frac{155 + 62i}{29} = \frac{155}{29} + \frac{62}{29}i$$

### **Step 7: Add $-4$ to the Result**

Now we add $-4$ to our fraction:

$$-4 + \frac{155}{29} + \frac{62}{29}i$$

Convert $-4$ to a fraction with denominator 29:

$$-4 = \frac{-116}{29}$$

Combine the real parts:

$$\frac{-116}{29} + \frac{155}{29} = \frac{39}{29}$$

### **Step 8: Write the Final Answer**

$$\frac{39}{29} + \frac{62}{29}i$$

Or in decimal form: **1.34 + 2.14i**

---

### **Key Steps for Mixed Operations:**

1. **Order of operations**: Simplify division first, then addition
2. **Keep imaginary and real parts separate**: Only add real to real, imaginary to imaginary
3. **Common denominators**: When adding, convert all numbers to the same denominator
4. **Standard form**: Always finish in $a + bi$ form

---

## Key Takeaways

1. **Multiply by the conjugate** of the denominator
2. The conjugate of $(a + bi)$ is $(a - bi)$
3. $(a + bi)(a - bi) = a^2 + b^2$ (always real!)
4. Always express final answer in form $a + bi$
5. Check: multiply your answer by the original denominator
6. Only divide parts separately when denominator is **real**

## Congratulations! 🎉

You've completed the full course from zero to hero! You now understand:
- ✓ Different types of numbers
- ✓ Multiplying and dividing regular numbers
- ✓ What complex numbers are
- ✓ Multiplying complex numbers
- ✓ Dividing complex numbers

You're ready to tackle any problem involving multiplication and division of regular and complex numbers!

---

**Final Practice:** Open `Exercise_6.md` to master complex division and test everything you've learned!
