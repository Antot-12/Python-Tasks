# 🛠️ **XOR & Array Matching Utility** 🚀

This program combines two functions into one unified tool:

1. 🔎 **`maxXor`**: Find the **maximum XOR value** within a given range.  


2. 🔢 **`minimumMoves`**: Calculate the minimum moves required to match two arrays digit by digit.


---

## 📋 **Features**

- ✅ **maxXor**: Calculates the largest XOR result for pairs `(a, b)` where `lo ≤ a, b ≤ hi` and ensures the result is within a given limit `k`.  
- ✅ **minimumMoves**: Compares two integer arrays and calculates the total "move count" to match them, where a "move" is incrementing or decrementing individual digits.  
- ✅ **Menu-Driven Interface**: Easy-to-use interactive input selection for seamless operation.  

---

## 🚀 **Getting Started**

Clone the repository and run the program:

```bash
git clone https://github.com/yourusername/xor-array-matcher.git

cd xor-array-matcher

python3 main.py

```
---

## 📖 **How to Use**

1. Run the program. A menu will appear asking you to choose a function:

```
Select which function to run:
1. maxXor
2. minimumMoves
Enter your choice (1 or 2): 
```

### 🔎 **1. maxXor**

Input the range `[lo, hi]` and the maximum allowable XOR value `k`. The program will calculate the largest possible XOR value satisfying the conditions.

#### 🧩 **Example:**

**Input**:
```
Running maxXor function...
Enter the lower bound (lo): 3
Enter the upper bound (hi): 5
Enter the maximum XOR value (k): 6
```

**Output**:
```
Maximum XOR value: 6
```

**Explanation**:
- Pairs `(3, 5)` give XOR = 6, which is the largest value ≤ 6.

---

### 🔢 **2. minimumMoves**

Input two arrays of integers. The program calculates the total number of moves needed to make both arrays identical.

- **A move**: Incrementing or decrementing a single digit in a number.

#### 🧩 **Example:**

**Input**:
```
Running minimumMoves function...
Enter the number of elements in the first array: 2
Enter element 1 for array 1: 1234
Enter element 2 for array 1: 5678
Enter the number of elements in the second array: 2
Enter element 1 for array 2: 2345
Enter element 2 for array 2: 6789
```

**Output**:
```
Total minimum moves: 10
```

**Explanation**:
- Compare `1234` to `2345`:
    - Moves: `1→2, 2→3, 3→4, 4→5` → 4 moves.


- Compare `5678` to `6789`:
    - Moves: `5→6, 6→7, 7→8, 8→9` → 4 moves.


- Total = 4 + 4 = 8 moves.

---
