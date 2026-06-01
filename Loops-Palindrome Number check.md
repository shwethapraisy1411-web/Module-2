## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program

<img width="650" height="425" alt="image" src="https://github.com/user-attachments/assets/3f9d2333-adc4-4419-86a0-e1255337fd30" />

## Output
<img width="458" height="280" alt="image" src="https://github.com/user-attachments/assets/ba8b6552-742f-4667-b9d1-48d395d48cb7" />

## Result
The output is verified successfully.
