# Data Structures and Algorithms Practice

This repository contains solutions to common Data Structures and Algorithms (DSA) questions. Each question includes sample input and the expected output.

## Questions

### 1. Reverse a String

**Problem:**

Write a function to reverse a given string.

**Sample Input:**

```
"hello"
```

**Expected Output:**

```
"olleh"
```

**Solution:**

```python
def reverse_string(s):
    return s[::-1]
```

### 2. Palindrome Check

**Problem:**

Write a function to check if a given string is a palindrome.

**Sample Input:**

```
"radar"
```

**Expected Output:**

```
True
```

**Solution:**

```python
def is_palindrome(s):
    return s == s[::-1]
```

### 3. Find Maximum Number in a List

**Problem:**

Write a function to find the maximum number in a given list.

**Sample Input:**

```
[3, 7, 2, 9, 1]
```

**Expected Output:**

```
9
```

**Solution:**

```python
def find_max(nums):
    return max(nums)
```

### 4. Fibonacci Series

**Problem:**

Write a function to generate the Fibonacci series up to a given number of terms.

**Sample Input:**

```
5
```

**Expected Output:**

```
[0, 1, 1, 2, 3]
```

**Solution:**

```python
def fibonacci(n):
    fib_series = [0, 1]
    while len(fib_series) < n:
        fib_series.append(fib_series[-1] + fib_series[-2])
    return fib_series[:n]
```

### 5. Check for Prime Number

**Problem:**

Write a function to check if a given number is a prime number.

**Sample Input:**

```
11
```

**Expected Output:**

```
True
```

**Solution:**

```python
def is_prime(num):
    if num < 2:
        return False
    for i in range(2, int(num**0.5) + 1):
        if num % i == 0:
            return False
    return True
```

Feel free to use and modify these solutions for your practice!
```
