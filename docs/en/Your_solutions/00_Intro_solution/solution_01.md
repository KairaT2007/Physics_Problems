# Section 0 — Mathematical Foundations  
## 1. Vector Algebra

We are given two vectors in $\mathbb{R}^3$:

$$
\vec{a} = [2,\,1,\,-3], \qquad \vec{b} = [4,\,-2,\,1]
$$

---



### 1) Formulas used
1. Magnitude (length) of a vector:
   $$|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}$$
2. Dot product (scalar product):
   $$\vec{a}\cdot\vec{b} = a_x b_x + a_y b_y + a_z b_z$$
3. Cross product (vector product):
   $$\vec{a} \times \vec{b} = [a_y b_z - a_z b_y,\; a_z b_x - a_x b_z,\; a_x b_y - a_y b_x]$$
4. Angle between vectors:
   $$\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}|\,|\vec{b}|}, \qquad \theta = \arccos\left(\frac{\vec{a} \cdot \vec{b}}{|\vec{a}|\,|\vec{b}|}\right)$$

---

### 2) Step-by-step evaluation

#### a) Vector magnitudes
- For $\vec{a}$:
  $$|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14}$$
- For $\vec{b}$:
  $$|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21}$$

#### b) Dot product
- Compute:
  $$\vec{a} \cdot \vec{b} = 2\cdot4 + 1\cdot(-2) + (-3)\cdot1 = 8 - 2 - 3 = 3$$

#### c) Cross product
- Compute each component using the formula:
  - $x$-component: $a_y b_z - a_z b_y = 1\cdot1 - (-3)\cdot(-2) = 1 - 6 = -5$
  - $y$-component: $a_z b_x - a_x b_z = (-3)\cdot4 - 2\cdot1 = -12 - 2 = -14$
  - $z$-component: $a_x b_y - a_y b_x = 2\cdot(-2) - 1\cdot4 = -4 - 4 = -8$
- Thus:
  $$\vec{a} \times \vec{b} = [-5, -14, -8]$$

#### d) Angle between vectors
- Compute cosine:
  $$\cos\theta = \frac{3}{\sqrt{14}\,\sqrt{21}} = \frac{3}{\sqrt{294}}$$
- Then angle:
  $$\theta = \arccos\left(\frac{3}{\sqrt{294}}\right)$$
- Approximate value:
  $$\theta \approx 1.396\ \text{rad} \approx 80^\circ$$

---

### 3) Final answers
- $|\vec{a}| = \sqrt{14}$
- $|\vec{b}| = \sqrt{21}$
- $\vec{a} \cdot \vec{b} = 3$
- $\vec{a} \times \vec{b} = [-5, -14, -8]$
- $\theta \approx 80^\circ$

