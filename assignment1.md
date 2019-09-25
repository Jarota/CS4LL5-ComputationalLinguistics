# Probability Exercises
James Tait - 16321184

---
####Q1
i)

$P(A \wedge B) = P(A) \times P(B)$

$\frac{P(A \wedge B)}{P(B)} = P(A)$

$\frac{P(A \wedge B)}{P(B)} = P(A|B) = P(A)$

ii)

$P(A|B) = P(A)$

$P(A|B) = \frac{P(A \wedge B)}{P(B)} = P(A)$

$P(A \wedge B) = P(A) \times P(B)$

---
####Q2

|     | gw  | ¬gw |
|:---:|:---:|:---:|
|**ps**|28  |  2  |
|**¬ps**|140|  30 |

a)

$28+2+140+30 = 200$

$P(gw|ps) = \frac{P(gw \wedge ps)}{P(ps)}$

$P(gw \wedge ps) = \frac{28}{200} = 0.14$

$P(ps) = \frac{30}{200} = 0.15$

$P(gw|ps) = \frac{0.14}{0.15} = 0.93$

The counts where Potter did not catch the Golden Snitch (ie the bottom row) are irrelevant to this calculation.

b)

$P(ps|gw) = \frac{P(ps \wedge gw)}{P(gw)}$

$P(ps \wedge gw) = 0.14$

$P(gw) = \frac{168}{200} = 0.84$

$P(ps|gw) = \frac{0.14}{0.84} = 0.01$

The count where Gryffindor did not win (ie the right column) are not relevant to this calculation.

---
####Q3
a)

$p(vmel) = 0.01, p(dbi|vmel) = 0.95, p(dbi|¬vmel) = 0.01$

###$p(vmel|dbi) = \frac{p(vmel \wedge dbi)}{p(dbi)}$

$p(vmel \wedge dbi) = p(dbi|vmel) \times p(vmel)$

$p(vmel \wedge dbi) = 0.95 \times 0.01 = 0.0095$

$p(dbi) = p(dbi|vmel) \vee p(dbi|¬vmel)$

$p(dbi) = 0.95 + 0.01 = 0.96$

$p(vmel|dbi) = \frac{0.0095}{0.96} =0.0099$

###$p(¬vmel|dbi) = \frac{p(¬vmel \wedge dbi)}{p(dbi)}$

$p(¬vmel \wedge dbi) = p(dbi|¬vmel) \times p(¬vmel)$

$p(¬vmel \wedge dbi) = 0.01 \times 0.99 = 0.0099$

$p(¬vmel|dbi) = \frac{0.0099}{0.96} = 0.0103$

**¬vmel is likelier.**

b)

$p(vmel) = 0.15, p(dbi|vmel) = 0.95, p(dbi|¬vmel) = 0.01$

###$p(vmel|dbi) = \frac{p(vmel \wedge dbi)}{p(dbi)}$

$p(vmel \wedge dbi) = p(dbi|vmel) \times p(vmel)$

$p(vmel \wedge dbi) = 0.95 \times 0.15 = 0.1425$

$p(dbi) = p(dbi|vmel) \vee p(dbi|¬vmel)$

$p(dbi) = 0.95 + 0.01 = 0.96$

$p(vmel|dbi) = \frac{0.1425}{0.96} =0.1484$

###$p(¬vmel|dbi) = \frac{p(¬vmel \wedge dbi)}{p(dbi)}$

$p(¬vmel \wedge dbi) = p(dbi|¬vmel) \times p(¬vmel)$

$p(¬vmel \wedge dbi) = 0.01 \times 0.85 = 0.0085$

$p(¬vmel|dbi) = \frac{0.0085}{0.96} = 0.0089$

**vmel is likelier.**

c)

$p(vmel) = 0.01, p(dbi|vmel) = 0.95, p(dbi|¬vmel) = 0.001$

###$p(vmel|dbi) = \frac{p(vmel \wedge dbi)}{p(dbi)}$

$p(vmel \wedge dbi) = p(dbi|vmel) \times p(vmel)$

$p(vmel \wedge dbi) = 0.95 \times 0.01 = 0.0095$

$p(dbi) = p(dbi|vmel) \vee p(dbi|¬vmel)$

$p(dbi) = 0.95 + 0.001 = 0.951$

$p(vmel|dbi) = \frac{0.0095}{0.951} =0.01$

###$p(¬vmel|dbi) = \frac{p(¬vmel \wedge dbi)}{p(dbi)}$

$p(¬vmel \wedge dbi) = p(dbi|¬vmel) \times p(¬vmel)$

$p(¬vmel \wedge dbi) = 0.001 \times 0.99 = 0.00099$

$p(¬vmel|dbi) = \frac{0.00099}{0.951} = 0.001$

**vmel is likelier.**

---
####Q4

|           | noisy: +  | noisy: - |
|:---:      |:---:      |:---:     |
|**cool: +**| 62        | 108      |
|**cool: -**| 38        | 292      |

$62 + 108 + 38 + 292 = 500$

$p(cool: +) = \frac{170}{500} = 0.34$

$p(cool: +|noisy: +) = \frac{p(cool: + \wedge noisy: +)}{p(noisy: +)}$

$p(cool: + \wedge noisy: +) = \frac{62}{500} = 0.124$

$p(noisy: +) = \frac{100}{500} = 0.2$

$p(cool: +|noisy: +) = \frac{0.124}{0.2} = 0.62$

$0.34 \ne 0.62$

**cool: + is not independent of noisy: +.**

---
####Q5

|  open: +  | noisy: +  | noisy: - |
|:---:      |:---:      |:---:     |
|**cool: +**| 54        | 36       |
|**cool: -**| 6         | 4        |

|  open: -  | noisy: +  | noisy: - |
|:---:      |:---:      |:---:     |
|**cool: +**| 8         | 72       |
|**cool: -**| 32        | 288      |

$p(cool: +|open: +) = \frac{54 + 36}{100} = 0.9$

$p(cool: +|open: +, noisy: +) = \frac{54}{60} = 0.9$

**cool: + is conditionally independent of noisy: + given open: +.**

$p(cool: +|open: -) = \frac{8 + 72}{400} = 0.2$

$p(cool: +|open: -, noisy: +) = \frac{8}{40} = 0.2$

**cool: + is conditionally independent of noisy: + given open: -.**
