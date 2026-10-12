# IGNOU ASSIGNMENT

**Course Code:** BCS-012
**Course Title:** Basic Mathematics
**Assignment Number:** BCA_NEW/BCAOL(I)012/Assign/2026-27
**Maximum Marks:** 100

**Student Name:** ________________________
**Enrollment No.:** ________________________

---

**Q1: If A = [3 −1; 2 1], show that A² − 4A + 5I₂ = 0. Also find A⁴.**

**Answer:**

Given Matrix $A = \begin{pmatrix} 3 & -1 \\ 2 & 1 \end{pmatrix}$.

First, calculate $A^2$:
$$A^2 = \begin{pmatrix} 3 & -1 \\ 2 & 1 \end{pmatrix} \begin{pmatrix} 3 & -1 \\ 2 & 1 \end{pmatrix} = \begin{pmatrix} (3)(3) + (-1)(2) & (3)(-1) + (-1)(1) \\ (2)(3) + (1)(2) & (2)(-1) + (1)(1) \end{pmatrix}$$
$$A^2 = \begin{pmatrix} 9 - 2 & -3 - 1 \\ 6 + 2 & -2 + 1 \end{pmatrix} = \begin{pmatrix} 7 & -4 \\ 8 & -1 \end{pmatrix}$$

Next, calculate $4A$:
$$4A = 4 \begin{pmatrix} 3 & -1 \\ 2 & 1 \end{pmatrix} = \begin{pmatrix} 12 & -4 \\ 8 & 4 \end{pmatrix}$$

Calculate $5I_2$:
$$5I_2 = 5 \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix} = \begin{pmatrix} 5 & 0 \\ 0 & 5 \end{pmatrix}$$

Now, substitute these into the equation $A^2 - 4A + 5I_2$:
$$= \begin{pmatrix} 7 & -4 \\ 8 & -1 \end{pmatrix} - \begin{pmatrix} 12 & -4 \\ 8 & 4 \end{pmatrix} + \begin{pmatrix} 5 & 0 \\ 0 & 5 \end{pmatrix}$$
$$= \begin{pmatrix} 7 - 12 + 5 & -4 - (-4) + 0 \\ 8 - 8 + 0 & -1 - 4 + 5 \end{pmatrix}$$
$$= \begin{pmatrix} 0 & 0 \\ 0 & 0 \end{pmatrix} = 0$$
**Hence Proved.**

To find $A^4$, we square $A^2$:
$$A^4 = A^2 \cdot A^2 = \begin{pmatrix} 7 & -4 \\ 8 & -1 \end{pmatrix} \begin{pmatrix} 7 & -4 \\ 8 & -1 \end{pmatrix}$$
$$= \begin{pmatrix} (7)(7) + (-4)(8) & (7)(-4) + (-4)(-1) \\ (8)(7) + (-1)(8) & (8)(-4) + (-1)(-1) \end{pmatrix}$$
$$= \begin{pmatrix} 49 - 32 & -28 + 4 \\ 56 - 8 & -32 + 1 \end{pmatrix} = \begin{pmatrix} 17 & -24 \\ 48 & -31 \end{pmatrix}$$

---
<br>

**Q2: Solve the following system of equations using the matrix inverse method:**
**3x + 4y + 7z = 14**
**2x − y + 3z = 4**
**2x + 2y − 3z = 0**

**Answer:**

The system can be written in matrix form as $AX = B$:
$A = \begin{pmatrix} 3 & 4 & 7 \\ 2 & -1 & 3 \\ 2 & 2 & -3 \end{pmatrix}, X = \begin{pmatrix} x \\ y \\ z \end{pmatrix}, B = \begin{pmatrix} 14 \\ 4 \\ 0 \end{pmatrix}$

First, find the Determinant $|A|$:
$|A| = 3[(-1)(-3) - (2)(3)] - 4[(2)(-3) - (2)(3)] + 7[(2)(2) - (-1)(2)]$
$|A| = 3(3 - 6) - 4(-6 - 6) + 7(4 + 2)$
$|A| = 3(-3) - 4(-12) + 7(6)$
$|A| = -9 + 48 + 42 = 81$

Since $|A| \neq 0$, the inverse exists.
Now, find the Cofactors of A:
$C_{11} = (3 - 6) = -3$
$C_{12} = -(-6 - 6) = 12$
$C_{13} = (4 + 2) = 6$
$C_{21} = -(-12 - 14) = 26$
$C_{22} = (-9 - 14) = -23$
$C_{23} = -(6 - 8) = 2$
$C_{31} = (12 + 7) = 19$
$C_{32} = -(9 - 14) = 5$
$C_{33} = (-3 - 8) = -11$

Adjoint Matrix $Adj(A)$ is the transpose of the cofactor matrix:
$Adj(A) = \begin{pmatrix} -3 & 26 & 19 \\ 12 & -23 & 5 \\ 6 & 2 & -11 \end{pmatrix}$

Find $A^{-1} = \frac{1}{|A|} Adj(A)$:
$X = A^{-1}B = \frac{1}{81} \begin{pmatrix} -3 & 26 & 19 \\ 12 & -23 & 5 \\ 6 & 2 & -11 \end{pmatrix} \begin{pmatrix} 14 \\ 4 \\ 0 \end{pmatrix}$

Calculate the product matrix:
$x = \frac{(-3 \times 14) + (26 \times 4) + (19 \times 0)}{81} = \frac{-42 + 104}{81} = \frac{62}{81}$
$y = \frac{(12 \times 14) + (-23 \times 4) + (5 \times 0)}{81} = \frac{168 - 92}{81} = \frac{76}{81}$
$z = \frac{(6 \times 14) + (2 \times 4) + (-11 \times 0)}{81} = \frac{84 + 8}{81} = \frac{92}{81}$

**Final Answer:** $x = 62/81, \quad y = 76/81, \quad z = 92/81$.

---
<br>

**Q3: Use the principle of mathematical induction to prove that:**
**1/(1×2) + 1/(2×3) + … + 1/[n(n+1)] = n/(n+1)**

**Answer:**

**Step 1: Verify the base case for $n=1$.**
LHS = $1/(1 \times 2) = 1/2$.
RHS = $1/(1+1) = 1/2$.
Since LHS = RHS, the statement holds true for $n=1$.

**Step 2: Inductive Hypothesis.**
Assume the statement is true for some positive integer $k$:
$1/(1 \times 2) + 1/(2 \times 3) + \dots + 1/[k(k+1)] = k/(k+1)$.

**Step 3: Prove for $n=k+1$.**
We must show that the sum of the first $(k+1)$ terms equals $(k+1)/(k+2)$.
Add the $(k+1)^{th}$ term to both sides of the hypothesis equation:
LHS for $(k+1) = \left[ \frac{1}{1 \times 2} + \dots + \frac{1}{k(k+1)} \right] + \frac{1}{(k+1)(k+2)}$
Substitute the hypothesis into the bracketed part:
$= \frac{k}{k+1} + \frac{1}{(k+1)(k+2)}$
Take common denominator $(k+1)(k+2)$:
$= \frac{k(k+2) + 1}{(k+1)(k+2)}$
$= \frac{k^2 + 2k + 1}{(k+1)(k+2)}$
Factorize the numerator:
$= \frac{(k+1)^2}{(k+1)(k+2)}$
Cancel one $(k+1)$ from top and bottom:
$= \frac{k+1}{k+2}$
This exactly matches the RHS formula for $n=k+1$. 
Thus, by the principle of mathematical induction, the statement is true for all natural numbers $n$.

---
<br>

**Q4: If the pᵗʰ term of an A.P. is q and the qᵗʰ term of the same A.P. is p, find its rᵗʰ term.**

**Answer:**

Let the first term of the Arithmetic Progression (A.P.) be $a$ and the common difference be $d$.
Formula for the $n^{th}$ term is $T_n = a + (n-1)d$.

Given:
$T_p = a + (p-1)d = q$  --- (Equation 1)
$T_q = a + (q-1)d = p$  --- (Equation 2)

Subtract Equation 2 from Equation 1:
$[a + (p-1)d] - [a + (q-1)d] = q - p$
$(p - 1 - q + 1)d = q - p$
$(p - q)d = -(p - q)$
$d = -1$ (Assuming $p \neq q$)

Substitute $d = -1$ into Equation 1 to find $a$:
$a + (p-1)(-1) = q$
$a - p + 1 = q$
$a = p + q - 1$

Now, find the $r^{th}$ term ($T_r$):
$T_r = a + (r-1)d$
Substitute $a$ and $d$:
$T_r = (p + q - 1) + (r - 1)(-1)$
$T_r = p + q - 1 - r + 1$
$T_r = p + q - r$

**Final Answer:** The $r^{th}$ term is **$p + q - r$**.

---
<br>

**Q5: How many terms of the G.P. √3, 3, 3√3, … add up to 39 + 13√3?**

**Answer:**

Given Geometric Progression (G.P.): $\sqrt{3}, 3, 3\sqrt{3}, \dots$
First term, $a = \sqrt{3}$.
Common ratio, $r = 3 / \sqrt{3} = \sqrt{3}$. Since $r > 1$, we use the sum formula $S_n = \frac{a(r^n - 1)}{r - 1}$.

Given Sum $S_n = 39 + 13\sqrt{3}$.
Factor out $13\sqrt{3}$ from the sum: $39 + 13\sqrt{3} = 13\sqrt{3}(\sqrt{3} + 1)$.

Set up the equation:
$\frac{\sqrt{3}( (\sqrt{3})^n - 1 )}{\sqrt{3} - 1} = 13\sqrt{3}(\sqrt{3} + 1)$

Divide both sides by $\sqrt{3}$:
$\frac{(\sqrt{3})^n - 1}{\sqrt{3} - 1} = 13(\sqrt{3} + 1)$

Multiply both sides by $(\sqrt{3} - 1)$:
$(\sqrt{3})^n - 1 = 13(\sqrt{3} + 1)(\sqrt{3} - 1)$

Apply the difference of squares $(a+b)(a-b) = a^2 - b^2$:
$(\sqrt{3})^n - 1 = 13(3 - 1)$
$(\sqrt{3})^n - 1 = 13(2) = 26$
$(\sqrt{3})^n = 26 + 1 = 27$

Convert 27 to base 3:
$(3^{1/2})^n = 3^3$
$3^{n/2} = 3^3$
Compare the powers:
$n/2 = 3 \implies n = 6$.

**Final Answer:** **6 terms** of the G.P. add up to the given sum.

---
<br>

**Q6: Find the sum of all integers between 100 and 1000 that are divisible by 7.**

**Answer:**

To find integers between 100 and 1000 divisible by 7, we form an Arithmetic Progression (A.P.).
*   The first integer greater than 100 divisible by 7 is 105 ($15 \times 7$).
*   The last integer less than 1000 divisible by 7 is 994 ($142 \times 7$).

The A.P. is: $105, 112, 119, \dots, 994$.
Here, first term $a = 105$, common difference $d = 7$, last term $l = 994$.

Find the number of terms ($n$) using the formula $l = a + (n-1)d$:
$994 = 105 + (n-1)7$
$889 = (n-1)7$
$n - 1 = 127$
$n = 128$

Now, find the sum using the formula $S_n = \frac{n}{2} (a + l)$:
$S_n = \frac{128}{2} (105 + 994)$
$S_n = 64 \times 1099$
$S_n = 70336$

**Final Answer:** The sum is **70,336**.

---
<br>

**Q7: If 1, ω, ω² are the cube roots of unity, show that: (2 − ω)(2 − ω²)(2 − ω¹⁹)(2 − ω²³) = 49**

**Answer:**

Properties of cube roots of unity: 
1) $\omega^3 = 1$
2) $1 + \omega + \omega^2 = 0 \implies \omega^2 + \omega = -1$

Simplify the higher powers of $\omega$ in the given expression:
$\omega^{19} = (\omega^3)^6 \cdot \omega^1 = (1)^6 \cdot \omega = \omega$.
$\omega^{23} = (\omega^3)^7 \cdot \omega^2 = (1)^7 \cdot \omega^2 = \omega^2$.

Substitute these into the Left Hand Side (LHS):
LHS $= (2-\omega)(2-\omega^2)(2-\omega)(2-\omega^2)$
LHS $= [(2-\omega)(2-\omega^2)]^2$

Expand the expression inside the brackets:
$(2-\omega)(2-\omega^2) = (2)(2) - 2\omega^2 - 2\omega + (\omega)(\omega^2)$
$= 4 - 2(\omega^2 + \omega) + \omega^3$

Substitute $\omega^2 + \omega = -1$ and $\omega^3 = 1$:
$= 4 - 2(-1) + 1$
$= 4 + 2 + 1 = 7$

Now square the result as per the LHS:
LHS $= [7]^2 = 49$.
Since LHS = RHS (49 = 49), the statement is **Proved**.

---
<br>

**Q8: Use De Moivre’s theorem to find the value of (√3 + i)³**

**Answer:**

Let complex number $z = \sqrt{3} + i$.
We must convert it into polar form $z = r(\cos\theta + i\sin\theta)$.
Modulus $r = \sqrt{(\sqrt{3})^2 + 1^2} = \sqrt{3 + 1} = \sqrt{4} = 2$.
Argument $\theta = \tan^{-1}(y/x) = \tan^{-1}(1/\sqrt{3}) = \pi/6$.

Polar form: $z = 2(\cos(\pi/6) + i\sin(\pi/6))$.

According to De Moivre's Theorem, $z^n = r^n(\cos(n\theta) + i\sin(n\theta))$.
For $n = 3$:
$z^3 = 2^3 \left( \cos\left(3 \times \frac{\pi}{6}\right) + i\sin\left(3 \times \frac{\pi}{6}\right) \right)$
$z^3 = 8(\cos(\pi/2) + i\sin(\pi/2))$

Since $\cos(\pi/2) = 0$ and $\sin(\pi/2) = 1$:
$z^3 = 8(0 + i(1))$
$z^3 = 8i$

**Final Answer:** **8i**.

---
<br>

**Q9: If α and β are the roots of x² − 3ax + a² = 0, find the value of a when α² + β² = 7/4.**

**Answer:**

From the given quadratic equation $x^2 - 3ax + a^2 = 0$, we find:
Sum of roots: $\alpha + \beta = -(-3a)/1 = 3a$
Product of roots: $\alpha\beta = a^2/1 = a^2$

We are given $\alpha^2 + \beta^2 = 7/4$.
Using the algebraic identity: $\alpha^2 + \beta^2 = (\alpha + \beta)^2 - 2\alpha\beta$
Substitute the known values into the identity:
$7/4 = (3a)^2 - 2(a^2)$
$7/4 = 9a^2 - 2a^2$
$7/4 = 7a^2$

Divide both sides by 7:
$1/4 = a^2$
Take the square root of both sides:
$a = \pm\sqrt{1/4}$
$a = \pm 1/2$

**Final Answer:** **$a = 1/2$ or $a = -1/2$**.

---
<br>

**Q10: If α and β are the roots of 2x² − 3x − 5 = 0, form the quadratic equation whose roots are α² and β².**

**Answer:**

From the given equation $2x^2 - 3x - 5 = 0$, we find:
Sum of roots: $\alpha + \beta = -(-3)/2 = 3/2$
Product of roots: $\alpha\beta = -5/2$

To form a new quadratic equation with roots $\alpha^2$ and $\beta^2$, we need the Sum and Product of these new roots.
**1. Sum of new roots ($S$):**
$S = \alpha^2 + \beta^2 = (\alpha + \beta)^2 - 2\alpha\beta$
$S = (3/2)^2 - 2(-5/2)$
$S = 9/4 + 5 = 9/4 + 20/4 = 29/4$

**2. Product of new roots ($P$):**
$P = (\alpha^2)(\beta^2) = (\alpha\beta)^2$
$P = (-5/2)^2 = 25/4$

The formula for a quadratic equation is $x^2 - Sx + P = 0$.
$x^2 - (29/4)x + (25/4) = 0$
Multiply the entire equation by 4 to remove fractions:
$4x^2 - 29x + 25 = 0$

**Final Answer:** The required equation is **$4x^2 - 29x + 25 = 0$**.

---
<br>

**Q11: Solve the equation: x³ − 13x² + 15x + 189 = 0, given that one root exceeds another by 2.**

**Answer:**

Let the three roots of the cubic equation be $\alpha$, $\alpha+2$, and $\beta$.
From the coefficients of $x^3 - 13x^2 + 15x + 189 = 0$, we know:
**Sum of roots:**
$\alpha + (\alpha+2) + \beta = -(-13)/1 = 13$
$2\alpha + \beta + 2 = 13 \implies \beta = 11 - 2\alpha$  --- (Equation 1)

**Sum of products of roots in pairs:**
$\alpha(\alpha+2) + \alpha\beta + (\alpha+2)\beta = 15$
Substitute $\beta$ into the equation:
$\alpha^2 + 2\alpha + \beta(\alpha + \alpha + 2) = 15$
$\alpha^2 + 2\alpha + (11 - 2\alpha)(2\alpha + 2) = 15$
Expand the brackets:
$\alpha^2 + 2\alpha + 22\alpha + 22 - 4\alpha^2 - 4\alpha = 15$
$-3\alpha^2 + 20\alpha + 22 = 15$
Move 15 to the left side:
$-3\alpha^2 + 20\alpha + 7 = 0$
Multiply by -1:
$3\alpha^2 - 20\alpha - 7 = 0$

Factorize the quadratic equation:
$3\alpha^2 - 21\alpha + \alpha - 7 = 0$
$3\alpha(\alpha - 7) + 1(\alpha - 7) = 0$
$(3\alpha + 1)(\alpha - 7) = 0$
So, $\alpha = 7$ or $\alpha = -1/3$.
Assuming integer roots, let $\alpha = 7$.
The second root is $\alpha + 2 = 7 + 2 = 9$.
The third root is $\beta = 11 - 2(7) = 11 - 14 = -3$.

*(Verification via Product of roots: $7 \times 9 \times -3 = -189$. The formula $-d/a = -189/1 = -189$. It matches perfectly.)*

**Final Answer:** The roots are **7, 9, and -3**.

---
<br>

**Q12: Solve the inequality and graph its solution: 2/(x − 1) > 5**

**Answer:**

Subtract 5 from both sides:
$\frac{2}{x-1} - 5 > 0$
Find a common denominator:
$\frac{2 - 5(x - 1)}{x - 1} > 0$
$\frac{2 - 5x + 5}{x - 1} > 0$
$\frac{7 - 5x}{x - 1} > 0$

Multiply the numerator by -1, which flips the inequality sign:
$\frac{5x - 7}{x - 1} < 0$

The critical points (where numerator or denominator equals zero) are:
$5x - 7 = 0 \implies x = 7/5 = 1.4$
$x - 1 = 0 \implies x = 1$

We check the sign of the expression in the intervals $(-\infty, 1)$, $(1, 1.4)$, and $(1.4, \infty)$:
*   For $x = 0$ (in interval 1): $(0 - 7) / (0 - 1) = 7$ (Positive, False)
*   For $x = 1.2$ (in interval 2): $(6 - 7) / (1.2 - 1) = -1 / 0.2 = -5$ (Negative, **True**)
*   For $x = 2$ (in interval 3): $(10 - 7) / (2 - 1) = 3 / 1 = 3$ (Positive, False)

**Final Answer:** The solution is the interval where the expression is less than 0.
$1 < x < 7/5$ (or $x \in (1, 1.4)$).
*(Graphing Instructions: Draw a number line. Place an open circle (not shaded) at 1 and another open circle at 1.4. Draw a thick line connecting the two open circles to represent all values between them.)*

---
<br>

**Q13: If y = log[ (√(1+x) − √(1−x)) / (√(1+x) + √(1−x)) ], find dy/dx.**

**Answer:**

First, simplify the expression inside the logarithm by rationalizing the denominator. Multiply both numerator and denominator by $(\sqrt{1+x} - \sqrt{1-x})$:
Numerator: $(\sqrt{1+x} - \sqrt{1-x})^2 = (1+x) + (1-x) - 2\sqrt{(1+x)(1-x)} = 2 - 2\sqrt{1-x^2}$
Denominator: $(\sqrt{1+x} + \sqrt{1-x})(\sqrt{1+x} - \sqrt{1-x}) = (1+x) - (1-x) = 2x$
Simplified fraction $= \frac{2 - 2\sqrt{1-x^2}}{2x} = \frac{1 - \sqrt{1-x^2}}{x}$

Substitute this back into the original equation:
$y = \log \left( \frac{1 - \sqrt{1-x^2}}{x} \right)$
Using log properties: $y = \log(1 - \sqrt{1-x^2}) - \log(x)$

Now, differentiate with respect to $x$:
$\frac{dy}{dx} = \frac{1}{1 - \sqrt{1-x^2}} \cdot \frac{d}{dx}(1 - \sqrt{1-x^2}) - \frac{1}{x}$
The derivative of $-\sqrt{1-x^2}$ is $-\frac{1}{2\sqrt{1-x^2}} \cdot (-2x) = \frac{x}{\sqrt{1-x^2}}$
So, $\frac{dy}{dx} = \left( \frac{1}{1 - \sqrt{1-x^2}} \right) \cdot \left( \frac{x}{\sqrt{1-x^2}} \right) - \frac{1}{x}$
$\frac{dy}{dx} = \frac{x}{(1 - \sqrt{1-x^2})\sqrt{1-x^2}} - \frac{1}{x}$

Take a common denominator:
$\frac{dy}{dx} = \frac{x^2 - \sqrt{1-x^2}(1 - \sqrt{1-x^2})}{x\sqrt{1-x^2}(1 - \sqrt{1-x^2})}$
Simplify the numerator:
$= x^2 - (\sqrt{1-x^2} - (1-x^2)) = x^2 - \sqrt{1-x^2} + 1 - x^2 = 1 - \sqrt{1-x^2}$
So the entire fraction becomes:
$\frac{dy}{dx} = \frac{1 - \sqrt{1-x^2}}{x\sqrt{1-x^2}(1 - \sqrt{1-x^2})}$

Cancel the common term $(1 - \sqrt{1-x^2})$ from top and bottom:
$\frac{dy}{dx} = \frac{1}{x\sqrt{1-x^2}}$

**Final Answer:** **$dy/dx = \frac{1}{x\sqrt{1-x^2}}$**

---
<br>

**Q14: If y = aeᵐˣ + be⁻ᵐˣ, prove that: d²y/dx² = m²y**

**Answer:**

Given equation:
$y = ae^{mx} + be^{-mx}$

Find the first derivative ($dy/dx$) with respect to $x$ using the chain rule:
$\frac{dy}{dx} = a \cdot e^{mx} \cdot \frac{d}{dx}(mx) + b \cdot e^{-mx} \cdot \frac{d}{dx}(-mx)$
$\frac{dy}{dx} = a m e^{mx} - b m e^{-mx}$

Find the second derivative ($d^2y/dx^2$) by differentiating again:
$\frac{d^2y}{dx^2} = am \cdot e^{mx} \cdot (m) - bm \cdot e^{-mx} \cdot (-m)$
$\frac{d^2y}{dx^2} = am^2 e^{mx} + bm^2 e^{-mx}$

Factor out the common term $m^2$:
$\frac{d^2y}{dx^2} = m^2(ae^{mx} + be^{-mx})$

Notice that the term in the parentheses is exactly our original equation $y$. Substitute $y$ back in:
$\frac{d^2y}{dx^2} = m^2y$

**Hence Proved.**

---
<br>

**Q15: Determine the intervals in which f(x) = x⁴ − 8x³ + 22x² − 24x + 21 is increasing and decreasing.**

**Answer:**

To find intervals of increase/decrease, we need to find the first derivative $f'(x)$ and determine where it is positive (increasing) or negative (decreasing).
$f'(x) = 4x^3 - 24x^2 + 44x - 24$
Factor out 4:
$f'(x) = 4(x^3 - 6x^2 + 11x - 6)$

Find the critical points by setting $f'(x) = 0$:
By trial and error, test $x=1$:
$1^3 - 6(1)^2 + 11(1) - 6 = 1 - 6 + 11 - 6 = 0$. So $(x-1)$ is a factor.
Use synthetic division or long division to divide $(x^3 - 6x^2 + 11x - 6)$ by $(x-1)$:
Result is a quadratic: $x^2 - 5x + 6$.
Factorize the quadratic: $(x-2)(x-3)$.
So, $f'(x) = 4(x-1)(x-2)(x-3)$.

The critical points are $x = 1$, $x = 2$, and $x = 3$. These divide the number line into four intervals:
1. **$(-\infty, 1)$:** Choose $x=0$. $f'(0) = 4(-1)(-2)(-3) = -24$ (Negative). Function is Decreasing.
2. **$(1, 2)$:** Choose $x=1.5$. $f'(1.5) = 4(+)(-) (-) = +$ (Positive). Function is Increasing.
3. **$(2, 3)$:** Choose $x=2.5$. $f'(2.5) = 4(+)(+)(-) = -$ (Negative). Function is Decreasing.
4. **$(3, \infty)$:** Choose $x=4$. $f'(4) = 4(+)(+)(+) = +$ (Positive). Function is Increasing.

**Final Answer:**
Function is **Increasing** in the intervals: **$(1, 2) \cup (3, \infty)$**
Function is **Decreasing** in the intervals: **$(-\infty, 1) \cup (2, 3)$**

---
<br>

**Q16: Find the points of local maximum and local minimum of: f(x) = x³ − 6x² + 9x + 2014**

**Answer:**

Find the first derivative $f'(x)$ and set it to 0 to find critical points:
$f'(x) = 3x^2 - 12x + 9$
$0 = 3(x^2 - 4x + 3)$
$0 = 3(x-1)(x-3)$
Critical points are $x = 1$ and $x = 3$.

Use the Second Derivative Test to determine max/min. Find $f''(x)$:
$f''(x) = 6x - 12$

Evaluate the second derivative at each critical point:
1. At $x = 1$:
$f''(1) = 6(1) - 12 = -6$. 
Since $f''(1) < 0$, the function has a **Local Maximum** at $x = 1$.

2. At $x = 3$:
$f''(3) = 6(3) - 12 = 6$. 
Since $f''(3) > 0$, the function has a **Local Minimum** at $x = 3$.

**Final Answer:** The point of local maximum is **$x = 1$**. The point of local minimum is **$x = 3$**.

---
<br>

**Q17: Evaluate: ∫ x²√(5x − 3) dx**

**Answer:**

Let us use the substitution method.
Let $u = 5x - 3$.
Then, $du = 5 dx \implies dx = du/5$.
Also, express $x$ in terms of $u$: $5x = u + 3 \implies x = (u + 3)/5$.

Substitute these into the integral:
$= \int \left( \frac{u+3}{5} \right)^2 \cdot \sqrt{u} \cdot \frac{du}{5}$
$= \int \frac{u^2 + 6u + 9}{25} \cdot u^{1/2} \cdot \frac{du}{5}$
Pull out the constants:
$= \frac{1}{125} \int (u^2 + 6u + 9) u^{1/2} du$
Distribute $u^{1/2}$:
$= \frac{1}{125} \int (u^{5/2} + 6u^{3/2} + 9u^{1/2}) du$

Integrate term by term using power rule $\int u^n du = \frac{u^{n+1}}{n+1}$:
$= \frac{1}{125} \left( \frac{u^{7/2}}{7/2} + \frac{6u^{5/2}}{5/2} + \frac{9u^{3/2}}{3/2} \right) + C$
$= \frac{1}{125} \left( \frac{2}{7}u^{7/2} + \frac{12}{5}u^{5/2} + 6u^{3/2} \right) + C$

Substitute back $u = 5x - 3$:
**Final Answer:**
$= \frac{2}{875}(5x-3)^{7/2} + \frac{12}{625}(5x-3)^{5/2} + \frac{6}{125}(5x-3)^{3/2} + C$

---
<br>

**Q18: Using integration, find the length of the curve y = 3 – x from (−1, 4) to (3, 0).**

**Answer:**

The formula for the arc length of a curve $y = f(x)$ from $x=a$ to $x=b$ is:
$L = \int_{a}^{b} \sqrt{1 + \left(\frac{dy}{dx}\right)^2} dx$

Given equation: $y = 3 - x$
Derivative: $\frac{dy}{dx} = -1$
Square of derivative: $\left(\frac{dy}{dx}\right)^2 = (-1)^2 = 1$

Limits of integration from the given points are $x = -1$ to $x = 3$.
Substitute these into the formula:
$L = \int_{-1}^{3} \sqrt{1 + 1} dx$
$L = \int_{-1}^{3} \sqrt{2} dx$
$L = \sqrt{2} \int_{-1}^{3} 1 dx$
$L = \sqrt{2} [x]_{-1}^{3}$
Evaluate the limits:
$L = \sqrt{2} [3 - (-1)]$
$L = \sqrt{2} (4) = 4\sqrt{2}$

**Final Answer:** The length of the curve is **$4\sqrt{2}$ units**.

---
<br>

**Q19: Find the scalar component of projection of the vector a = 2î + 3ĵ + 5k̂ on the vector b = 2î − 2ĵ + k̂.**

**Answer:**

The formula for the scalar projection of vector $\vec{a}$ onto vector $\vec{b}$ is:
Projection $= \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|}$

**1. Find the dot product ($\vec{a} \cdot \vec{b}$):**
$\vec{a} \cdot \vec{b} = (2 \times 2) + (3 \times -2) + (5 \times 1)$
$\vec{a} \cdot \vec{b} = 4 - 6 + 5 = 3$

**2. Find the magnitude of vector b ($|\vec{b}|$):**
$|\vec{b}| = \sqrt{2^2 + (-2)^2 + 1^2}$
$|\vec{b}| = \sqrt{4 + 4 + 1}$
$|\vec{b}| = \sqrt{9} = 3$

**3. Calculate Projection:**
Projection $= 3 / 3 = 1$

**Final Answer:** The scalar component of the projection is **1**.

---
<br>

**Q20: A tailor needs at least 40 large buttons and 60 small buttons. A box contains 6 large and 2 small buttons, and a card contains 2 large and 4 small buttons. If the cost of a box is $3 and the cost of a card is $2, formulate and solve the problem as a linear programming problem to minimize expenditure.**

**Answer:**

Let $x$ be the number of boxes purchased.
Let $y$ be the number of cards purchased.

**Objective Function (to minimize):**
Cost $Z = 3x + 2y$

**Subject to Constraints:**
1. Large buttons requirement: $6x + 2y \ge 40$ (can be simplified to $3x + y \ge 20$)
2. Small buttons requirement: $2x + 4y \ge 60$ (can be simplified to $x + 2y \ge 30$)
3. Non-negativity constraints: $x \ge 0, y \ge 0$

**Solving graphically:**
Find coordinates where lines intersect the axes:
Line 1: $3x + y = 20$. If $x=0, y=20$ $(0,20)$. If $y=0, x=20/3$ $(6.67,0)$.
Line 2: $x + 2y = 30$. If $x=0, y=15$ $(0,15)$. If $y=0, x=30$ $(30,0)$.

Find the exact intersection point of the two lines by substitution:
From Line 1, $y = 20 - 3x$.
Substitute into Line 2: $x + 2(20 - 3x) = 30$
$x + 40 - 6x = 30$
$-5x = -10 \implies x = 2$
Substitute $x$ back: $y = 20 - 3(2) = 14$
Intersection point: **$(2, 14)$**.

Since the constraints are "greater than or equal to" ($\ge$), the feasible region is unbounded and formed by the outer boundaries. The corner points of the feasible region are:
A $(0, 20)$
B $(2, 14)$
C $(30, 0)$

Calculate the cost (Z) at these corner points:
At A $(0, 20): Z = 3(0) + 2(20) = \$40$
At B $(2, 14): Z = 3(2) + 2(14) = 6 + 28 = \$34$
At C $(30, 0): Z = 3(30) + 2(0) = \$90$

The minimum cost is $\$34$, which occurs at point $(2, 14)$.

**Final Answer:** The tailor should purchase **2 boxes and 14 cards** to minimize the expenditure to **$34**.
