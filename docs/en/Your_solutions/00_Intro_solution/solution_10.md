# Section 0 — Mathematical Foundations
## 10. Infinite Series

Problem:
- Starting point (0,0).
- Moves: 1 m east, 1/2 m north, 1/3 m west, 1/4 m south, 1/5 m east, ...
- Determine final position after infinitely many steps.

---

### 1) Separate coordinates
- East (+x), west (-x); north (+y), south (-y).
- x series: $1 - \frac13 + \frac15 - \frac17 + \dots$
- y series: $\frac12 - \frac14 + \frac16 - \frac18 + \dots$

### 2) Recognize series
- x series is alternating odd reciprocals: $\sum_{k=0}^{\infty} \frac{(-1)^k}{2k+1} = \arctan(1) = \frac{\pi}{4}$.
- y series is one-half of alternating even reciprocals:
  $\sum_{k=1}^{\infty} \frac{(-1)^{k-1}}{2k} = \frac12\ln 2$ (because $\ln 2 = 1 - 1/2 + 1/3 - 1/4 + ...$);
  with even terms only, formula gives $\frac12\ln 2$.

### 3) Final coordinates
- $x_{final} = \frac{\pi}{4}$.
- $y_{final} = \frac12\ln 2$.

---

### 4) Final answer
- Final position: $(x, y)=\left(\frac{\pi}{4},\frac{1}{2}\ln 2\right)$.
