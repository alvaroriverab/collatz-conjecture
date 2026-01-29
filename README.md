<div align="center">
  <img src="https://miro.medium.com/v2/resize:fit:890/format:webp/0*m4baUaM9S7DIFGku.png" width="600">
  <h1>🔢 Collatz Conjecture Explorer</h1>

  
  **The 3n+1 Problem** - Does every positive integer eventually reach 1?
  
  ![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/collatz-conjecture?style=social)
  ![Python](https://img.shields.io/badge/Python-3.8+-blue)
  ![MIT License](https://img.shields.io/badge/License-MIT-green)
</div>

## 🚀 Quick Demo
```bash
In 1937, a German mathematician named Lothar Collatz formulated an intriguing hypothesis (it still remains unproven) which can be described in the following way:

    take any non-negative and non-zero integer number and name it c0;
    if it's even, evaluate a new c0 as c0 ÷ 2;
    otherwise, if it's odd, evaluate a new c0 as 3 × c0 + 1;
    if c0 ≠ 1, go back to point 2.

The hypothesis says that regardless of the initial value of c0, it will always go to 1.

This small code doesn't look to prove/disprove the conjecture, just to read one natural number and execute the above steps as long as c0 remains different from 1, while printing the number generated in every iteration and the number of iterations in the end.
