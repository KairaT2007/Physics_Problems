# Section 0 — Mathematical Foundations
## 6. Function Analysis

Given function:
$$f(x)=3x^2-12x+7$$

Task: identify local maxima or minima.

---

### 1) Formulas and method
- For a quadratic $f(x)=ax^2+bx+c$ with $a\neq0$:
  - Vertex at $x_v=-\frac{b}{2a}$
  - If $a>0$, vertex is minimum; if $a<0$, vertex is maximum.
- Derivative method:
  - $f'(x)=2ax+b$, set $f'(x)=0$ to find critical point,
  - $f''(x)=2a$ to classify min/max.

### 2) Apply to $f(x)=3x^2-12x+7$
- $a=3$, $b=-12$, $c=7$.
- Derivative: $f'(x)=6x-12$.
- Solve $f'(x)=0$: $6x-12=0 \Rightarrow x=2$.
- Second derivative: $f''(x)=6>0$, so this is a local minimum.

### 3) Value at the critical point
- $f(2)=3\cdot2^2-12\cdot2+7 = 12-24+7 = -5$.

---

## Final answer
- Local minimum at $x=2$, with value $f(2)=-5$.
- No local maximum (quadratic opens upward).
