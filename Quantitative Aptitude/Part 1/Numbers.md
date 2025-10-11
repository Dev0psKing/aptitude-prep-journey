# 🔢 Numbers - Foundation of Quantitative Aptitude

Numbers are the **building blocks of mathematics** - every calculation, equation, and logical expression is derived from them.  
In this module, we’ll explore **types of numbers**, **divisibility rules**, **remainders**, **cyclicity**, and more - essential for aptitude and reasoning mastery.

---

![GitHub repo size](https://img.shields.io/github/repo-size/Dev0psKing/aptitude-prep-journey?color=blue&label=Repo%20Size&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/Dev0psKing/aptitude-prep-journey?color=brightgreen&style=flat-square)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

---

## 🧮 Overview
> “Mathematics is the language of logic — and numbers are its alphabet.”

This topic introduces:
- Types and classifications of numbers  
- Divisibility and remainder shortcuts  
- Patterns and cyclicity for rapid mental calculation  
- Essential theorems for exam-oriented reasoning  

---

## 🧩 Types of Numbers

| **Type** | **Definition** | **Examples** |
|-----------|----------------|---------------|
| **Integers** | Numbers without a fractional part | -3, -2, -1, 0, 1, 2, 3 |
| **Natural Numbers** | Counting numbers starting from 1 | 1, 2, 3, 4, 5… |
| **Whole Numbers** | All natural numbers including 0 | 0, 1, 2, 3, 4… |
| **Prime Numbers** | Numbers with exactly two factors (1 and itself) | 2, 3, 5, 7, 11… |
| **Composite Numbers** | Numbers greater than 1 that are **not prime** | 4, 6, 8, 9, 10… |

<img width="1042" height="745" alt="image" src="https://github.com/user-attachments/assets/d3bfcbe7-5d0b-4aa2-9253-911570cb608a" />

---

## 🧠 Important Notes on Prime Numbers

- 0 and 1 are **neither prime nor composite**.  
- 2 is the **only even prime number**.  
- There are **25 prime numbers** below 100:  
  `2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97`.

> ✅ **Prime Test Rule:**  
> For a number `p`, find the smallest integer `n` such that `n² ≥ p`.  
> If `p` is not divisible by any prime ≤ `n`, then `p` is prime.

---

### 🤝 Co-Primes
Two numbers are **co-prime** if their **HCF = 1**.  
Example: (8, 15) are co-prime, but (8, 12) are not.

---

### 🔍 Finding the Number of Divisors

If  
`n = p₁^e₁ × p₂^e₂ × p₃^e₃ × ... × pₖ^eₖ`  

Then,  
**Total divisors of n =** `(e₁ + 1)(e₂ + 1)(e₃ + 1)...(eₖ + 1)`

**Example:**  
200 = `2³ × 5²`  
→ Number of divisors = `(3 + 1)(2 + 1) = 12`

---

## ⚖️ Divisibility Rules

| **Divisible by** | **Rule** | **Example** |
|------------------|----------|--------------|
| **2** | Last digit is even | 124 → ✅ |
| **3** | Sum of digits divisible by 3 | 12321 → 1+2+3+2+1=9 ✅ |
| **4** | Last two digits divisible by 4 | 1232 → 32 ÷ 4 ✅ |
| **5** | Last digit is 0 or 5 | 85 → ✅ |
| **6** | Divisible by both 2 and 3 | 114 → ✅ |
| **7** | Double last digit, subtract → result divisible by 7 | 196 → 19 - 12 = 7 ✅ |
| **8** | Last three digits divisible by 8 | 1232 → 232 ÷ 8 ✅ |
| **9** | Sum of digits divisible by 9 | 12321 → 9 ✅ |
| **11** | Difference between sums of alternate digits is 0 or multiple of 11 | 121 → (1+1)-(2)=0 ✅ |

---

### 💡 Other Quick Rules
- Repeating a 3-digit number twice (e.g., 376376) → always divisible by **7, 11, and 13**.  
- A number of form `2^N` has **N + 1 divisors**.  
  Example: 4 = 2² → (2 + 1) = 3 divisors (1, 2, 4).  
- If `p` and `q` are **co-prime**, and `n` is divisible by both → then `n` is divisible by `p × q`.  
  Example: 48 divisible by 3 and 8 → also by 24.

---

## 🔢 Remainder Rules

| **Divisor** | **Rule** | **Example** |
|--------------|-----------|--------------|
| **2** | Even → remainder 0; Odd → remainder 1 | 37 → remainder 1 |
| **3** | Sum digits → divide by 3 | 23 → 5 ÷ 3 → remainder 2 |
| **4** | Last 2 digits ÷ 4 | 123 → 23 ÷ 4 → remainder 3 |
| **5** | Last digit ÷ 5 | 32 → remainder 2 |
| **6** | Apply both 2 and 3 rules | 35 → remainder 5 |
| **7** | Alternate group sum rule | 198 → remainder 2 |
| **8** | Last 3 digits ÷ 8 | 1476 → remainder 4 |
| **9** | Sum digits ÷ 9 | 1234 → remainder 1 |

---

## 📘 Division Theorem
\[
\text{Dividend} = (\text{Divisor} × \text{Quotient}) + \text{Remainder}
\]

### 🔹 Key Results
1. **(xⁿ − aⁿ)** is divisible by **(x − a)** for all n  
   Example: x² − a² = (x − a)(x + a) ✅  
2. **(xⁿ − aⁿ)** is divisible by **(x + a)** if n is **even**  
   Example: x² − a² divisible by (x + a) ✅  
3. **(xⁿ + aⁿ)** is divisible by **(x + a)** if n is **odd**  
   Example: x³ + a³ = (x + a)(x² − xa + a²) ✅

---

## 🔁 Cyclicity of Numbers

Cyclicity determines the **repetition pattern of unit digits** when a number is raised to powers.

| **Digit** | **Cyclicity Pattern** | **Example** |
|------------|------------------------|--------------|
| 0, 1, 5, 6 | Same digit repeats | 5²=25 → 5, 6³=216 → 6 |
| 4 | 4, 6 | 4²=16, 4³=64 |
| 9 | 9, 1 | 9²=81, 9³=729 |
| 2 | 2, 4, 8, 6 | 2²=4, 2³=8, 2⁴=16 |
| 3 | 3, 9, 7, 1 | 3²=9, 3³=27, 3⁴=81 |
| 7 | 7, 9, 3, 1 | 7²=49, 7³=343 |
| 8 | 8, 4, 2, 6 | 8²=64, 8³=512 |

> 🧩 **Shortcut:**  
> If you know the cycle length, divide the power by it and use the remainder to find the unit digit instantly.

---

## 🧭 Navigation
← [Back to Quantitative Aptitude Overview](../README.md)  
↑ [Return to Main Repository](https://github.com/Dev0psKing/aptitude-prep-journey)

---

> ✨ *"Numbers are not just quantities — they are patterns of logic waiting to be discovered."*  
> — *Uwabor Collins*

---

### 🏷️ Tags
`#Numbers` `#QuantitativeAptitude` `#Divisibility` `#RemainderRules` `#Cyclicity` `#MathLogic`
