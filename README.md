# BigINT

## High-Performance Arbitrary Precision Integer Library for C++

BigINT is a custom arbitrary precision arithmetic library written in C++ that supports computations on extremely large integers beyond native C++ datatype limits.

The project demonstrates:
- custom arithmetic algorithms,
- operator overloading,
- low-level numerical computation,
- algorithmic problem solving,
- and systems-oriented C++ design.

Designed primarily for:
- Competitive Programming
- Number Theory
- Scientific Computation
- Large Integer Arithmetic
- Educational Systems Programming

---

## 🚀 Features

- ✅ Arbitrary Precision Integer Arithmetic
- ✅ Addition, Subtraction, Multiplication, Division & Modulo
- ✅ Operator Overloading
- ✅ GCD & LCM Computation
- ✅ Factorial of Extremely Large Numbers
- ✅ Prime Checking
- ✅ Square Root Computation
- ✅ Logarithmic Utilities
- ✅ Palindrome & Reverse Utilities
- ✅ Increment / Decrement Operations
- ✅ Standard C++ Style Usage

---

# 📦 Project Structure

```text
BigINT/
│
├── bigint class.h
├── bigint_function_definitions.h
├── SampleTest.cpp
└── README.md
```

---

# ⚙️ Compilation & Execution

## Compile

```bash
g++ -std=c++17 SampleTest.cpp -o test
```

## Run

```bash
./test
```

---

# 🧠 Example Usage

```cpp
#include "bigint class.h"
#include "bigint_function_definitions.h"

int main() {

    bigint a("999999999999999999999999999999");
    bigint b("888888888888888888888888888888");

    cout << "Addition : " << a + b << endl;

    cout << "Multiplication : " << a * b << endl;

    cout << "Factorial(100) : " << big_fact(100) << endl;

    cout << "GCD : " << big_gcd(a, b) << endl;

}
```

---

# 🔢 Supported Operations

## Arithmetic Operations

- Addition
- Subtraction
- Multiplication
- Division
- Modulo

Example:

```cpp
bigint c = a + b;
bigint d = a * b;
bigint e = a / b;
bigint f = a % b;
```

---

## Comparison Operators

Supports:
- `>`
- `<`
- `>=`
- `<=`
- `==`
- `!=`

Example:

```cpp
if(a > b) {
    cout << "a is greater";
}
```

---

# 🛠️ Inbuilt Functions

| Function | Description |
|---|---|
| `to_bigint()` | Converts integer/string to bigint |
| `big_abs()` | Absolute value |
| `big_max()` | Maximum of two bigints |
| `big_min()` | Minimum of two bigints |
| `big_pow()` | Exponentiation |
| `big_sqrt()` | Square root |
| `big_log2()` | Base-2 logarithm |
| `big_log10()` | Base-10 logarithm |
| `big_logwithbase()` | Logarithm with custom base |
| `big_swap()` | Swaps two bigints |
| `big_gcd()` | Greatest Common Divisor |
| `big_lcm()` | Lowest Common Multiple |
| `big_fact()` | Factorial |
| `big_isPrime()` | Prime checker |
| `big_reverse()` | Reverse digits |
| `big_isPalindrome()` | Palindrome checker |

---

# 📊 Complexity Analysis

| Operation | Complexity |
|---|---|
| Addition | O(n) |
| Subtraction | O(n) |
| Multiplication | O(n²) |
| Division | O(n²) |
| Modulo | O(n²) |
| GCD | O(log n) |
| Factorial | O(n² log n) |

---

# 🔍 Internal Design

The library internally represents large integers as strings and performs arithmetic using custom digit-based algorithms.

Key concepts implemented:
- Carry Propagation
- Manual Long Arithmetic
- Operator Overloading
- String-Based Numerical Representation
- Sign Handling
- Recursive & Iterative Mathematical Utilities

---

# 💡 Example Outputs

## Large Integer Multiplication

```text
3445743511488768021543787806860750328299778111849236444610289955667677784
```

## Factorial(15)

```text
1307674368000
```

## Square Root

```text
7526901790514881921
```

---

# 🎯 Why This Project?

The goal of this project was not merely to create another utility library, but to deeply understand:

- arbitrary precision arithmetic,
- operator overloading,
- low-level numerical algorithms,
- complexity analysis,
- and systems-oriented C++ design.

This project strongly aligns with competitive programming and algorithmic problem solving.

---

# 🚀 Future Improvements

- Karatsuba Multiplication
- FFT-Based Multiplication
- Miller Rabin Primality Testing
- Faster Internal Base Representation
- Benchmarking against Boost Multiprecision
- Modular Arithmetic Utilities
- RSA Demonstration
- Expression Parsing Support

---

# 🏆 Applications

- Competitive Programming
- Cryptography
- Number Theory
- Scientific Computing
- Educational Purposes
- Large Integer Simulations

---

# 👨‍💻 Author

Developed by Aman Tripathi.

- Competitive Programmer
- ICPC 2025 Regionalist
- CodeChef 5★
- LeetCode Guardian
- Codeforces Expert

---
