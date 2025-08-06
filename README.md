# 🧠 Bitwise Operators in C++

---

## 🔹 What Are Bitwise Operators?

Bitwise operators are used to perform operations directly on **binary representations** of integers. These operators are especially useful in **system programming, low-level data manipulation, embedded systems, cryptography**, and **game development**.

Every integer in memory is stored in binary (a sequence of 0s and 1s). Bitwise operators allow you to manipulate these bits directly for maximum performance and control.

---

## 🔸 Why Use Bitwise Operators?

✅ Faster execution (bitwise operations are low-level and close to hardware)  
✅ Useful in memory-efficient algorithms  
✅ Helpful for setting flags, toggling bits, packing/unpacking data  
✅ Core concept in operating systems, hardware drivers, and embedded systems  

---

## 🔹 List of Bitwise Operators in C++

| Operator | Symbol | Description                                |
|----------|--------|--------------------------------------------|
| AND      | `&`    | Bitwise AND                                 |
| OR       | `\|`   | Bitwise OR                                  |
| XOR      | `^`    | Bitwise Exclusive OR                        |
| NOT      | `~`    | Bitwise NOT (One's Complement)              |
| Left Shift  | `<<` | Shifts bits to the left (fills 0 from right) |
| Right Shift | `>>` | Shifts bits to the right (drops rightmost bits) |

---

## 🧾 Detailed Explanation of Each Operator

### 🔸 1. Bitwise AND (`&`)

Performs **logical AND** operation on each corresponding bit of two numbers. The result is 1 only if **both bits are 1**.

#### Example:
```cpp
int a = 5;  // 0101
int b = 3;  // 0011
int c = a & b; // 0001 → 1

