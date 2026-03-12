# Section 0 — Mathematical Foundations
## 9. Optimization Problem

Problem:
- Curve: $y = 3 - x^2$ in first quadrant.
- Find rectangle under curve with maximum area, with one corner at origin, opposite corner $(x, y)$ on curve.

---

### 1) Set up area function
- Using $y = 3 - x^2$ and rectangle area $A = x y$.
- Then $A(x)=x(3-x^2)=3x-x^3$ for $0\le x\le\sqrt{3}$.

### 2) Find derivative and critical point
- $A'(x)=3-3x^2 = 3(1-x^2)$.
- Solve $A'(x)=0$: $x = \pm 1$; in the first quadrant $x=1$.

### 3) Second derivative test
- $A''(x)=-6x$.
- At $x=1$: $A''(1)=-6 < 0$ → local maximum.

### 4) Evaluate maximum area
- $y(1)=3-1^2 = 2$.
- $A(1)=1\cdot 2 = 2$.

---

## Final answer
- Optimal rectangle dimensions: width $x=1$, height $y=2$.
- Maximum area: $2$.
