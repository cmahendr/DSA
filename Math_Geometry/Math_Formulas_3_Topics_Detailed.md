# 📘 Mathematics Formula Handbook (Detailed Revision Notes)

This document covers:

1. **Sequences & Series (AP, GP, HP)**
2. **Linear Equations & Algebra**
3. **Basic Geometry & Mensuration**

---

# 1️⃣ Sequences & Series

---

## 🔹 Arithmetic Progression (AP)

### Definition
A sequence where the difference between consecutive terms is constant.

\[
a,\; a+d,\; a+2d,\; a+3d,\; ...
\]

Where:
- **a** = first term  
- **d** = common difference  
- **n** = number of terms  

---

### 📌 nth Term
\[
a_n = a + (n-1)d
\]

**Example:**  
a = 3, d = 4  
Find 5th term:

\[
a_5 = 3 + (5-1)\cdot4 = 19
\]

---

### 📌 Sum of First n Terms
\[
S_n = \frac{n}{2}\,[2a + (n-1)d]
\]

Alternate form (when last term **l** is known):
\[
S_n = \frac{n}{2}(a + l)
\]

**Example:**  
a = 2, d = 3, n = 5

\[
S_5 = \frac{5}{2}[2\cdot2 + (5-1)\cdot3] = 40
\]

---

### 📌 Mean of an AP
\[
\text{Mean} = \frac{\text{first term} + \text{last term}}{2}
\]

---

### 📌 Special Case (Sum of first n natural numbers)
\[
1+2+3+\cdots+n = \frac{n(n+1)}{2}
\]

---

## 🔹 Geometric Progression (GP)

### Definition
A sequence where each term is multiplied by a constant ratio.

\[
a,\; ar,\; ar^2,\; ar^3,\; ...
\]

Where:
- **a** = first term  
- **r** = common ratio  

---

### 📌 nth Term
\[
a_n = a\cdot r^{n-1}
\]

**Example:**  
a = 3, r = 2, n = 4

\[
a_4 = 3\cdot 2^3 = 24
\]

---

### 📌 Sum of First n Terms (Finite GP)

If \(r \neq 1\):

\[
S_n = \frac{a(1-r^n)}{1-r}
\]

Alternative form:

\[
S_n = \frac{a(r^n-1)}{r-1}
\]

**Example:**  
a = 3, r = 2, n = 4

\[
S_4 = \frac{3(1-2^4)}{1-2} = 45
\]

---

### 📌 Infinite GP (|r| < 1)

\[
S_\infty = \frac{a}{1-r}
\]

**Example:**  
a = 5, r = 1/2

\[
S_\infty = \frac{5}{1-\frac12} = 10
\]

---

## 🔹 Harmonic Progression (HP)

### Definition
A sequence is in HP if the reciprocals are in AP.

If AP is:
\[
a,\; a+d,\; a+2d,\; ...
\]

Then HP is:
\[
\frac{1}{a},\; \frac{1}{a+d},\; \frac{1}{a+2d},\; ...
\]

---

### 📌 Example
AP: 2, 4, 6  
HP: 1/2, 1/4, 1/6

---

# 2️⃣ Linear Equations & Algebra

---

## 🔹 Linear Equation (One Variable)

\[
ax + b = 0
\]

\[
x = -\frac{b}{a}
\]

**Example:**  
\[
2x + 6 = 0 \Rightarrow x = -3
\]

---

## 🔹 Linear Equations (Two Variables)

\[
a_1x + b_1y = c_1
\]
\[
a_2x + b_2y = c_2
\]

---

### 📌 Determinant Method (Cramer’s Rule)

Denominator:

\[
D = a_1b_2 - a_2b_1
\]

\[
x = \frac{c_1b_2 - c_2b_1}{D}
\]

\[
y = \frac{a_1c_2 - a_2c_1}{D}
\]

---

## 🔹 Quadratic Equation

\[
ax^2 + bx + c = 0
\]

\[
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
\]

---

### 📌 Discriminant
\[
D = b^2 - 4ac
\]

- \(D > 0\) → Two distinct real roots  
- \(D = 0\) → Two equal real roots  
- \(D < 0\) → Complex roots  

---

## 🔹 Algebraic Identities

\[
(a+b)^2 = a^2 + 2ab + b^2
\]

\[
(a-b)^2 = a^2 - 2ab + b^2
\]

\[
a^2 - b^2 = (a-b)(a+b)
\]

\[
(a+b)^3 = a^3 + b^3 + 3ab(a+b)
\]

\[
(a-b)^3 = a^3 - b^3 - 3ab(a-b)
\]

\[
a^3 + b^3 = (a+b)(a^2 - ab + b^2)
\]

\[
a^3 - b^3 = (a-b)(a^2 + ab + b^2)
\]

---

## 🔹 Binomial Theorem

\[
(a+b)^n = \sum_{k=0}^{n} {n \choose k} a^{n-k}b^k
\]

---

## 🔹 Logarithm Rules

\[
\log(ab) = \log a + \log b
\]

\[
\log\left(\frac{a}{b}\right) = \log a - \log b
\]

\[
\log(a^n) = n\log a
\]

\[
\log_a b = \frac{\log b}{\log a}
\]

---

# 3️⃣ Basic Geometry & Mensuration

---

# 🔹 2D Shapes

---

## Rectangle
- Area: \(A = l \times b\)  
- Perimeter: \(P = 2(l+b)\)  
- Diagonal: \(d = \sqrt{l^2 + b^2}\)

---

## Square
- Area: \(A = a^2\)  
- Perimeter: \(P = 4a\)  
- Diagonal: \(d = a\sqrt{2}\)

---

## Triangle

### Area
\[
A = \frac12 bh
\]

### Heron’s Formula
\[
s = \frac{a+b+c}{2}
\]
\[
A = \sqrt{s(s-a)(s-b)(s-c)}
\]

---

## Equilateral Triangle
\[
A = \frac{\sqrt{3}}{4}a^2
\]
\[
h = \frac{\sqrt{3}}{2}a
\]

---

## Circle
- Area: \(A = \pi r^2\)  
- Circumference: \(C = 2\pi r\)  
- Diameter: \(d = 2r\)

### Sector Area
\[
A = \frac{\theta}{360}\pi r^2
\]

### Arc Length
\[
L = \frac{\theta}{360}2\pi r
\]

---

## Parallelogram
\[
A = b\cdot h
\]
\[
P = 2(a+b)
\]

---

## Rhombus
\[
A = \frac12 d_1 d_2
\]
\[
P = 4a
\]

---

## Trapezium
\[
A = \frac12(a+b)h
\]

---

## Regular Polygon
\[
A = \frac{n s^2}{4\tan(\pi/n)}
\]

---

# 🔹 3D Shapes (Mensuration)

---

## Cube
- Surface Area: \(6a^2\)  
- Volume: \(a^3\)  
- Diagonal: \(a\sqrt{3}\)

---

## Cuboid
\[
TSA = 2(lb + bh + hl)
\]
\[
V = lbh
\]
\[
Diagonal = \sqrt{l^2 + b^2 + h^2}
\]

---

## Cylinder
\[
CSA = 2\pi rh
\]
\[
TSA = 2\pi r(h+r)
\]
\[
V = \pi r^2 h
\]

---

## Cone
\[
l = \sqrt{r^2 + h^2}
\]
\[
CSA = \pi rl
\]
\[
TSA = \pi r(l+r)
\]
\[
V = \frac13 \pi r^2 h
\]

---

## Sphere
\[
SA = 4\pi r^2
\]
\[
V = \frac{4}{3}\pi r^3
\]

---

## Hemisphere
\[
SA = 3\pi r^2
\]
\[
V = \frac{2}{3}\pi r^3
\]

---

## Frustum of Cone
\[
V = \frac13 \pi h(R^2 + r^2 + Rr)
\]

---

# 🔹 Coordinate Geometry

---

## Distance Formula
\[
d = \sqrt{(x_2-x_1)^2 + (y_2-y_1)^2}
\]

---

## Midpoint Formula
\[
\left(\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2}\right)
\]

---

## Slope of a Line
\[
m = \frac{y_2-y_1}{x_2-x_1}
\]

---

## Equation of a Line
\[
y = mx + c
\]

---

## Section Formula (Internal Division)
If a point divides a line segment joining A(x1,y1) and B(x2,y2) in ratio m:n:

\[
\left(\frac{mx_2 + nx_1}{m+n}, \frac{my_2 + ny_1}{m+n}\right)
\]

---

# ✅ End of Document
