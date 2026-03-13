# Arithmetic vs Geometric Mean — Comparative Example

## Observation Series

| obs_num | value | delta | deltaPct | rate |
|---------|-------|-------|----------|------|
| 1 | 1 | | | |
| 2 | 2 | 1 | 100% | 2 |
| 3 | 1 | -1 | -50% | 0.5 |

The series returns to its initial value of 1.

---

## Where the Formula Inputs Come From

The two inputs — `2` and `0.5` — are the **rates** from the observation series:

| obs_num | transition | rate | meaning |
|---------|------------|------|---------|
| 1 → 2 | 1 to 2 | **2.0** | value doubled |
| 2 → 3 | 2 to 1 | **0.5** | value halved |

Both methods operate on these two rates.

---

## Mean Comparison

| Method | Formula | Expanded | Result |
|--------|---------|----------|--------|
| Arithmetic mean | (r₁ + r₂) / 2 | (2 + 0.5) / 2 | **1.25** |
| Geometric mean | sqrt(r₁ × r₂) | sqrt(2 × 0.5) | **1.00** |

---

## Interpretation

The arithmetic mean overstates central tendency at **1.25**, implying net growth that did not occur. The geometric mean returns **1.00**, correctly reflecting that the series ended where it started.

For multiplicative rate series, the geometric mean is the appropriate measure of central tendency.
