# Lesson 4: Introduction to Complex Numbers

Congratulations! You've mastered regular numbers. Now we're entering exciting new territory: **Complex Numbers**!

## The Problem That Started It All

Try to solve this equation:
$$x^2 = -1$$

What number, when multiplied by itself, gives -1?
- It's not 1, because $1 \times 1 = 1$
- It's not -1, because $(-1) \times (-1) = 1$
- No real number works!

Mathematicians invented a **new type of number** to solve this problem.

## The Imaginary Unit: $i$

We define a special number called $i$ (imaginary unit):
$$i = \sqrt{-1}$$
$$i^2 = -1$$

**Key Property:** When you square $i$, you get -1.

### Powers of $i$

Let's see what happens when we raise $i$ to different powers:

- $i^1 = i$
- $i^2 = -1$
- $i^3 = i^2 \times i = -1 \times i = -i$
- $i^4 = i^2 \times i^2 = (-1) \times (-1) = 1$
- $i^5 = i^4 \times i = 1 \times i = i$
- $i^6 = i^4 \times i^2 = 1 \times (-1) = -1$

**Pattern:** The powers of $i$ repeat in a cycle of 4!

| Power | Value |
|-------|-------|
| $i^1$ | $i$ |
| $i^2$ | $-1$ |
| $i^3$ | $-i$ |
| $i^4$ | $1$ |
| $i^5$ | $i$ (cycle repeats) |

**Trick:** To find $i^n$, divide $n$ by 4 and use the remainder:
- $i^{17}$: $17 \div 4 = 4$ remainder $1$, so $i^{17} = i^1 = i$
- $i^{26}$: $26 \div 4 = 6$ remainder $2$, so $i^{26} = i^2 = -1$

## What Are Complex Numbers?

**Complex numbers** combine real numbers and imaginary numbers:

$$z = a + bi$$

Where:
- $a$ is the **real part**
- $b$ is the **imaginary part** (the coefficient of $i$)
- Both $a$ and $b$ are real numbers

### Examples

1. $3 + 4i$ → real part: 3, imaginary part: 4
2. $-2 + 5i$ → real part: -2, imaginary part: 5
3. $7 - 3i$ → real part: 7, imaginary part: -3
4. $5i$ → real part: 0, imaginary part: 5 (purely imaginary)
5. $8$ → real part: 8, imaginary part: 0 (purely real)

**Important:** All real numbers are complex numbers (with imaginary part = 0)!

## The Complex Plane

Just like we use a number line for real numbers, we use a **complex plane** for complex numbers:

```
      Imaginary Axis (bi)
            ↑
         4i |    • (3 + 4i)
         3i |
         2i |
         1i |
    --------+-------→ Real Axis (a)
       -2 -1 0 1 2 3
        -1i |
        -2i |      • (2 - 2i)
        -3i |
            ↓
```

- **Horizontal axis:** Real part ($a$)
- **Vertical axis:** Imaginary part ($bi$)
- Each complex number is a point on this plane

## Basic Operations with Complex Numbers

### Adding Complex Numbers

**Rule:** Add the real parts and add the imaginary parts separately.

$$(a + bi) + (c + di) = (a + c) + (b + d)i$$

**Examples:**

1. $(3 + 4i) + (2 + 5i) = (3 + 2) + (4 + 5)i = 5 + 9i$

2. $(7 - 3i) + (-2 + 6i) = (7 - 2) + (-3 + 6)i = 5 + 3i$

3. $(5 + 2i) + (3 - 2i) = (5 + 3) + (2 - 2)i = 8 + 0i = 8$

### Subtracting Complex Numbers

**Rule:** Subtract the real parts and subtract the imaginary parts separately.

$$(a + bi) - (c + di) = (a - c) + (b - d)i$$

**Examples:**

1. $(5 + 7i) - (2 + 3i) = (5 - 2) + (7 - 3)i = 3 + 4i$

2. $(4 + 2i) - (6 - 3i) = (4 - 6) + (2 - (-3))i = -2 + 5i$

3. $(8 + 5i) - (8 + 2i) = (8 - 8) + (5 - 2)i = 0 + 3i = 3i$

## Important Concepts

### Equality of Complex Numbers

Two complex numbers are equal if and only if:
- Their real parts are equal, AND
- Their imaginary parts are equal

$$a + bi = c + di \text{ if and only if } a = c \text{ and } b = d$$

**Example:** If $x + 3i = 5 + yi$, then $x = 5$ and $y = 3$

### Conjugate of a Complex Number

The **complex conjugate** of $a + bi$ is $a - bi$ (flip the sign of the imaginary part).

**Notation:** $\overline{z}$ or $z^*$

**Examples:**
- Conjugate of $3 + 4i$ is $3 - 4i$
- Conjugate of $5 - 2i$ is $5 + 2i$
- Conjugate of $7i$ is $-7i$
- Conjugate of $6$ is $6$ (no imaginary part to flip)

**Important Property:** $z \times \overline{z}$ always gives a real number!

**Example:** $(3 + 4i)(3 - 4i) = 9 - 12i + 12i - 16i^2 = 9 - 16(-1) = 9 + 16 = 25$

### Absolute Value (Modulus)

The **absolute value** (or modulus) of a complex number is its distance from the origin:

$$|a + bi| = \sqrt{a^2 + b^2}$$

This comes from the Pythagorean theorem!

**Examples:**

1. $|3 + 4i| = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5$

2. $|5 - 12i| = \sqrt{5^2 + (-12)^2} = \sqrt{25 + 144} = \sqrt{169} = 13$

3. $|6i| = \sqrt{0^2 + 6^2} = \sqrt{36} = 6$

4. $|8| = \sqrt{8^2 + 0^2} = \sqrt{64} = 8$

## Why Are Complex Numbers Useful?

Complex numbers aren't just mathematical curiosities - they're used in:

1. **Electrical Engineering:** Analyzing AC circuits (voltage and current)
2. **Quantum Physics:** Describing quantum states
3. **Signal Processing:** Audio, image, and video processing
4. **Computer Graphics:** 3D rotations and transformations
5. **Fluid Dynamics:** Modeling fluid flow
6. **Fractals:** Creating beautiful patterns like the Mandelbrot set

## Simplifying Square Roots of Negative Numbers

Using $i = \sqrt{-1}$, we can simplify square roots of negative numbers:

$$\sqrt{-n} = \sqrt{-1 \times n} = \sqrt{-1} \times \sqrt{n} = i\sqrt{n}$$

**Examples:**
- $\sqrt{-4} = i\sqrt{4} = 2i$
- $\sqrt{-9} = i\sqrt{9} = 3i$
- $\sqrt{-25} = i\sqrt{25} = 5i$
- $\sqrt{-7} = i\sqrt{7}$

## Summary: Types of Numbers

Let's see how complex numbers fit into the bigger picture:

```
Complex Numbers (ℂ): a + bi
    ├── Real Numbers (ℝ): a + 0i
    │       ├── Rational Numbers
    │       │       ├── Integers
    │       │       │    ├── Whole Numbers
    │       │       │    │    └── Natural Numbers
    │       │       │    └── Negative Integers
    │       │       └── Fractions
    │       └── Irrational Numbers (π, √2, e, ...)
    └── Imaginary Numbers: 0 + bi (purely imaginary)
```

**Complex numbers are the most complete number system we have!**

## Key Takeaways

1. $i = \sqrt{-1}$ and $i^2 = -1$
2. Complex numbers have the form $a + bi$
3. Powers of $i$ repeat in cycles of 4: $i, -1, -i, 1$
4. Add/subtract complex numbers by combining like parts
5. The conjugate flips the sign of the imaginary part
6. $|a + bi| = \sqrt{a^2 + b^2}$ (distance from origin)

## Next Steps

Now that you understand what complex numbers are, let's learn how to **multiply** them!

---

**Ready to practice?** Open `Exercise_4.md` to master complex number basics!
