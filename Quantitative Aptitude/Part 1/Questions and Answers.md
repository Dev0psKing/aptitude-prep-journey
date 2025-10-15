# 🔢 Numbers - Solved Questions and Answers

> “Numbers are the foundation of all reasoning — master them, and logic follows naturally.”

This section presents **practice questions with fully worked solutions** to strengthen your grasp of number theory, divisibility, and remainders — core areas in **quantitative aptitude** and **competitive reasoning tests**.

---

## 📘 Overview

A **number** is a collection of digits arranged in a specific order.  
These solved questions cover key numerical concepts like **LCM/HCF**, **remainders**, **divisibility**, **cyclicity**, and **prime numbers**, helping you connect theory with applied problem-solving.

---

## 🧮 Practice Questions and Detailed Solutions

### **Question 1:**  
When a number is successively divided by 35, 45, and 55, we get 18, 28, and 38 as remainders respectively.  
What is the smallest such number?

**Solution:**
- LCM(35, 45, 55) = 3465  
- Common difference:  
  - 35 − 18 = 17  
  - 45 − 28 = 17  
  - 55 − 38 = 17  
  ⇒ Common remainder = **17**

Now, smallest number = LCM − remainder = **3465 − 17 = 3448**

✅ **Answer:** 3448

---

### **Question 2:**  
How many four-digit numbers are divisible by 7?

**Solution:**
- Smallest 4-digit number = 1000  
  ⇒ 1000 ÷ 7 ≈ 142.857 → Next = 143 × 7 = 1001  
- Largest 4-digit number = 9999  
  ⇒ 9999 ÷ 7 ≈ 1428.428 → 1428 × 7 = 9996  

Arithmetic sequence:  
a₁ = 1001, aₙ = 9996, d = 7  

\[
aₙ = a₁ + (n − 1)d
\]

\[
9996 = 1001 + (n−1)7
\Rightarrow n = 1286
\]

✅ **Answer:** 1286 four-digit numbers divisible by 7

---

### **Question 3:**  
Find the maximum value of **B** in:

1 2 B

B 4 C

C 6 7

1 0 3 5

yaml
Copy code

**Solution:**
From the hundreds column:  
B + C = 8 or 18  

If B + C = 18 → B = C = 9 → gives 2045 ≠ 1035 ❌  
So, B + C = 8 → To maximize **B**, set C = 0 → B = 8  

✅ **Answer:** B = 8

---

### **Question 4:**  
Which are prime numbers?  
(i) 247 (ii) 397 (iii) 423  

**Solution:**
- 247 divisible by 13 → ❌ Composite  
- 397 not divisible by primes ≤ 19 → ✅ Prime  
- 423 divisible by 3 → ❌ Composite  

✅ **Answer:** 397 is prime

---

### **Question 5:**  
Find the unit’s digit of (17)¹⁵³ × (31)⁶².

**Solution:**
Focus on unit digits: 7 and 1.  
Cyclicity of 7 → [7, 9, 3, 1] repeats every 4 powers.  

153 ÷ 4 = remainder 1 → unit digit = 7  
1⁶² = 1  

7 × 1 = **7**

✅ **Answer:** 7

---

### **Question 6:**  
Find the unit’s digit of (17)¹⁵³ + (31)⁶².

Cyclic pattern same as above:  
7¹⁵³ → 7; 1⁶² → 1  
Sum = 7 + 1 = **8**

✅ **Answer:** 8

---

### **Question 7:**  
Find total number of prime factors in:  
(14)¹¹ × (7)² × (11)³  

**Solution:**
\[
(14)^{11} × (7)^2 × (11)^3
= (2×7)^{11} × 7^2 × 11^3
= 2^{11} × 7^{13} × 11^3
\]

Sum of powers = 11 + 13 + 3 = **27**

✅ **Answer:** 27 prime factors

---

### **Question 8:**  
Which digits replace * and # so that 12386*# is divisible by 8 and 5?

**Solution:**
- Divisible by 5 ⇒ last digit (#) = 0  
- Last 3 digits form 6*0 ⇒ divisible by 8 when * = 0, 4, or 8  

✅ **Answer:** * = 0, 4, or 8; # = 0

---

### **Question 9:**  
What least number must be **subtracted** from 9999 to make it divisible by 19?

**Solution:**
9999 ÷ 19 leaves remainder 5 → subtract 5

✅ **Answer:** 5

---

### **Question 10:**  
What least number must be **added** to 9999 to make it divisible by 19?

**Solution:**
Remainder = 5 → add (19 − 5) = 14

✅ **Answer:** 14

---

### **Question 11:**  
A number when divided by 340 leaves remainder 47.  
What is the remainder when divided by 17?

**Solution:**
\[
N = 340a + 47 = 17(20a + 2) + 13
\]

✅ **Answer:** 13

---

### **Question 12:**  
Find remainder when 3²¹ is divided by 5.

**Solution:**
Cyclic pattern of 3 mod 5 → [3, 4, 2, 1] every 4 terms.  
21 ÷ 4 → remainder 1 → unit digit = 3  

✅ **Answer:** 3

---

## 💡 Key Takeaways
- **Patterns matter:** Unit digits and cyclicity simplify large powers.  
- **LCM/HCF logic** helps solve modular remainder problems efficiently.  
- **Practice consistency** turns complex divisibility into intuition.  

---

## 🧭 Next Step
Continue to the next topic:  
➡️ [LCM & HCF](../LCM_HCF/README.md)

---

**Author:** [Uwabor Collins](https://github.com/Dev0psKing)  
**Repository:** [Aptitude Prep Journey](https://github.com/Dev0psKing/aptitude-prep-journey)
