
---

# 🔢 Numbers - Solved Questions and Answers (Expanded Explanations)

> “Numbers are the foundation of all reasoning - master them, and logic follows naturally.”

This section presents **practice questions with fully worked solutions** and **extra-detailed explanations** to strengthen your grasp of number theory, divisibility, and remainders - core areas in **quantitative aptitude** and **competitive reasoning tests**. We'll break down each step so it's easy to follow!

---

## 📘 Overview

A **number** is just a way to count things, made up of digits (like 0, 1, 2, 3, 4, 5, 6, 7, 8, 9) arranged in a specific order.  
These solved questions cover key numerical concepts like **LCM (Least Common Multiple)**, **HCF (Highest Common Factor)**, **remainders** (what's left over after division), **divisibility** (if one number can be divided by another without anything left over), **cyclicity** (patterns of repeating digits), and **prime numbers** (numbers only divisible by 1 and themselves). Our goal is to connect the theory with how to solve real problems.

---

## 🧮 Practice Questions and Detailed Solutions

### **Question 1:**  
When a number is successively divided by 35, 45, and 55, we get 18, 28, and 38 as remainders respectively.  
What is the smallest such number?

**Explanation Breakdown:**

This type of problem is a classic. It looks tricky because it mentions "successively divided," but the key is to notice a pattern in the numbers and their remainders.

1.  **Spot the Pattern (Common Difference):**
    *   When divided by 35, the remainder is 18. What's the difference between the divisor and the remainder? `35 - 18 = 17`
    *   When divided by 45, the remainder is 28. What's the difference? `45 - 28 = 17`
    *   When divided by 55, the remainder is 38. What's the difference? `55 - 38 = 17`

    Aha! The difference is always `17`. This "common difference" or "common remainder deficit" is super important. It means if we *added* 17 to our mystery number, it would be perfectly divisible by 35, 45, and 55.

2.  **Find the Least Common Multiple (LCM):**
    *   Since adding 17 makes the number divisible by 35, 45, and 55, our number (plus 17) must be a multiple of all three. To find the *smallest* such number, we need the *Least Common Multiple* (LCM) of 35, 45, and 55.

    Let's find the LCM:
    *   Prime factorize each number:
        *   `35 = 5 × 7`
        *   `45 = 3 × 3 × 5 = 3² × 5`
        *   `55 = 5 × 11`

    *   To find the LCM, take the highest power of all unique prime factors:
        *   `LCM = 3² × 5 × 7 × 11`
        *   `LCM = 9 × 5 × 7 × 11`
        *   `LCM = 45 × 77`
        *   `LCM = 3465`

3.  **Calculate the Smallest Number:**
    *   We found that `(our number + 17)` is `3465` (the smallest multiple).
    *   So, `our number = LCM - 17`
    *   `our number = 3465 - 17 = 3448`

**Solution:**
- **Step 1: Find the common difference.**
  - `35 − 18 = 17`
  - `45 − 28 = 17`
  - `55 − 38 = 17`
  ⇒ The common difference (or "remainder deficit") is **17**. This means if we add 17 to our number, it will be perfectly divisible by 35, 45, and 55.

- **Step 2: Find the LCM of the divisors.**
  - `LCM(35, 45, 55)`
  - Prime factors: `35 = 5 × 7`, `45 = 3² × 5`, `55 = 5 × 11`
  - `LCM = 3² × 5 × 7 × 11 = 9 × 5 × 7 × 11 = 3465`

- **Step 3: Calculate the smallest number.**
  - The smallest number is `LCM - common difference`.
  - Smallest number = `3465 − 17 = 3448`

✅ **Answer:** The smallest such number is **3448**.
`

### **Question 2:**  
How many four-digit numbers are divisible by 7?

**Explanation Breakdown:**

We need to count all the numbers between 1000 (smallest 4-digit) and 9999 (largest 4-digit) that can be perfectly divided by 7. This is like counting items in a sequence where each item is 7 more than the last. This is an **Arithmetic Sequence**.

1.  **Find the First 4-Digit Number Divisible by 7:**
    *   The smallest 4-digit number is 1000.
    *   Divide 1000 by 7: `1000 ÷ 7 = 142 with a remainder of 6`.
    *   This means 1000 is not divisible by 7. To find the *next* number that is, we need to add `(7 - remainder)` to 1000.
    *   `1000 + (7 - 6) = 1000 + 1 = 1001`.
    *   So, `1001` is our first 4-digit number divisible by 7. This is `a₁`.

2.  **Find the Last 4-Digit Number Divisible by 7:**
    *   The largest 4-digit number is 9999.
    *   Divide 9999 by 7: `9999 ÷ 7 = 1428 with a remainder of 3`.
    *   This means 9999 is not divisible by 7. To find the *previous* number that is, we subtract the remainder from 9999.
    *   `9999 - 3 = 9996`.
    *   So, `9996` is our last 4-digit number divisible by 7. This is `aₙ`.

3.  **Use the Arithmetic Sequence Formula:**
    *   We have a sequence: 1001, 1008, 1015, ..., 9996.
    *   First term (`a₁`) = 1001
    *   Last term (`aₙ`) = 9996
    *   Common difference (`d`) = 7 (because each number is 7 more than the last)
    *   We want to find `n`, the number of terms.

    The formula for the nth term of an arithmetic sequence is: `aₙ = a₁ + (n - 1)d`

    *   Plug in the values: `9996 = 1001 + (n - 1)7`
    *   Subtract 1001 from both sides: `9996 - 1001 = (n - 1)7`
    *   `8995 = (n - 1)7`
    *   Divide by 7: `8995 ÷ 7 = n - 1`
    *   `1285 = n - 1`
    *   Add 1 to both sides: `n = 1285 + 1 = 1286`

**Solution:**
- **Step 1: Find the smallest 4-digit number divisible by 7.**
  - Smallest 4-digit number is 1000.
  - `1000 ÷ 7 = 142` with a remainder of `6`.
  - To make it divisible, `1000 + (7 - 6) = 1001`.
  - So, `a₁ = 1001`.

- **Step 2: Find the largest 4-digit number divisible by 7.**
  - Largest 4-digit number is 9999.
  - `9999 ÷ 7 = 1428` with a remainder of `3`.
  - To make it divisible, `9999 - 3 = 9996`.
  - So, `aₙ = 9996`.

- **Step 3: Use the arithmetic sequence formula to count.**
  - `aₙ = a₁ + (n - 1)d`
  - `9996 = 1001 + (n - 1)7`
  - `8995 = (n - 1)7`
  - `1285 = n - 1`
  - `n = 1286`

✅ **Answer:** There are **1286** four-digit numbers divisible by 7.
`

### **Question 3:**  
Find the maximum value of **B** in:

```
  1 2 B
+ B 4 C
+ C 6 7
---------
1 0 3 5
```

**Explanation Breakdown:**

This is an addition puzzle! We're adding three 3-digit numbers, and we need to find the largest possible value for the digit 'B'. We'll solve this column by column, starting from the rightmost (ones place) and moving left.

1.  **Analyze the Ones Column (rightmost):**
    *   We have `B + C + 7` in the ones column.
    *   The result in the answer's ones column is `5`.
    *   This means `B + C + 7` must end in a `5`.
    *   Possible sums: `5`, `15`, `25`, etc.
    *   If `B + C + 7 = 5`, then `B + C = -2`, which is impossible for digits.
    *   So, `B + C + 7 = 15`. This gives `B + C = 15 - 7 = 8`.
    *   This also means we **carry over 1** to the tens column.

2.  **Analyze the Tens Column (middle):**
    *   We have `2 + 4 + 6` plus the `1` we carried over from the ones column.
    *   So, `1 + 2 + 4 + 6 = 13`.
    *   The result in the answer's tens column is `3`. This matches `13` (where `3` is the digit and `1` is carried over).
    *   This means we **carry over 1** to the hundreds column.

3.  **Analyze the Hundreds Column (leftmost):**
    *   We have `1 + B + C` plus the `1` we carried over from the tens column.
    *   So, `1 + B + C + 1`.
    *   The result in the answer's hundreds column is `0`, but there's a `1` in the thousands place (making it 1035). This means the sum of the hundreds column must be `10` (or `20`, etc.).
    *   So, `1 + B + C + 1 = 10`
    *   `B + C + 2 = 10`
    *   `B + C = 8`.

4.  **Confirm and Maximize B:**
    *   Notice that our calculation from the ones column (`B + C = 8`) matches our calculation from the hundreds column (`B + C = 8`). This consistency is a good sign!
    *   We need to maximize `B` given that `B + C = 8`.
    *   Since `C` is a digit (0-9), to make `B` as large as possible, we need to make `C` as small as possible.
    *   The smallest possible digit for `C` is `0`.
    *   If `C = 0`, then `B + 0 = 8`, so `B = 8`.

    Let's quickly check if setting `B=8` and `C=0` works with the original sum:
    ```
      1 2 8
    + 8 4 0
    + 0 6 7
    ---------
    ```
    *   Ones: `8 + 0 + 7 = 15` (write 5, carry 1)
    *   Tens: `1 (carry) + 2 + 4 + 6 = 13` (write 3, carry 1)
    *   Hundreds: `1 (carry) + 1 + 8 + 0 = 10` (write 0, carry 1)
    *   Thousands: `1 (carry)`
    *   Result: `1035`. It works!

**Solution:**
- **Step 1: Look at the ones column (rightmost).**
  - `B + C + 7` must end in a `5`.
  - The smallest possible sum ending in `5` is `15`.
  - So, `B + C + 7 = 15`
  - This means `B + C = 8`. We carry over `1` to the tens column.

- **Step 2: Look at the tens column (middle).**
  - We have `2 + 4 + 6` plus the `1` carried over from the ones column.
  - `1 + 2 + 4 + 6 = 13`.
  - The result's tens digit is `3`, which matches. We carry over `1` to the hundreds column.

- **Step 3: Look at the hundreds column (leftmost).**
  - We have `1 + B + C` plus the `1` carried over from the tens column.
  - `1 + B + C + 1` must result in `10` (since the final answer is 1035).
  - So, `B + C + 2 = 10`
  - This means `B + C = 8`. (This confirms our finding from Step 1!)

- **Step 4: Maximize B.**
  - We know `B + C = 8`.
  - To make `B` as large as possible, `C` must be as small as possible.
  - The smallest digit `C` can be is `0`.
  - If `C = 0`, then `B + 0 = 8`, so `B = 8`.

✅ **Answer:** The maximum value of **B** is **8**.
`

### **Question 4:**  
Which are prime numbers?  
(i) 247 (ii) 397 (iii) 423  

**Explanation Breakdown:**

A **prime number** is a whole number greater than 1 that has only two divisors: 1 and itself. A **composite number** has more than two divisors.

To check if a number is prime, we try dividing it by small prime numbers (2, 3, 5, 7, 11, 13, 17, 19, etc.) up to the square root of the number. If it's not divisible by any of these, it's prime.

Let's check each number:

1.  **Check (i) 247:**
    *   Not divisible by 2 (it's odd).
    *   Sum of digits `2+4+7 = 13`, not divisible by 3 (so 247 isn't divisible by 3).
    *   Doesn't end in 0 or 5 (so not divisible by 5).
    *   Try 7: `247 ÷ 7 = 35` with remainder `2` (not divisible by 7).
    *   Try 11: `247 ÷ 11 = 22` with remainder `5` (not divisible by 11).
    *   Try 13: `247 ÷ 13`. Let's do long division or estimation. `13 × 10 = 130`, `13 × 20 = 260`. So it's between 10 and 20.
        *   `247 - 130 = 117`.
        *   `13 × 9 = 117`.
        *   So, `247 = 13 × 19`.
    *   Since 247 can be divided by 13 (and 19), it is **not prime**. It's a composite number.

2.  **Check (ii) 397:**
    *   To check up to what prime number we need to test, find the square root of 397.
        *   `20 × 20 = 400`. So, `√397` is just under 20.
        *   We need to test prime numbers less than 20: 2, 3, 5, 7, 11, 13, 17, 19.
    *   Not divisible by 2 (odd).
    *   Sum of digits `3+9+7 = 19`, not divisible by 3.
    *   Doesn't end in 0 or 5 (not divisible by 5).
    *   Try 7: `397 ÷ 7 = 56` with remainder `5` (not divisible by 7).
    *   Try 11: `397 ÷ 11 = 36` with remainder `1` (not divisible by 11).
    *   Try 13: `397 ÷ 13 = 30` with remainder `7` (not divisible by 13).
    *   Try 17: `397 ÷ 17 = 23` with remainder `6` (not divisible by 17).
    *   Try 19: `397 ÷ 19 = 20` with remainder `17` (not divisible by 19).
    *   Since it's not divisible by any prime numbers up to its square root, `397` is a **prime number**.

3.  **Check (iii) 423:**
    *   Not divisible by 2 (odd).
    *   Sum of digits `4+2+3 = 9`.
    *   Since the sum of digits (9) is divisible by 3, the number `423` itself is divisible by 3.
    *   `423 ÷ 3 = 141`.
    *   Since 423 can be divided by 3, it is **not prime**. It's a composite number.

**Solution:**
- **(i) 247:**
  - `247 ÷ 13 = 19`.
  - Since it has factors other than 1 and itself, 247 is a **Composite** number. ❌

- **(ii) 397:**
  - To check, we test divisibility by prime numbers up to `√397` (which is approximately 19.9). So we test 2, 3, 5, 7, 11, 13, 17, 19.
  - It is not divisible by 2 (odd).
  - Sum of digits `3+9+7=19` (not div by 3).
  - Does not end in 0 or 5 (not div by 5).
  - `397 ÷ 7 = 56 R 5` (not div by 7).
  - `397 ÷ 11 = 36 R 1` (not div by 11).
  - `397 ÷ 13 = 30 R 7` (not div by 13).
  - `397 ÷ 17 = 23 R 6` (not div by 17).
  - `397 ÷ 19 = 20 R 17` (not div by 19).
  - Since it's not divisible by any of these primes, 397 is a **Prime** number. ✅

- **(iii) 423:**
  - Sum of digits `4+2+3 = 9`.
  - Since the sum of its digits (9) is divisible by 3, 423 is divisible by 3. (`423 ÷ 3 = 141`).
  - So, 423 is a **Composite** number. ❌

✅ **Answer:** Only **397** is a prime number.
`

### **Question 5:**  
Find the unit’s digit of (17)¹⁵³ × (31)⁶².

**Explanation Breakdown:**

To find the unit's digit of a product, we only need to look at the unit's digits of the numbers being multiplied. For powers, we look for "cyclicity" – how the unit digits repeat in a pattern.

1.  **Unit's Digit of (17)¹⁵³:**
    *   The unit's digit of 17 is `7`.
    *   Let's look at the pattern of unit's digits for powers of 7:
        *   `7¹ = 7`
        *   `7² = 49` (unit digit is `9`)
        *   `7³ = 343` (unit digit is `3`)
        *   `7⁴ = 2401` (unit digit is `1`)
        *   `7⁵ = 16807` (unit digit is `7`)
    *   The pattern of unit digits for 7 is `[7, 9, 3, 1]`. This pattern repeats every `4` powers (it has a **cyclicity of 4**).

    *   To find the unit's digit of `7¹⁵³`, we divide the exponent (153) by the cyclicity (4) and look at the remainder.
        *   `153 ÷ 4 = 38` with a remainder of `1`.
    *   A remainder of `1` means the unit digit is the 1st digit in the cycle: `7`.

2.  **Unit's Digit of (31)⁶²:**
    *   The unit's digit of 31 is `1`.
    *   Let's look at the pattern of unit's digits for powers of 1:
        *   `1¹ = 1`
        *   `1² = 1`
        *   `1³ = 1`
    *   Any power of a number ending in `1` will always have a unit's digit of `1`. (Cyclicity of 1, remainder doesn't matter).

3.  **Multiply the Unit's Digits:**
    *   The unit's digit of `(17)¹⁵³` is `7`.
    *   The unit's digit of `(31)⁶²` is `1`.
    *   Multiply these unit's digits: `7 × 1 = 7`.

**Solution:**
- **Step 1: Find the unit's digit of (17)¹⁵³.**
  - The unit digit of the base is `7`.
  - The cyclicity of the unit digits of powers of `7` is `4` (the pattern is `[7, 9, 3, 1]`).
  - Divide the exponent `153` by `4`: `153 ÷ 4 = 38` with a **remainder of 1**.
  - The 1st digit in the cycle is `7`. So, the unit's digit of `(17)¹⁵³` is `7`.

- **Step 2: Find the unit's digit of (31)⁶².**
  - The unit digit of the base is `1`.
  - Any positive integer power of a number ending in `1` will always have `1` as its unit's digit.
  - So, the unit's digit of `(31)⁶²` is `1`.

- **Step 3: Multiply the unit's digits.**
  - Multiply the unit's digits found in Step 1 and Step 2: `7 × 1 = 7`.

✅ **Answer:** The unit's digit is **7**.
`

### **Question 6:**  
Find the unit’s digit of (17)¹⁵³ + (31)⁶².

**Explanation Breakdown:**

This is very similar to Question 5, but instead of multiplying, we're adding the numbers.

1.  **Unit's Digit of (17)¹⁵³:**
    *   As calculated in Question 5, the unit's digit of `(17)¹⁵³` is `7`.

2.  **Unit's Digit of (31)⁶²:**
    *   As calculated in Question 5, the unit's digit of `(31)⁶²` is `1`.

3.  **Add the Unit's Digits:**
    *   Add the unit's digits found: `7 + 1 = 8`.

**Solution:**
- **Step 1: Find the unit's digit of (17)¹⁵³.**
  - From Question 5, the unit's digit of `(17)¹⁵³` is `7`.

- **Step 2: Find the unit's digit of (31)⁶².**
  - From Question 5, the unit's digit of `(31)⁶²` is `1`.

- **Step 3: Add the unit's digits.**
  - Sum the unit's digits: `7 + 1 = 8`.

✅ **Answer:** The unit's digit is **8**.
`

### **Question 7:**  
Find total number of prime factors in:  
(14)¹¹ × (7)² × (11)³  

**Explanation Breakdown:**

A **prime factor** is a prime number that divides a given number exactly. When a number is expressed in its prime factorization (like `2³ × 3² × 5`), the "total number of prime factors" is the sum of the exponents of all the prime factors.

1.  **Break Down Bases into Prime Factors:**
    *   `(14)¹¹`: The base is `14`. Prime factors of `14` are `2` and `7`.
        *   So, `(14)¹¹ = (2 × 7)¹¹ = 2¹¹ × 7¹¹`.
    *   `(7)²`: The base is `7`, which is already a prime number.
        *   So, `(7)²` stays as `7²`.
    *   `(11)³`: The base is `11`, which is already a prime number.
        *   So, `(11)³` stays as `11³`.

2.  **Combine All Prime Factors:**
    *   Now, put all these prime factors together:
        *   `2¹¹ × 7¹¹ × 7² × 11³`
    *   Combine the powers of the same prime factor (remember, when multiplying powers with the same base, you add the exponents: `aᵐ × aⁿ = aᵐ⁺ⁿ`):
        *   `2¹¹ × (7¹¹ × 7²) × 11³`
        *   `2¹¹ × 7⁽¹¹⁺²⁾ × 11³`
        *   `2¹¹ × 7¹³ × 11³`

3.  **Sum the Exponents:**
    *   The prime factors are 2, 7, and 11.
    *   Their exponents are 11, 13, and 3.
    *   Add the exponents: `11 + 13 + 3 = 27`.

**Solution:**
- **Step 1: Express all bases as a product of their prime factors.**
  - `(14)¹¹ = (2 × 7)¹¹ = 2¹¹ × 7¹¹`
  - `(7)²` is already in prime factor form.
  - `(11)³` is already in prime factor form.

- **Step 2: Combine all prime factors into a single expression.**
  - `(2¹¹ × 7¹¹) × 7² × 11³`
  - When multiplying powers with the same base, add their exponents:
  - `2¹¹ × 7⁽¹¹⁺²⁾ × 11³`
  - `2¹¹ × 7¹³ × 11³`

- **Step 3: Sum the exponents of all the prime factors.**
  - Exponents are 11, 13, and 3.
  - Total number of prime factors = `11 + 13 + 3 = 27`.

✅ **Answer:** There are **27** total prime factors.
`

### **Question 8:**  
Which digits replace * and # so that 12386*# is divisible by 8 and 5?

**Explanation Breakdown:**

We need to find the digits * and # in the 7-digit number `12386*#` so that it's divisible by both 8 and 5. Let's use the divisibility rules.

1.  **Divisibility Rule for 5:**
    *   A number is divisible by 5 if its last digit is `0` or `5`.
    *   So, `#` must be `0` or `5`.

2.  **Divisibility Rule for 8:**
    *   A number is divisible by 8 if the number formed by its last three digits is divisible by 8.
    *   In our number `12386*#`, the last three digits form `6*#`.
    *   Since the number must also be divisible by 5, `#` must be `0` (because if `#` were `5`, the number `6*5` would be odd and thus not divisible by 8).
    *   So, we now know `# = 0`. Our number is `12386*0`.
    *   Now we need `6*0` to be divisible by 8. Let's test values for `*` (which can be any digit from 0 to 9).

    *   If `* = 0`: Is `600` divisible by 8? `600 ÷ 8 = 75`. Yes! So `* = 0` works.
    *   If `* = 1`: Is `610` divisible by 8? `610 ÷ 8 = 76` with remainder `2`. No.
    *   If `* = 2`: Is `620` divisible by 8? `620 ÷ 8 = 77` with remainder `4`. No.
    *   If `* = 3`: Is `630` divisible by 8? `630 ÷ 8 = 78` with remainder `6`. No.
    *   If `* = 4`: Is `640` divisible by 8? `640 ÷ 8 = 80`. Yes! So `* = 4` works.
    *   If `* = 5`: Is `650` divisible by 8? `650 ÷ 8 = 81` with remainder `2`. No.
    *   If `* = 6`: Is `660` divisible by 8? `660 ÷ 8 = 82` with remainder `4`. No.
    *   If `* = 7`: Is `670` divisible by 8? `670 ÷ 8 = 83` with remainder `6`. No.
    *   If `* = 8`: Is `680` divisible by 8? `680 ÷ 8 = 85`. Yes! So `* = 8` works.
    *   If `* = 9`: Is `690` divisible by 8? `690 ÷ 8 = 86` with remainder `2`. No.

    So, `*` can be `0`, `4`, or `8`.

**Solution:**
- **Step 1: Apply the divisibility rule for 5.**
  - A number is divisible by 5 if its unit digit (`#`) is `0` or `5`.

- **Step 2: Apply the divisibility rule for 8.**
  - A number is divisible by 8 if the number formed by its last three digits (`6*#`) is divisible by 8.
  - For `6*#` to be divisible by 8, it must be an even number. This means `#` cannot be `5`.
  - Therefore, `#` must be `0`.
  - Now we need the number `6*0` to be divisible by 8.
  - Test values for `*` (from 0 to 9):
    - If `* = 0`: `600 ÷ 8 = 75`. (Works!)
    - If `* = 4`: `640 ÷ 8 = 80`. (Works!)
    - If `* = 8`: `680 ÷ 8 = 85`. (Works!)
  - Other values of `*` will not make `6*0` divisible by 8.

✅ **Answer:** `*` can be **0, 4, or 8** and `#` must be **0**.
`

### **Question 9:**  
What least number must be **subtracted** from 9999 to make it divisible by 19?

**Explanation Breakdown:**

When you divide one number by another, sometimes there's a remainder. If you want the original number to be perfectly divisible, you just need to get rid of that "extra" bit, which is the remainder.

1.  **Divide 9999 by 19:**
    *   Let's perform the division: `9999 ÷ 19`.
    *   `19 × 5 = 95`. So `99 ÷ 19 = 5` with remainder `4`.
*   Bring down the next `9`, making it `49`.
*   `19 × 2 = 38`. So `49 ÷ 19 = 2` with remainder `11`.
*   Bring down the last `9`, making it `119`.
*   `19 × 6 = 114`. So `119 ÷ 19 = 6` with remainder `5`.

    So, `9999 = 19 × 526 + 5`.

2.  **Determine the Number to Subtract:**
    *   The remainder is `5`. This means 9999 is `5` units *more* than a perfect multiple of 19.
    *   To make it perfectly divisible by 19, we just need to subtract this extra `5`.
    *   `9999 - 5 = 9994`. And `9994 ÷ 19 = 526` (perfectly divisible).

**Solution:**
- **Step 1: Divide 9999 by 19.**
  - `9999 ÷ 19 = 526` with a **remainder of 5**.
  - This can be written as: `9999 = 19 × 526 + 5`.

- **Step 2: Understand the remainder.**
  - The remainder `5` means that 9999 is `5` units larger than the nearest multiple of 19 (which is 9994).

- **Step 3: Find the least number to subtract.**
  - To make 9999 perfectly divisible by 19, we need to remove this extra `5`.
  - Least number to subtract = **5**.

✅ **Answer:** The least number that must be subtracted is **5**.
`

### **Question 10:**  
What least number must be **added** to 9999 to make it divisible by 19?

**Explanation Breakdown:**

This is similar to Question 9, but this time we want to *add* the smallest amount to reach the *next* multiple of 19.

1.  **Divide 9999 by 19:**
    *   From Question 9, we already know that `9999 ÷ 19` leaves a **remainder of 5**.
    *   This means `9999 = 19 × 526 + 5`.
    *   The multiple of 19 just *before* 9999 is `19 × 526 = 9994`.

2.  **Determine the Number to Add:**
    *   We are currently at 9999. The *next* multiple of 19 after 9994 would be `19 × 527`.
    *   `19 × 527 = 9994 + 19 = 10013`.
    *   We want to go from 9999 to 10013.
    *   The amount to add is `10013 - 9999 = 14`.

    *   **Easier way:** If the remainder is `5`, it means we've covered `5` units into the current "block" of 19. To get to the *next* full block of 19, we need to add the difference between the divisor and the remainder.
    *   Amount to add = `Divisor - Remainder`
    *   Amount to add = `19 - 5 = 14`.

**Solution:**
- **Step 1: Divide 9999 by 19.**
  - As established in Question 9, `9999 ÷ 19 = 526` with a **remainder of 5**.
  - This means 9999 is 5 units beyond the previous multiple of 19 (which is 9994).

- **Step 2: Find the least number to add.**
  - To reach the *next* multiple of 19, we need to add the difference between the divisor (19) and the current remainder (5).
  - Least number to add = `19 - Remainder`
  - Least number to add = `19 - 5 = 14`.
  - (Checking: `9999 + 14 = 10013`, and `10013 ÷ 19 = 527` exactly).

✅ **Answer:** The least number that must be added is **14**.
`

### **Question 11:**  
A number when divided by 340 leaves remainder 47.  
What is the remainder when divided by 17?

**Explanation Breakdown:**

This problem uses the idea that if a number `N` is divisible by `A`, and `A` is also divisible by `B`, then `N` must also be divisible by `B`. Or, if we're dealing with remainders, we can "re-divide" the remainder.

1.  **Understand the First Statement:**
    *   "A number when divided by 340 leaves remainder 47."
    *   We can write this mathematically as: `N = 340 × (some_quotient) + 47`.
    *   Let's call `some_quotient` as `a`. So, `N = 340a + 47`.

2.  **Check Divisibility of the Divisor (340) by the New Divisor (17):**
    *   Is 340 divisible by 17?
    *   `340 ÷ 17 = 20`. Yes, it is perfectly divisible! This is key.

3.  **Re-evaluate the Number in terms of 17:**
    *   Since `N = 340a + 47`, and `340` is a multiple of `17` (`340 = 17 × 20`), we can rewrite the equation:
    *   `N = (17 × 20)a + 47`
    *   `N = 17 × (20a) + 47`
    *   The `17 × (20a)` part is clearly divisible by 17 (it's a multiple of 17).
    *   So, the remainder when `N` is divided by 17 will come entirely from the remainder `47`.

4.  **Find the Remainder of the Remainder:**
    *   Now, we just need to find the remainder when `47` is divided by `17`.
    *   `47 ÷ 17`.
    *   `17 × 1 = 17`
    *   `17 × 2 = 34`
    *   `17 × 3 = 51` (too big)
    *   So, `47 ÷ 17 = 2` with a remainder of `47 - 34 = 13`.

    *   Therefore, the remainder when `N` is divided by 17 is `13`.

**Solution:**
- **Step 1: Write the given information in a formula.**
  - Let the number be `N`.
  - `N = (Divisor_1 × Quotient_1) + Remainder_1`
  - `N = 340a + 47` (where 'a' is some whole number quotient).

- **Step 2: Check if the first divisor (340) is divisible by the new divisor (17).**
  - `340 ÷ 17 = 20`. Yes, it is perfectly divisible!

- **Step 3: Re-express the number using the new divisor.**
  - Since `340` is a multiple of `17`, the term `340a` is definitely divisible by `17`.
  - So, `340a = 17 × (20a)`. This means `340a` leaves a remainder of `0` when divided by `17`.
  - The only part that will contribute to a remainder when `N` is divided by `17` is the original remainder, `47`.

- **Step 4: Find the remainder when the original remainder (47) is divided by the new divisor (17).**
  - `47 ÷ 17 = 2` with a remainder of `13` (`47 - (17 × 2) = 47 - 34 = 13`).

✅ **Answer:** The remainder when divided by 17 is **13**.
`

### **Question 12:**  
Find remainder when 3²¹ is divided by 5.

**Explanation Breakdown:**

This question asks for the remainder, not just the unit digit. However, for division by 5, the remainder is the same as the unit digit (unless the unit digit is 0 or 5, in which case the remainder is 0). We'll use the concept of cyclicity (similar to unit digits) but for remainders when divided by 5. This is called **modular arithmetic**.

1.  **Find the Cyclicity of Remainders when Powers of 3 are Divided by 5:**
    *   `3¹ = 3`. Remainder when `3 ÷ 5` is `3`.
    *   `3² = 9`. Remainder when `9 ÷ 5` is `4`.
    *   `3³ = 27`. Remainder when `27 ÷ 5` is `2`.
    *   `3⁴ = 81`. Remainder when `81 ÷ 5` is `1`.
    *   `3⁵ = 243`. Remainder when `243 ÷ 5` is `3`.

    *   The pattern of remainders is `[3, 4, 2, 1]`. This pattern repeats every `4` powers (it has a **cyclicity of 4** for modulo 5).

2.  **Use the Exponent and Cyclicity:**
    *   We need to find the remainder of `3²¹ ÷ 5`.
    *   Divide the exponent `21` by the cyclicity `4`.
    *   `21 ÷ 4 = 5` with a **remainder of 1**.

3.  **Determine the Remainder:**
    *   A remainder of `1` from the exponent division means we take the 1st remainder in our cycle.
    *   The 1st remainder in the cycle `[3, 4, 2, 1]` is `3`.

**Solution:**
- **Step 1: Determine the cyclic pattern of remainders when powers of 3 are divided by 5.**
  - `3¹ ÷ 5 → Remainder = 3`
  - `3² ÷ 5 → 9 ÷ 5 → Remainder = 4`
  - `3³ ÷ 5 → 27 ÷ 5 → Remainder = 2`
  - `3⁴ ÷ 5 → 81 ÷ 5 → Remainder = 1`
  - `3⁵ ÷ 5 → 243 ÷ 5 → Remainder = 3` (The pattern `[3, 4, 2, 1]` repeats.)
  - The **cyclicity is 4**.

- **Step 2: Divide the exponent by the cyclicity.**
  - The exponent is `21`.
  - `21 ÷ 4 = 5` with a **remainder of 1**.

- **Step 3: Use the remainder to find the final remainder.**
  - A remainder of `1` means the remainder will be the 1st term in the cycle.
  - The 1st term in the cycle `[3, 4, 2, 1]` is `3`.

✅ **Answer:** The remainder when 3²¹ is divided by 5 is **3**.
`

## 💡 Key Takeaways
- **Patterns matter:** Understanding how unit digits and remainders repeat (cyclicity) is a powerful shortcut for large powers.
- **LCM/HCF logic** helps solve modular remainder problems efficiently, especially when dealing with multiple divisors.
- **Divisibility Rules** are your best friends! Memorizing rules for 2, 3, 4, 5, 8, 9, 10, 11 will save a lot of time.
- **Practice consistency** turns complex divisibility into intuition. The more you practice, the easier it becomes to spot these patterns and apply the rules.

---

## 🧭 Next Step
Now that you've mastered these number theory basics with detailed explanations, you're ready to dive deeper!
➡️ [Next](https://github.com/Dev0psKing/aptitude-prep-journey/blob/master/Quantitative%20Aptitude/Numbers%20Questions%20and%20Solutions/Questions%20and%20Answers%20Part%202.md)

---

**Author:** [Uwabor Collins](https://github.com/Dev0psKing)  
**Repository:** [Aptitude Prep Journey](https://github.com/Dev0psKing/aptitude-prep-journey)