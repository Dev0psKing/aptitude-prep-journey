Of course! This is a fantastic idea. A well-explained resource is key to learning. I've completely redesigned your markdown file, breaking down each solution into a beginner-friendly, step-by-step format with clear reasoning, visual cues, and a more engaging structure.

Here is the revamped version, ready for your repo:

---

# 🔢 Numbers — Solved Questions and Answers

> “Don't fear numbers. Fear not understanding them. Let's break them down, together.”

Welcome to your ultimate guide for mastering number-based aptitude questions. This section transforms complex problems into simple, digestible steps. Whether you're a beginner or just need a refresher, these explanations are designed for **clarity and deep understanding**.

---

## 📘 First, Let's Get Our Bearings

Before we dive in, let's recall two key ideas we'll use often:

*   **LCM (Least Common Multiple):** The smallest number that is a multiple of two or more numbers.
*   **Remainder:** What is "left over" after division.

---

## 🧮 Practice Questions: Solved Step-by-Step

### **Question 1: The Successive Division Puzzle**
**Problem:** When a number is divided by 35, 45, and 55, the remainders are 18, 28, and 38, respectively. What is the smallest such number?

---

#### **🛠️ Step-by-Step Solution**

**Step 1: Understand the Pattern**
If a number gives a remainder, it means the number is *just a little bit less* than a perfect multiple. Notice the remainders (18, 28, 38) are all 17 less than their respective divisors (35, 45, 55).

*   35 - 18 = 17
*   45 - 28 = 17
*   55 - 38 = 17

This means if we **add 17** to our mystery number (`N`), it would be perfectly divisible by 35, 45, and 55!

**Step 2: Find the Number that Fits All Three**
A number divisible by 35, 45, and 55 is a **common multiple** of them. We want the *smallest* number, so we find the **Least Common Multiple (LCM)**.

*   Prime Factors:
    *   35 = 5 × 7
    *   45 = 3² × 5
    *   55 = 5 × 11
*   LCM = 3² × 5 × 7 × 11 = **3465**

So, `N + 17 = 3465` (or a larger multiple of it).

**Step 3: Find the Original Number (N)**
Since we want the smallest `N`, we take the smallest common multiple.
`N + 17 = 3465`
Therefore, `N = 3465 - 17 = 3448`

---

#### ✅ **Final Answer:** **3448**

---

### **Question 2: Counting the Divisible**
**Problem:** How many four-digit numbers are divisible by 7?

---

#### **🛠️ Step-by-Step Solution**

**Step 1: Find the First Four-Digit Number Divisible by 7**
The smallest 4-digit number is 1000.
*   1000 ÷ 7 = 142.857...
*   This isn't a whole number. The next whole number is 143.
*   So, the first valid number is: `143 × 7 = 1001`.

**Step 2: Find the Last Four-Digit Number Divisible by 7**
The largest 4-digit number is 9999.
*   9999 ÷ 7 = 1428.428...
*   This isn't a whole number. The last whole number is 1428.
*   So, the last valid number is: `1428 × 7 = 9996`.

**Step 3: Count How Many Numbers Are in This Sequence**
We have a sequence: 1001, 1008, 1015, ..., 9996. This is an arithmetic sequence where each number is 7 more than the last.

The formula for the number of terms (`n`) in a sequence is:
`Last Number = First Number + (n - 1) × Common Difference`

Plug in our values:
`9996 = 1001 + (n - 1) × 7`

Now solve for `n`:
1.  `9996 - 1001 = (n - 1) × 7`
2.  `8995 = (n - 1) × 7`
3.  `n - 1 = 8995 ÷ 7`
4.  `n - 1 = 1285`
5.  `n = 1286`

---

#### ✅ **Final Answer:** **1286** four-digit numbers are divisible by 7.

---

### **Question 3: The Cryptic Addition**
**Problem:** Find the maximum value of **B** in this addition:

```
  1 2 B
+ B 4 C
+ C 6 7
--------
 1 0 3 5
```

---

#### **🛠️ Step-by-Step Solution**

**Step 1: Focus on the Units Column (Ones Place)**
We add: `B + C + 7`. The result ends with a **5**.
So, `B + C + 7 = _5` (a number ending in 5, like 5, 15, or 25).

The most likely scenario is `B + C + 7 = 15` (it can't be 5 because B and C are at least 0, and 0+0+7=7, which is too small. It's unlikely to be 25 as that would require B and C to be 9 and 9, which we can test later).
So, `B + C = 15 - 7 = 8`.  **(Equation 1)**

**Step 2: Focus on the Hundreds Column**
We add: `1 + B + C`. From Equation 1, we know `B + C = 8`.
So, `1 + B + C = 1 + 8 = 9`.

But the result in the hundreds place is **0**. This means there must be a **carry-over** from the tens column that turned 9 into 10.
Let's call the carry-over from the tens column `carry_tens`.
So, `1 + B + C + carry_tens = 10`.
We know `B+C=8`, so: `1 + 8 + carry_tens = 10` → `9 + carry_tens = 10` → `carry_tens = 1`.

**Step 3: Focus on the Tens Column (with the Carry)**
We add: `2 + 4 + 6 + carry_tens = 2 + 4 + 6 + 1 = 13`.
This means we write down **3** in the tens place and carry over **1** to the hundreds column (which we already used in Step 2). Everything matches so far.

**Step 4: Maximize B**
From Equation 1: `B + C = 8`.
To maximize `B`, we minimize `C`. The smallest digit `C` can be is **0**.
If `C = 0`, then `B = 8`.

Let's verify with `B=8` and `C=0`:
```
  1 2 8
+ 8 4 0
+ 0 6 7
--------
 1 0 3 5
```
Adding the units: 8+0+7=15 (write 5, carry 1). ✅
Adding the tens: 2+4+6+1(carried)=13 (write 3, carry 1). ✅
Adding the hundreds: 1+8+0+1(carried)=10. ✅
It works perfectly.

---

#### ✅ **Final Answer:** The maximum value of **B** is **8**.

---

### **Question 4: Prime Number Detective**
**Problem:** Which of these are prime numbers?
(i) 247 (ii) 397 (iii) 423

---

#### **🛠️ Step-by-Step Solution**

A prime number is only divisible by 1 and itself. We test divisibility by small primes.

**Check 247:**
*   Is it even? No.
*   Sum of digits (2+4+7=13) not divisible by 3.
*   Check for 7: 7×35=245. 247 - 245 = 2. Not divisible.
*   Check for 13: 13×19=247. ✅ Exactly divisible!
*   **Conclusion:** 247 is **Composite**.

**Check 397:**
*   Is it even? No.
*   Sum of digits (3+9+7=19) not divisible by 3.
*   Check for 7: 7×56=392. 397-392=5. Not divisible.
*   Check for 11: 11×36=396. 397-396=1. Not divisible.
*   Check for 13: 13×30=390. 397-390=7. Not divisible.
*   Check for 17: 17×23=391. 397-391=6. Not divisible.
*   Check for 19: 19×20=380. 397-380=17. Not divisible.
*   The next prime is 23, and 23² = 529, which is greater than 397. We can stop checking.
*   **Conclusion:** 397 is **Prime**.

**Check 423:**
*   Sum of digits (4+2+3=9) is divisible by 3. (9 ÷ 3 = 3).
*   Therefore, 423 ÷ 3 = 141.
*   **Conclusion:** 423 is **Composite**.

---

#### ✅ **Final Answer:** Only **397** is a prime number.

---

### **Question 5 & 6: The Power of the Last Digit**
**Problem 5:** Find the unit’s digit of (17)¹⁵³ × (31)⁶².
**Problem 6:** Find the unit’s digit of (17)¹⁵³ + (31)⁶².

---

#### **🛠️ Step-by-Step Solution**

**Core Concept: Cyclicity**
The unit's digit of a product depends only on the unit's digits of the numbers being multiplied. Many digits follow a repeating cycle (cyclicity).

*   **Digit 7's Cycle:** [**7**, 9, 3, 1] → Repeats every 4 powers.
    *   7¹ → 7
    *   7² → 49 → unit digit 9
    *   7³ → 343 → unit digit 3
    *   7⁴ → 2401 → unit digit 1
    *   7⁵ → unit digit 7 again.
*   **Digit 1's Cycle:** [**1**] → 1 to any power is always 1.

**Solving Question 5: (17)¹⁵³ × (31)⁶²**
1.  Find unit digit of 17¹⁵³:
    *   The base is 17, so we look at the unit digit **7**.
    *   Find the position in the cycle: Divide the exponent 153 by the cycle length (4).
    *   `153 ÷ 4 = 38` with a **remainder of 1**.
    *   A remainder of 1 means we take the **1st** value in the cycle [7, 9, 3, 1], which is **7**.
2.  Find unit digit of 31⁶²:
    *   The base is 31, so we look at the unit digit **1**.
    *   1 to the power of anything is **1**.
3.  Multiply the unit digits: `7 × 1 = 7`.

#### ✅ **Final Answer for Q5:** **7**

**Solving Question 6: (17)¹⁵³ + (31)⁶²**
1.  From above, unit digit of 17¹⁵³ is **7**.
2.  Unit digit of 31⁶² is **1**.
3.  Add the unit digits: `7 + 1 = 8`.

#### ✅ **Final Answer for Q6:** **8**

---

### **Question 7: Counting Prime Factors**
**Problem:** Find the total number of prime factors in: (14)¹¹ × (7)² × (11)³

---

#### **🛠️ Step-by-Step Solution**

**Step 1: Break Everything into Prime Factors**
*   `(14)^11` = (2 × 7)¹¹ = **2¹¹ × 7¹¹**
*   `(7)^2` = **7²**
*   `(11)^3` = **11³**

**Step 2: Combine Everything**
Now multiply them all together:
`2¹¹ × 7¹¹ × 7² × 11³ = 2¹¹ × 7¹³ × 11³`

**Step 3: Count the Prime Factors**
The question asks for the **total number** of prime factors. This means we add up all the exponents.
*   Exponent of 2: **11**
*   Exponent of 7: **13**
*   Exponent of 11: **3**
*   Total = 11 + 13 + 3 = **27**

> **Note:** These are 27 prime factors when counted with multiplicity (i.e., 2 is counted 11 times).

---

#### ✅ **Final Answer:** **27**

---

### **Question 8: Divisibility Rules in Action**
**Problem:** Which digits replace * and # so that 12386*# is divisible by both 8 and 5?

---

#### **🛠️ Step-by-Step Solution**

We use divisibility rules.

**Rule for 5:** A number is divisible by 5 if its last digit is **0 or 5**.
*   Therefore, `#` must be **0**.

**Rule for 8:** A number is divisible by 8 if the number formed by its **last three digits** is divisible by 8.
*   Our number is `12386*#` and we know `#=0`.
*   So, the last three digits are: `6*0`.

**Step 3: Find * that makes `6*0` divisible by 8**
Let's test digits from 0 to 9:
*   `600 ÷ 8 = 75` → Divisible? ✅ Yes. So * can be **0**.
*   `610 ÷ 8 = 76.25` → No.
*   `620 ÷ 8 = 77.5` → No.
*   `630 ÷ 8 = 78.75` → No.
*   `640 ÷ 8 = 80` → Divisible? ✅ Yes. So * can be **4**.
*   `650 ÷ 8 = 81.25` → No.
*   `660 ÷ 8 = 82.5` → No.
*   `670 ÷ 8 = 83.75` → No.
*   `680 ÷ 8 = 85` → Divisible? ✅ Yes. So * can be **8**.
*   `690 ÷ 8 = 86.25` → No.

---

#### ✅ **Final Answer:** **# = 0**, and *** can be 0, 4, or 8**.

---

### **Questions 9 & 10: The Art of Making Numbers Divisible**
**Problem 9:** What least number must be **subtracted** from 9999 to make it divisible by 19?
**Problem 10:** What least number must be **added** to 9999 to make it divisible by 19?

---

#### **🛠️ Step-by-Step Solution**

The key is to find the **remainder** when 9999 is divided by 19.

**Step 1: Find the Remainder**
*   `9999 ÷ 19 = ?`
*   Let's calculate: 19 × 526 = 19 × (500 + 26) = 9500 + 494 = 9994.
*   `9999 - 9994 = 5`.
*   So, the **remainder is 5**.

**Solving Question 9: What to Subtract?**
If the remainder is 5, it means 9999 is "5 more" than a perfect multiple of 19. To make it perfectly divisible, we just need to **remove this extra 5**.
`9999 - 5 = 9994`, which is divisible by 19.

#### ✅ **Final Answer for Q9:** **5**

**Solving Question 10: What to Add?**
If the remainder is 5, how much do we need to add to reach the *next* multiple of 19?
The next multiple is `9999 + (19 - 5) = 9999 + 14`.
So, we need to add **14**.

#### ✅ **Final Answer for Q10:** **14**

---

### **Question 11: Remainder Trick**
**Problem:** A number when divided by 340 leaves a remainder of 47. What is the remainder when this number is divided by 17?

---

#### **🛠️ Step-by-Step Solution**

**Step 1: Express the Problem as an Equation**
Let the number be `N`.
If `N ÷ 340` gives remainder 47, we can write:
`N = 340 × a + 47` (where `a` is some quotient).

**Step 2: Relate it to the New Divisor (17)**
Notice that 340 is a multiple of 17? Let's check: `340 ÷ 17 = 20`. Yes!
So, we can rewrite the equation:
`N = (17 × 20 × a) + 47`
`N = 17 × (20a) + 47`

**Step 3: Find the New Remainder**
Now, when we divide `N` by 17, the first part, `17 × (20a)`, is perfectly divisible by 17. The remainder will come entirely from the second part, **47**.
So, we just need to find the remainder when `47` is divided by `17`.
`47 ÷ 17 = 2` with a remainder of `13` (because 17 × 2 = 34, and 47 - 34 = 13).

---

#### ✅ **Final Answer:** **13**

---

### **Question 12: The Cycle Strikes Again**
**Problem:** Find the remainder when 3²¹ is divided by 5.

---

#### **🛠️ Step-by-Step Solution**

This is similar to finding the unit's digit, because the remainder when dividing by 5 is determined *only* by the unit's digit (e.g., a number ending in 1 gives remainder 1, ending in 2 gives remainder 2, etc.).

**Step 1: Find the Cyclicity of 3's Unit Digit**
The cycle for the digit 3 is: [**3**, 9, 7, 1]. It repeats every 4 powers.
*   3¹ → 3
*   3² → 9
*   3³ → 27 → unit digit 7
*   3⁴ → 81 → unit digit 1

**Step 2: Find the Position in the Cycle**
*   Exponent is 21.
*   `21 ÷ 4 = 5` with a **remainder of 1**.
*   A remainder of 1 means we take the **1st** value in the cycle [3, 9, 7, 1], which is **3**.

**Step 3: Relate to the Remainder**
A unit digit of **3** means the number ends with 3. When you divide a number ending in 3 by 5, the remainder is **3**.

---

#### ✅ **Final Answer:** **3**

---

## 💡 Key Takeaways & Mindset
*   **Break it Down:** Every complex problem is a series of simple steps.
*   **Patterns are Your Friend:** Cyclicity (for unit digits) and divisibility rules save immense time.
*   **Understand the "Why":** Knowing *why* a formula works (like `LCM - common difference`) is better than just memorizing it.
*   **Practice Makes Permanent:** The more you solve, the more these techniques become second nature.

---

## 🧭 What's Next?
Feel confident with these? Let's build on this foundation!
➡️ **[LCM & HCF — Solved Problems](../LCM_HCF/README.md)**

---

**Author:** [Uwabor Collins](https://github.com/Dev0psKing)  
**Repository:** [Aptitude Prep Journey](https://github.com/Dev0psKing/aptitude-prep-journey)  
*Happy Learning! 🌟*