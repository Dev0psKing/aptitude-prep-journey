
---

# 🔢 Advanced Number Theory & Divisibility (Expanded Explanations)

> "Numbers have life; they're not just symbols on paper." - **Shakuntala Devi**

Welcome to the advanced section where we tackle complex divisibility rules, prime factorization, and number theory concepts. Each problem is broken down into simple, logical steps that anyone can follow.

---

## 🧮 Divisibility by Composite Numbers

When checking for divisibility by a composite number (a number that is not prime, like 24), we can often simplify the problem by checking for divisibility by its co-prime factors.

### **Question 1: Divisibility by 24**

**Problem:** Is 52563744 divisible by 24?

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

Instead of performing a long division by 24, we can use a clever trick. The key is to break down 24 into factors that have no common divisors other than 1. These are called **co-prime** factors.

1.  **Factorize the Divisor (24):**
    *   `24 = 4 × 6` (Not co-prime, they share a factor of 2)
    *   `24 = 2 × 12` (Not co-prime, they share a factor of 2)
    *   `24 = 3 × 8` (Co-prime! Their only common factor is 1)

    *   **The Golden Rule:** If a number is divisible by two co-prime numbers `a` and `b`, then it must be divisible by their product `a × b`.
    *   So, to check if a number is divisible by 24, we just need to check if it's divisible by both 3 and 8.

2.  **Check for Divisibility by 3:**
    *   **Rule for 3:** A number is divisible by 3 if the sum of its digits is divisible by 3.
    *   Sum of digits of `52563744`: `5 + 2 + 5 + 6 + 3 + 7 + 4 + 4 = 36`.
    *   Is `36` divisible by 3? Yes, `36 ÷ 3 = 12`.
    *   ✅ So, `52563744` is divisible by 3.

3.  **Check for Divisibility by 8:**
    *   **Rule for 8:** A number is divisible by 8 if the number formed by its last three digits is divisible by 8.
    *   The last three digits of `52563744` are `744`.
    *   Is `744` divisible by 8? Let's check: `744 ÷ 8 = 93`. Yes, it is.
    *   ✅ So, `52563744` is divisible by 8.

4.  **Final Conclusion:**
    *   Since the number `52563744` is divisible by both 3 and 8 (which are co-prime), it must be divisible by their product, `3 × 8 = 24`.

---

#### ✅ **Final Answer:** **Yes, 52563744 is divisible by 24**
`

### **Question 2: Find Missing Digits**

**Problem:** Find values of M and N if M39048458N is divisible by both 8 and 11, where M and N are single-digit integers.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

We have a large number with two missing digits, M and N. We're given two conditions (divisible by 8 and 11) that will allow us to form equations and solve for M and N. It's usually best to start with the rule that involves fewer unknown digits.

1.  **Use the Divisibility by 8 Rule to Find N:**
    *   The rule for 8 only depends on the last three digits. This is perfect because it only involves one of our unknown digits, N.
    *   **Rule for 8:** The number formed by the last three digits must be divisible by 8.
    *   Last three digits: `58N`.
    *   We need to find a single digit `N` (from 0 to 9) that makes `58N` divisible by 8. Let's test values or use division:
        *   Think about multiples of 8 near 580. We know `8 × 70 = 560` and `8 × 75 = 600`. The number must be between these.
        *   `8 × 71 = 568`
        *   `8 × 72 = 576`
        *   `8 × 73 = 584`  <-- This ends in a 4 and starts with 58! This is our number.
        *   `8 × 74 = 592`
    *   The only multiple of 8 in the 580s is `584`.
    *   Therefore, `N` must be `4`.

2.  **Use the Divisibility by 11 Rule to Find M (now that we know N):**
    *   Our number is now: `M390484584`.
    *   **Rule for 11:** The difference between the sum of digits in odd positions and the sum of digits in even positions must be `0` or a multiple of `11`. (Let's count positions from right to left).

    *   Number: `M  3  9  0  4  8  4  5  8  4`
    *   Position: `10 9  8  7  6  5  4  3  2  1`
        (Or from left: `1 2 3 4 5 6 7 8 9 10`) - the result is the same. Let's use left-to-right for simplicity here.

    *   **Sum of odd-position digits (1st, 3rd, 5th, 7th, 9th):**
        `M + 9 + 4 + 4 + 8 = M + 25`

    *   **Sum of even-position digits (2nd, 4th, 6th, 8th, 10th):**
        `3 + 0 + 8 + 5 + 4 = 20`

    *   **Calculate the difference:**
        `(Sum of odd) - (Sum of even) = (M + 25) - 20 = M + 5`

    *   **Set the difference to a multiple of 11:**
        We need `M + 5` to be `0` or `11` or `22`, etc.
        *   `M` is a single-digit integer. M must also be positive and non-zero since it's the first digit of the number. So M is between 1 and 9.
        *   If `M + 5 = 0`, then `M = -5` (Impossible).
        *   If `M + 5 = 11`, then `M = 11 - 5 = 6` (Possible! `6` is a single digit).
        *   If `M + 5 = 22`, then `M = 17` (Impossible, not a single digit).

    *   The only valid solution is `M = 6`.

---

#### ✅ **Final Answer:** **M = 6, N = 4**
`

### **Question 3: Smallest Number with Digits 1 and 0**

**Problem:** Find the number of digits in the smallest number made up of digits 1 and 0 only, divisible by 225.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

We need to build the *smallest possible* number that meets three criteria:
1.  It uses only the digits 1 and 0.
2.  It is divisible by 225.
3.  We need to find its total number of digits.

1.  **Factorize the Divisor (225):**
    *   `225 = 25 × 9`.
    *   `25` and `9` are co-prime, so we can check for divisibility by 9 and 25 separately.

2.  **Apply the Divisibility Rules:**
    *   **Condition for Divisibility by 25:** The number must end in `00`, `25`, `50`, or `75`. Since we can only use digits `1` and `0`, the number must end in `00`.
    *   **Condition for Divisibility by 9:** The sum of the digits of the number must be divisible by 9.

3.  **Construct the Smallest Number:**
    *   To make the number as *small* as possible, it should have the fewest digits possible.
    *   We know the number must end in `00`.
    *   The other digits must be `1`s and `0`s. The sum of the digits comes only from the `1`s.
    *   For the sum of digits to be divisible by 9, the number of `1`s must be a multiple of 9 (e.g., 9 ones, 18 ones, etc.).
    *   To get the *smallest* number, we should use the *minimum* number of `1`s, which is **nine `1`s**.
    *   To make the number small, we should place the `1`s at the beginning (highest place value) and the `0`s at the end.
    *   So, the smallest number will be nine `1`s followed by two `0`s: `111,111,111,00`.

4.  **Count the Digits:**
    *   The number has nine `1`s and two `0`s.
    *   Total number of digits = `9 + 2 = 11`.

5.  **Final Verification:**
    *   The number `11111111100` ends in `00`, so it's divisible by 25.
    *   The sum of its digits is `1×9 + 0×2 = 9`, which is divisible by 9.
    *   Since it's divisible by both 9 and 25, it's divisible by 225. It's also the smallest such number because it uses the fewest possible digits arranged in the smallest possible configuration.

---

#### ✅ **Final Answer:** **11 digits**
`

### **Question 4: Find Missing Digits for Divisibility by 99**

**Problem:** If 3422213pq is divisible by 99, find the missing digits p and q.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

This is similar to Question 2, but this time we have two missing digits at the end. We'll use the co-prime factors of 99 to create two equations with two variables (`p` and `q`) and solve them simultaneously.

1.  **Factorize the Divisor (99):**
    *   `99 = 9 × 11`.
    *   `9` and `11` are co-prime.

2.  **Create Equation 1 (Using Divisibility by 9):**
    *   **Rule for 9:** The sum of digits must be divisible by 9.
    *   Sum = `3 + 4 + 2 + 2 + 2 + 1 + 3 + p + q`
    *   Sum = `17 + p + q`.
    *   This sum must be a multiple of 9. Since `p` and `q` are single digits (0-9), their maximum sum is `9+9=18`. So `17 + p + q` can have a maximum value of `17+18 = 35`.
    *   Multiples of 9 near 17 are 18 and 27.
        *   **Case 1:** `17 + p + q = 18`  =>  `p + q = 1`
        *   **Case 2:** `17 + p + q = 27`  =>  `p + q = 10`

3.  **Create Equation 2 (Using Divisibility by 11):**
    *   **Rule for 11:** (Sum of odd-position digits) - (Sum of even-position digits) must be `0` or a multiple of `11`. (Counting from the left for simplicity).
    *   Number: `3  4  2  2  2  1  3  p  q`
    *   Position: `1  2  3  4  5  6  7  8  9`
    *   **Sum of odd-position digits (1, 3, 5, 7, 9):**
        `3 + 2 + 2 + 3 + q = 10 + q`
    *   **Sum of even-position digits (2, 4, 6, 8):**
        `4 + 2 + 1 + p = 7 + p`
    *   **Difference:** `(10 + q) - (7 + p) = 3 + q - p`.
    *   This difference must be a multiple of 11. Since `p` and `q` are single digits, the difference `3+q-p` will be a small number. Let's check the most likely possibilities: `0`, `11`, or `-11`.
        *   **Case A:** `3 + q - p = 0`   =>  `p - q = 3`
        *   **Case B:** `3 + q - p = 11`  =>  `q - p = 8`
        *   **Case C:** `3 + q - p = -11` =>  `p - q = 14` (Impossible, as max difference between two digits is 9).

4.  **Solve the System of Equations:**
    *   We need to find a pair of single-digit numbers `p` and `q` that satisfy one equation from Step 2 and one from Step 3. Let's test the four possible combinations.

    *   **Combination 1:** `p + q = 1` and `p - q = 3`.
        *   Add the two equations: `(p+q) + (p-q) = 1+3` => `2p = 4` => `p = 2`.
        *   If `p=2`, then `2+q=1` => `q = -1`. (Impossible, q must be a digit from 0-9).

    *   **Combination 2:** `p + q = 1` and `q - p = 8`.
        *   From `q-p=8`, `q = p+8`. Substitute into first equation: `p + (p+8) = 1` => `2p = -7` => `p = -3.5`. (Impossible).

    *   **Combination 3:** `p + q = 10` and `p - q = 3`.
        *   Add the two equations: `2p = 13` => `p = 6.5`. (Impossible, p must be an integer).

    *   **Combination 4:** `p + q = 10` and `q - p = 8`.
        *   From `q-p=8`, `q = p+8`. Substitute into first equation: `p + (p+8) = 10` => `2p = 2` => `p = 1`.
        *   If `p=1`, then `1+q=10` => `q = 9`.
        *   This works! `p=1` and `q=9` are both single digits.

---

#### ✅ **Final Answer:** **p = 1, q = 9**
`

## 🎯 Special Number Properties

### **Question 5: Find All Possible Values**

**Problem:** x is a positive integer such that x² + 12 is exactly divisible by x. Find all possible values of x.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

The phrase "is exactly divisible by" means the result of the division is a whole number (an integer) with no remainder. We can simplify the given fraction to understand the condition.

1.  **Rewrite the Expression as a Fraction:**
    *   "x² + 12 is exactly divisible by x" can be written as: `(x² + 12) / x` must be an integer.

2.  **Split the Fraction:**
    *   We can split the numerator and divide each part by the denominator `x`:
        ```
        x² + 12      x²      12
        --------  =  ---  +  ---
           x          x       x
        ```

3.  **Simplify Each Term:**
    *   `x² / x = x`
    *   `12 / x` remains as it is.
    *   So, the expression simplifies to `x + (12 / x)`.

4.  **Analyze the Condition for the Simplified Expression:**
    *   We are given that `x` is a positive integer.
    *   For the entire expression `x + (12 / x)` to be an integer, the part `12 / x` must also be an integer.
    *   If `12 / x` is an integer, it means that `x` must be a divisor (or factor) of 12.

5.  **Find All Positive Divisors of 12:**
    *   The numbers that divide 12 perfectly are: 1, 2, 3, 4, 6, and 12.

6.  **Conclusion:**
    *   All these divisors are possible values for `x` because for each of them, `12 / x` will be a whole number, making the entire expression an integer.

---

#### ✅ **Final Answer:** **1, 2, 3, 4, 6, 12**
`

## 🔢 Number Adjustment Problems

These problems involve finding the smallest number to add or subtract to meet a divisibility condition. The key is to use the remainder from a division.

### **Question 6: Smallest Number to Add**

**Problem:** Find the smallest number to be added to 1000 so that 45 divides the sum exactly.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

We want to find the next multiple of 45 after 1000.

1.  **Divide 1000 by 45 and Find the Remainder:**
    *   `1000 ÷ 45`. Let's do the division:
        *   `100 ÷ 45 = 2` (since `45 × 2 = 90`), with a remainder of `100 - 90 = 10`.
        *   Bring down the next `0`, making it `100` again.
        *   `100 ÷ 45 = 2`, with a remainder of `10`.
    *   So, `1000 = 45 × 22 + 10`.
    *   This means 1000 is `10` units *past* the previous multiple of 45 (which was 990).

2.  **Calculate the Number to Add:**
    *   We have a remainder of `10`. To reach the *next* multiple of 45, we need to add the difference between the divisor (45) and the remainder (10).
    *   Number to add = `Divisor - Remainder`
    *   Number to add = `45 - 10 = 35`.

3.  **Verification:**
    *   `1000 + 35 = 1035`.
    *   `1035 ÷ 45 = 23`. It divides perfectly.

---

#### ✅ **Final Answer:** **35**
`

### **Question 7: Number to Subtract**

**Problem:** What least number must be subtracted from 2000 to get a number exactly divisible by 17?

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

This is the opposite of the previous problem. We want to find the multiple of 17 that comes just *before* 2000. The amount we need to subtract is simply the "extra" bit, which is the remainder.

1.  **Divide 2000 by 17 and Find the Remainder:**
    *   `2000 ÷ 17`.
        *   `20 ÷ 17 = 1`, remainder `3`.
        *   Bring down `0`, making it `30`. `30 ÷ 17 = 1`, remainder `13`.
        *   Bring down `0`, making it `130`. `130 ÷ 17`. Let's estimate: `17 × 7 = 119`. `130 - 119 = 11`.
    *   So, `2000 = 17 × 117 + 11`.
    *   The remainder is `11`.

2.  **Determine the Number to Subtract:**
    *   The remainder `11` is the amount by which 2000 exceeds a perfect multiple of 17.
    *   To make it perfectly divisible, we must subtract this remainder.
    *   Number to subtract = `Remainder` = `11`.

3.  **Verification:**
    *   `2000 - 11 = 1989`.
    *   `1989 ÷ 17 = 117`. It divides perfectly.

---

#### ✅ **Final Answer:** **11**
`

### **Question 8: Nearest Divisible Number**

**Problem:** Find the number nearest to 3105 that is exactly divisible by 21.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

We need to find the two multiples of 21 that are closest to 3105 (one just before, one just after) and then see which one is nearer.

1.  **Divide 3105 by 21 and Find the Remainder:**
    *   `3105 ÷ 21`.
        *   `31 ÷ 21 = 1`, remainder `10`.
        *   Bring down `0`, making it `100`. `100 ÷ 21 = 4` (`21×4=84`), remainder `16`.
        *   Bring down `5`, making it `165`. `165 ÷ 21`. `21×7=147`. `165-147=18`.
    *   So, `3105 = 21 × 147 + 18`.
    *   The remainder is `18`.

2.  **Find the Two Nearest Multiples of 21:**
    *   **Multiple Before:** To find the multiple before 3105, we subtract the remainder:
        `3105 - 18 = 3087`.
    *   **Multiple After:** To find the multiple after 3105, we add the difference between the divisor and the remainder:
        `3105 + (21 - 18) = 3105 + 3 = 3108`.

3.  **Compare the Distances:**
    *   The distance between 3105 and 3087 is `18`.
    *   The distance between 3105 and 3108 is `3`.
    *   Since `3` is smaller than `18`, the number `3108` is closer.

---

#### ✅ **Final Answer:** **3108**
`

### **Question 9: Smallest 5-Digit Divisible Number**

**Problem:** Find the smallest five-digit number exactly divisible by 476.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

We need to find the first multiple of 476 that is greater than or equal to the smallest 5-digit number (10000).

1.  **Identify the Smallest 5-Digit Number:**
    *   The smallest 5-digit number is `10000`.

2.  **Divide 10000 by 476 and Find the Remainder:**
    *   `10000 ÷ 476`.
        *   `1000 ÷ 476 = 2` (`476×2=952`), remainder `48`.
        *   Bring down `0`, making it `480`. `480 ÷ 476 = 1`, remainder `4`.
    *   So, `10000 = 476 × 21 + 4`.
    *   The remainder is `4`.

3.  **Find the Next Multiple:**
    *   `10000` is not divisible. To get to the *next* multiple of 476, we must add the difference between the divisor and the remainder.
    *   Number to add = `476 - 4 = 472`.
    *   Required number = `10000 + 472 = 10472`.
    *   This is the smallest 5-digit number divisible by 476 because subtracting the remainder would give `9996`, which is only a 4-digit number.

---

#### ✅ **Final Answer:** **10472**
`

### **Question 10: Largest 5-Digit Divisible Number**

**Problem:** Find the greatest five-digit number exactly divisible by 47.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

We need to find the largest multiple of 47 that is less than or equal to the largest 5-digit number (99999).

1.  **Identify the Largest 5-Digit Number:**
    *   The largest 5-digit number is `99999`.

2.  **Divide 99999 by 47 and Find the Remainder:**
    *   `99999 ÷ 47`.
        *   `99 ÷ 47 = 2` (`47×2=94`), remainder `5`.
        *   Bring down `9`, making it `59`. `59 ÷ 47 = 1`, remainder `12`.
        *   Bring down `9`, making it `129`. `129 ÷ 47 = 2` (`47×2=94`), remainder `35`.
        *   Bring down `9`, making it `359`. `359 ÷ 47 = 7` (`47×7=329`), remainder `30`.
    *   So, `99999 = 47 × 2127 + 30`.
    *   The remainder is `30`.

3.  **Find the Previous Multiple:**
    *   `99999` is not divisible. To get to the *previous* multiple of 47, we must subtract the remainder.
    *   Required number = `99999 - 30 = 99969`.
    *   This is the largest 5-digit number divisible by 47 because adding to it would result in a 6-digit number.

---

#### ✅ **Final Answer:** **99969**
`

## 🔍 Special Multiplication Patterns

### **Question 11: Product of All Fives**

**Problem:** When a number is multiplied by 13, the product consists entirely of fives. Find the smallest such number.

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

This is a reverse problem. We are given the product's pattern and one of the factors. Let the unknown number be `N`.
The problem states: `N × 13 = 555...5`
To find `N`, we can rewrite this as: `N = (555...5) / 13`.

We need to find the smallest number made of all fives that is perfectly divisible by 13. We can do this by performing long division and adding another '5' at each step until the remainder becomes zero.

1.  **Set up the Long Division:**
    We will divide a stream of fives by 13.
    *   `5 ÷ 13` -> Doesn't work.
    *   `55 ÷ 13 = 4` with remainder `3`.
    *   Bring down next `5` -> `35`. `35 ÷ 13 = 2` with remainder `9`.
    *   Bring down next `5` -> `95`. `95 ÷ 13 = 7` with remainder `4`.
    *   Bring down next `5` -> `45`. `45 ÷ 13 = 3` with remainder `6`.
    *   Bring down next `5` -> `65`. `65 ÷ 13 = 5` with remainder `0`.
    *   We stopped! The remainder is `0`.

2.  **Identify the Dividend and Quotient:**
    *   The number made of fives that worked was `555,555`.
    *   The quotient (our answer `N`) is what we found during the division: `42735`.

3.  **Conclusion:**
    *   The smallest such number `N` is `42735`.
    *   Verification: `42735 × 13 = 555555`.

---

#### ✅ **Final Answer:** **42735**
`

### **Question 12: Product of All Twos**

**Problem:** When a number is multiplied by 18, the product consists entirely of 2's. What is the minimum number of 2's in the product?

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

Similar to the last question, we need to find the smallest number made of all `2`s that is divisible by `18`.

1.  **Set Up the Problem:**
    *   We need `222...2` to be divisible by `18`.
    *   Since `18 = 2 × 9`, the number must be divisible by both 2 and 9.

2.  **Check the Conditions:**
    *   **Divisibility by 2:** Any number ending in `2` is even, so `222...2` is always divisible by 2. This condition is always met.
    *   **Divisibility by 9:** The sum of the digits must be divisible by 9.
        *   The digits are all `2`s. Let `k` be the number of `2`s.
        *   Sum of digits = `2 + 2 + ... + 2` (`k` times) = `2k`.
        *   We need `2k` to be divisible by 9. Since 2 and 9 are co-prime, `k` must be divisible by 9.

3.  **Find the Minimum Value for k:**
    *   We need the *minimum* number of `2`s.
    *   So, we need the smallest positive integer `k` that is divisible by 9.
    *   That number is `k = 9`.

4.  **Conclusion:**
    *   The minimum number of `2`s required in the product is 9.
    *   The product would be `222,222,222`.

---

#### ✅ **Final Answer:** **9**
`

## 🔢 Unit Digit Problems

### **Question 13: Unit Digit in Product**

**Problem:** Find the unit's digit in 81 × 82 × 83 × ... × 89

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

To find the unit's digit of a large product, we only need to look at the unit's digits of the numbers being multiplied. There's a very important shortcut to look for.

1.  **List the Unit's Digits of the Numbers in the Product:**
    *   The numbers are 81, 82, 83, 84, 85, 86, 87, 88, 89.
    *   Their unit's digits are: `1, 2, 3, 4, 5, 6, 7, 8, 9`.

2.  **Look for the Magic Combination: 2 and 5:**
    *   The product of any even number (which has a factor of 2) and any number ending in 5 will always result in a number ending in 0.
    *   In our list of unit digits, we have a `2` (from 82) and a `5` (from 85).

3.  **Determine the Unit's Digit of the Product:**
    *   When we multiply all these numbers, somewhere in the process we will be multiplying a number ending in `2` by a number ending in `5`. For example, `82 × 85 = 6970`. This product ends in `0`.
    *   Once you have a number ending in `0` in a product, the final result will also end in `0` (because anything multiplied by 10, 20, 30, etc., will always have a zero at the end).

---

#### ✅ **Final Answer:** **0**
`

### **Question 14: Unit Digit with Powers**

**Problem:** Find the unit's digit in (2467)¹⁵³ × (341)⁷²

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

We only care about the unit's digit of each base number. We will find the unit's digit of each part separately and then multiply them.

1.  **Simplify the Problem:**
    *   The unit's digit of `(2467)¹⁵³` is the same as the unit's digit of `7¹⁵³`.
    *   The unit's digit of `(341)⁷²` is the same as the unit's digit of `1⁷²`.

2.  **Find the Unit's Digit of 7¹⁵³:**
    *   **Find the cyclicity of 7:**
        *   `7¹` ends in `7`
        *   `7²` ends in `9`
        *   `7³` ends in `3`
        *   `7⁴` ends in `1`
        *   `7⁵` ends in `7` (pattern repeats)
    *   The cycle of unit digits for 7 is `[7, 9, 3, 1]`, which has a length of `4`.
    *   **Find the position in the cycle:** Divide the exponent `153` by the cycle length `4`.
        *   `153 ÷ 4 = 38` with a **remainder of 1**.
    *   A remainder of 1 means the unit digit is the 1st number in the cycle, which is `7`.

3.  **Find the Unit's Digit of 1⁷²:**
    *   Any positive integer power of a number ending in `1` will always have `1` as its unit's digit.
    *   So, the unit's digit is `1`.

4.  **Multiply the Final Unit's Digits:**
    *   (Unit digit of `7¹⁵³`) × (Unit digit of `1⁷²`) = `7 × 1 = 7`.

---

#### ✅ **Final Answer:** **7**
`

### **Question 15: Unit Digit in Sum of Powers**

**Problem:** Find the unit's digit in (264)¹⁰² + (264)¹⁰³

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

Similar to the last question, we focus on the unit's digit of the base, find the unit's digit of each part, and then add them.

1.  **Simplify the Problem:**
    *   We need to find the unit's digit of `4¹⁰² + 4¹⁰³`.

2.  **Find the Unit's Digit of 4¹⁰²:**
    *   **Find the cyclicity of 4:**
        *   `4¹` ends in `4`
        *   `4²` ends in `6`
        *   `4³` ends in `4`
        *   `4⁴` ends in `6`
    *   The cycle of unit digits for 4 is `[4, 6]`. It depends on whether the exponent is odd or even.
    *   **Rule for 4:** If the power is **odd**, the unit digit is `4`. If the power is **even**, the unit digit is `6`.
    *   The exponent `102` is **even**. So, the unit's digit of `4¹⁰²` is `6`.

3.  **Find the Unit's Digit of 4¹⁰³:**
    *   The exponent `103` is **odd**. So, the unit's digit of `4¹⁰³` is `4`.

4.  **Add the Final Unit's Digits:**
    *   (Unit digit of `4¹⁰²`) + (Unit digit of `4¹⁰³`) = `6 + 4 = 10`.
    *   The unit's digit of the sum `10` is `0`.

---

#### ✅ **Final Answer:** **0**
`

## 📊 Prime Factorization

### **Question 16: Count Prime Factors**

**Problem:** Find total number of prime factors in 4¹¹ × 7⁵ × 11²

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

The "total number of prime factors" means if we were to write out the full prime factorization, how many prime numbers would be in that list. The shortcut is to sum the exponents after ensuring all bases are prime.

1.  **Break Down All Bases into Prime Numbers:**
    *   `4¹¹`: The base `4` is not a prime number. `4 = 2²`.
        *   So, `4¹¹ = (2²)¹¹`.
        *   Using the power rule `(a^m)^n = a^(m*n)`, this becomes `2^(2×11) = 2²²`.
    *   `7⁵`: The base `7` is a prime number. We leave it as is.
    *   `11²`: The base `11` is a prime number. We leave it as is.

2.  **Write the Full Prime Factorization:**
    *   The expression is `2²² × 7⁵ × 11²`.

3.  **Sum the Exponents:**
    *   This expression means we have `22` factors of `2`, `5` factors of `7`, and `2` factors of `11`.
    *   Total number of prime factors = `22 + 5 + 2 = 29`.

---

#### ✅ **Final Answer:** **29**
`

## 🔢 Counting Trailing Zeros

### **Question 17: Zeros in 100!**

**Problem:** What is the number of zeros at the end of the product of numbers from 1 to 100? (This is also written as finding the number of trailing zeros in 100!)

---

#### **🛠️ Step-by-Step Solution**

**Explanation Breakdown:**

Trailing zeros in a factorial (like 100! = 1 × 2 × 3 × ... × 100) are created by pairs of `2` and `5` in its prime factorization.
*   `10 = 2 × 5` (one zero)
*   `100 = 10 × 10 = (2 × 5) × (2 × 5)` (two zeros)

In any factorial, the prime factor `2` appears much more frequently than `5` (every even number has a factor of 2). Therefore, the number of trailing zeros is limited by the number of times `5` appears as a factor. Our task is to count the total number of factors of 5 in 100!.

1.  **Count Multiples of 5 (each contributes at least one factor of 5):**
    *   How many numbers from 1 to 100 are divisible by 5?
    *   `100 ÷ 5 = 20`.
    *   So, there are 20 numbers (5, 10, 15, ..., 100) that give us at least one factor of 5.

2.  **Count Multiples of 25 (each contributes an *extra* factor of 5):**
    *   Numbers like `25` (`5 × 5`), `50` (`2 × 5 × 5`), `75` (`3 × 5 × 5`), and `100` (`4 × 5 × 5`) have *two* factors of 5.
    *   We already counted one factor for each of them in Step 1. Now we need to count the second factor.
    *   How many numbers from 1 to 100 are divisible by 25?
    *   `100 ÷ 25 = 4`.
    *   So, there are 4 numbers that give us an additional factor of 5.

3.  **Count Multiples of 125 (each contributes a third factor of 5):**
    *   How many numbers from 1 to 100 are divisible by 125?
    *   `100 ÷ 125 = 0`.
    *   There are no multiples of 125 in this range.

4.  **Sum the Counts:**
    *   The total number of factors of 5 is the sum of the counts from each step.
    *   Total factors of 5 = (Count of multiples of 5) + (Count of multiples of 25) + ...
    *   Total = `20 + 4 = 24`.
    *   Since there are 24 factors of 5 (and more than enough factors of 2), we can make 24 pairs of `(2 × 5)`, which results in 24 trailing zeros.

---

#### ✅ **Final Answer:** **24**
`