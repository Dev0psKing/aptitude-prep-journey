
---

# 📚 Advanced Remainder Theorems & Number System Applications

> "The only way to learn mathematics is to do mathematics." - **Paul Halmos**

This section explores more complex word problems and advanced remainder theorems. By understanding the underlying principles, you can solve these seemingly difficult questions with ease.

---

### **Question 44: The Division Sum**

**Problem:** In a division sum, the divisor is ten times the quotient and five times the remainder. If the remainder is 46, determine the dividend.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

This problem is a classic word puzzle that relies on the fundamental division formula. We'll work backward from the one piece of concrete information we have: the remainder.

1.  **Recall the Division Algorithm:**
    The core formula for any division is:
    `Dividend = Divisor × Quotient + Remainder`

2.  **Use the Given Information to Find the Divisor:**
    *   We are given: `Remainder = 46`.
    *   The problem states: "the divisor is... five times the remainder."
    *   `Divisor = 5 × Remainder = 5 × 46 = 230`.

3.  **Use the Divisor to Find the Quotient:**
    *   The problem also states: "the divisor is ten times the quotient."
    *   `Divisor = 10 × Quotient`
    *   `230 = 10 × Quotient`
    *   To find the quotient, divide by 10: `Quotient = 230 / 10 = 23`.

4.  **Calculate the Dividend:**
    *   Now we have all the pieces:
        *   Divisor = 230
        *   Quotient = 23
        *   Remainder = 46
    *   Plug these into the main formula:
        `Dividend = 230 × 23 + 46`
        `Dividend = 5290 + 46`
        `Dividend = 5336`

---

#### ✅ **Final Answer:** **The dividend is 5336**
`

### **Question 45: Solving with Two Variables**

**Problem:** If three times the larger of the two numbers is divided by the smaller one, we get 4 as quotient and 3 as remainder. Also, if seven times the smaller number is divided by the larger one, we get 5 as quotient and 1 as remainder. Find the numbers.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

This problem describes two different division scenarios. We can translate each scenario into an equation using the Division Algorithm, creating a system of two linear equations that we can solve.

1.  **Define Variables:**
    *   Let the larger number be `x`.
    *   Let the smaller number be `y`.

2.  **Translate the First Scenario into an Equation:**
    *   "three times the larger (`3x`) is divided by the smaller (`y`), we get 4 as quotient and 3 as remainder."
    *   Using `Dividend = Divisor × Quotient + Remainder`:
        `3x = y × 4 + 3`
        `3x - 4y = 3`  --- (Equation i)

3.  **Translate the Second Scenario into an Equation:**
    *   "seven times the smaller (`7y`) is divided by the larger (`x`), we get 5 as quotient and 1 as remainder."
    *   `7y = x × 5 + 1`
        `7y - 5x = 1` or `-5x + 7y = 1` --- (Equation ii)

4.  **Solve the System of Linear Equations:**
    *   We have:
        1.  `3x - 4y = 3`
        2.  `-5x + 7y = 1`
    *   We can use the elimination method. Let's eliminate `x`. To do this, we need to make the coefficients of `x` equal and opposite. The least common multiple of 3 and 5 is 15.
    *   Multiply Equation (i) by 5:
        `5 × (3x - 4y = 3)`  =>  `15x - 20y = 15` --- (Equation iii)
    *   Multiply Equation (ii) by 3:
        `3 × (-5x + 7y = 1)` => `-15x + 21y = 3` --- (Equation iv)

5.  **Add the New Equations to Eliminate x:**
    *   Add Equation (iii) and (iv):
        ```
          15x - 20y = 15
        + (-15x + 21y = 3)
        ------------------
           0x + 1y = 18
        ```
    *   So, `y = 18`.

6.  **Substitute to Find x:**
    *   Put the value `y = 18` back into one of the original equations (let's use Equation i):
        `3x - 4(18) = 3`
        `3x - 72 = 3`
        `3x = 75`
        `x = 25`

---

#### ✅ **Final Answer:** **The numbers are 25 and 18**
`

### **Question 46: Remainder of a Square**

**Problem:** A number when divided by 6 leaves a remainder of 3. When the square of the same number is divided by 6, find the remainder.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

We can solve this by representing the unknown number algebraically based on the information given.

1.  **Represent the Number Algebraically:**
    *   "A number when divided by 6 leaves remainder 3."
    *   Using the Division Algorithm, we can write this number as:
        `Number = (6 × k) + 3`, where `k` is some integer quotient.

2.  **Square the Number:**
    *   The problem asks about the square of this number:
        `Number² = (6k + 3)²`
    *   Expand this using the identity `(a+b)² = a² + 2ab + b²`:
        `(6k)² + 2(6k)(3) + 3²`
        `= 36k² + 36k + 9`

3.  **Find the Remainder When the Square is Divided by 6:**
    *   We need to find the remainder of `(36k² + 36k + 9) ÷ 6`.
    *   Let's analyze each term's divisibility by 6:
        *   `36k²` is perfectly divisible by 6 (since 36 is a multiple of 6).
        *   `36k` is perfectly divisible by 6.
        *   `9` is not. When `9` is divided by 6, the remainder is `3` (`9 = 6 × 1 + 3`).
    *   We can rewrite the expression to make this clear:
        `36k² + 36k + (6 + 3)`
    *   Now, group all the terms that are divisible by 6:
        `(36k² + 36k + 6) + 3`
    *   Factor out a 6 from the group:
        `6(6k² + 6k + 1) + 3`
    *   This expression is in the form `(6 × Quotient) + Remainder`. The part `6(6k² + 6k + 1)` is a perfect multiple of 6. The "leftover" part is the remainder.

---

#### ✅ **Final Answer:** **The remainder is 3**
`

## 🔑 Advanced Remainder Theorems

The following problems use specific algebraic identities related to divisibility.

-   **(xⁿ – aⁿ)** is always divisible by **(x – a)** for any positive integer `n`.
-   **(xⁿ – aⁿ)** is divisible by **(x + a)** when `n` is an **even** integer.
-   **(xⁿ + aⁿ)** is divisible by **(x + a)** when `n` is an **odd** integer.

### **Question 47: Remainder with Addition**

**Problem:** Find the remainder when 9⁶ + 7 is divided by 8.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

We want to use the identity `(xⁿ – aⁿ)` is divisible by `(x – a)`. Here, our divisor `8` can be written as `9 – 1`. This gives us a hint to use `x=9` and `a=1`.

1.  **Relate the Divisor to the Base:**
    *   Divisor = `8`. Base = `9`. Notice that `8 = 9 - 1`.

2.  **Manipulate the Expression to Fit the Identity:**
    *   We have `9⁶ + 7`. We need a `9⁶ - 1` term to use the rule. Let's create it by subtracting and adding 1:
        `9⁶ + 7 = (9⁶ - 1) + 1 + 7 = (9⁶ - 1) + 8`

3.  **Apply the Remainder Theorem:**
    *   The term `(9⁶ - 1)` can be written as `(9⁶ - 1⁶)`.
    *   According to the rule `(xⁿ – aⁿ)` is divisible by `(x – a)`, the term `(9⁶ – 1⁶)` is perfectly divisible by `(9 – 1) = 8`. So, this part leaves a remainder of `0`.
    *   The second term in our expression is `8`. This is also perfectly divisible by `8`, leaving a remainder of `0`.

4.  **Find the Total Remainder:**
    *   Since both parts of the expression `(9⁶ - 1) + 8` are perfectly divisible by 8, their sum is also perfectly divisible by 8.

---

#### ✅ **Final Answer:** **The remainder is 0**
`

### **Question 48: Remainder with Large Powers**

**Problem:** Find the remainder when (397)³⁵⁸⁹ + 5 is divided by 398.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

Here, the divisor `398` can be written as `397 + 1`. This hints at using the identity for `(xⁿ + aⁿ)`.

1.  **Relate the Divisor to the Base:**
    *   Divisor = `398`. Base = `397`. Notice that `398 = 397 + 1`.

2.  **Check the Relevant Identity:**
    *   The identity is: `(xⁿ + aⁿ)` is divisible by `(x + a)` when `n` is **odd**.
    *   Here, `x = 397`, `a = 1`, and the exponent `n = 3589`.
    *   Is `n = 3589` odd? Yes, it is. So the rule applies.

3.  **Manipulate the Expression:**
    *   We have `(397)³⁵⁸⁹ + 5`. We need a `(397)³⁵⁸⁹ + 1` term to use the rule.
    *   Let's rewrite `+ 5` as `+ 1 + 4`:
        `(397)³⁵⁸⁹ + 5 = [(397)³⁵⁸⁹ + 1] + 4`

4.  **Apply the Theorem:**
    *   The term `[(397)³⁵⁸⁹ + 1³⁵⁸⁹]` is perfectly divisible by `(397 + 1) = 398`. This part leaves a remainder of `0`.
    *   The leftover part of the expression is `+ 4`.

5.  **Determine the Final Remainder:**
    *   When the entire expression `[(397)³⁵⁸⁹ + 1] + 4` is divided by 398, the first part divides perfectly, leaving the second part as the remainder.

---

#### ✅ **Final Answer:** **The remainder is 4**
`

### **Question 49: Rewriting the Base**

**Problem:** If 7¹²⁶ is divided by 48, find the remainder.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

The divisor `48` can be written as `49 - 1`. This suggests we should try to make the base of our power `49`.

1.  **Relate the Divisor to a Power of the Base:**
    *   Divisor = `48`. Base = `7`.
    *   We notice that `7² = 49`, and `48 = 49 - 1`.

2.  **Rewrite the Expression:**
    *   We can rewrite `7¹²⁶` using the power rule `a^(m*n) = (a^m)^n`:
        `7¹²⁶ = 7^(2 × 63) = (7²)⁶³ = 49⁶³`.

3.  **Apply the Remainder Theorem:**
    *   We need to find the remainder of `49⁶³ ÷ 48`.
    *   Let's use the identity `(xⁿ – aⁿ)` is divisible by `(x – a)`.
    *   Let `x = 49`, `a = 1`, and `n = 63`.
    *   The expression `(49⁶³ – 1⁶³)` is perfectly divisible by `(49 – 1) = 48`.
    *   This means `49⁶³ - 1` is a multiple of 48.
    *   Therefore, `49⁶³` must be exactly `1` more than a multiple of 48.

---

#### ✅ **Final Answer:** **The remainder is 1**
`

### **Question 50: Difference of Powers**

**Problem:** Find the remainder when (257¹⁶⁶ – 243¹⁶⁶) is divided by 500.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

Here we have a difference of powers. Let's see how the divisor relates to the bases.

1.  **Relate the Divisor to the Bases:**
    *   Divisor = `500`. Bases = `257` and `243`.
    *   Notice that `257 + 243 = 500`.

2.  **Check the Relevant Identity:**
    *   The identity is: `(xⁿ – aⁿ)` is divisible by `(x + a)` when `n` is an **even** integer.
    *   Here, `x = 257`, `a = 243`, and the exponent `n = 166`.
    *   Is `n = 166` even? Yes, it is.

3.  **Apply the Theorem:**
    *   Since the exponent is even, `(257¹⁶⁶ – 243¹⁶⁶)` is perfectly divisible by `(257 + 243) = 500`.

---

#### ✅ **Final Answer:** **The remainder is 0**
`

### **Question 51: Finding a Common Factor**

**Problem:** Find a common factor of (127¹²⁷ + 97¹²⁷) and (127⁹⁷ + 97⁹⁷).

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

We need to find a number that divides both expressions perfectly. Let's check our remainder identities.

1.  **Analyze the First Expression:** `(127¹²⁷ + 97¹²⁷)`
    *   This is in the form `(xⁿ + aⁿ)`.
    *   Here, `x = 127`, `a = 97`, and `n = 127`.
    *   The identity `(xⁿ + aⁿ)` is divisible by `(x + a)` when `n` is **odd**.
    *   Since `127` is odd, the expression is divisible by `(127 + 97) = 224`.

2.  **Analyze the Second Expression:** `(127⁹⁷ + 97⁹⁷)`
    *   This is also in the form `(xⁿ + aⁿ)`.
    *   Here, `x = 127`, `a = 97`, and `n = 97`.
    *   Since `97` is also odd, this expression is also divisible by `(127 + 97) = 224`.

3.  **Conclusion:**
    *   Since both expressions are divisible by 224, `224` is a common factor.

---

#### ✅ **Final Answer:** **A common factor is 224**
`

### **Question 52: Divisibility by 16**

**Problem:** A 99–digit number is formed by writing the first 59 natural numbers one after the other as:
`1234567891011121314...5859`
Find the remainder obtained when the above number is divided by 16.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

This problem looks terrifying because of the huge number, but it's actually a simple test of a divisibility rule.

1.  **Recall the Divisibility Rule for 16:**
    *   The rules for powers of 2 are related:
        *   Divisibility by 2 (`2¹`): Last digit must be divisible by 2.
        *   Divisibility by 4 (`2²`): Last 2 digits must be divisible by 4.
        *   Divisibility by 8 (`2³`): Last 3 digits must be divisible by 8.
        *   **Divisibility by 16 (`2⁴`):** The number formed by the **last four digits** must be divisible by 16.
    *   The remainder when the whole number is divided by 16 is the same as the remainder when its last four digits are divided by 16.

2.  **Identify the Last Four Digits of the Number:**
    *   The large number is formed by writing numbers back-to-back, ending with `...5859`.
    *   The last four digits are `5859`.

3.  **Divide the Last Four Digits by 16:**
    *   We need to find the remainder of `5859 ÷ 16`.
    *   Let's perform the division:
        *   `58 ÷ 16 = 3` (`16×3=48`), remainder `10`.
        *   Bring down `5`, making it `105`. `105 ÷ 16 = 6` (`16×6=96`), remainder `9`.
        *   Bring down `9`, making it `99`. `99 ÷ 16 = 6` (`16×6=96`), remainder `3`.
    *   The final remainder is `3`.

---

#### ✅ **Final Answer:** **The remainder is 3**

---

**Author:** [Uwabor Collins](https://github.com/Dev0psKing)  
**Repository:** [Aptitude Prep Journey](https://github.com/Dev0psKing/aptitude-prep-journey)  

*Keep practicing! Every problem solved makes you stronger. 💪*