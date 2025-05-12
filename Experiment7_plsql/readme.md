# Experiment 7: PL/SQL – Variables, Control Structures and Loops

## AIM
To write and execute simple PL/SQL programs using variables, loops, and conditional statements.


## THEORY

PL/SQL, which stands for Procedural Language extensions to the Structured Query Language (SQL). It is a combination of SQL along with the procedural features of programming languages.

**Syntax:**
```sql
DECLARE 
   <declarations section> 
BEGIN 
   <executable command(s)>
EXCEPTION 
   <exception handling> 
END;
```

### Basic Components of PL/SQL Block:
- DECLARE: Section to declare variables and constants.
- BEGIN: The execution section that contains PL/SQL statements.
- EXCEPTION: Handles errors or exceptions that occur in the program.
- END: Marks the end of the PL/SQL block.

# PL/SQL Programs – Steps and Expected Output

## 1. Write a PL/SQL program to find the Greatest of Two Numbers

### Steps:
- Declare two numeric variables and initialize them.
- Use an `IF` statement to compare the values.
- Display the greater number using `DBMS_OUTPUT.PUT_LINE`.
### Program:
![image](https://github.com/user-attachments/assets/e15d9465-0b21-468c-9ce8-9e2f88e9e0a2)

**Expected Output:**  
Greater number is: 80
### Output:
![image](https://github.com/user-attachments/assets/c02c8186-4e9d-44d8-bc1c-f675c606ef6c)

---

## 2. Write a PL/SQL program to Calculate Sum of First N Natural Numbers

### Steps:
- Declare a variable `n` and assign a value (e.g., 10).
- Initialize a `sum` variable to 0.
- Use a `WHILE` loop to iterate from 1 to `n`, adding each number to the sum.
- Display the result using `DBMS_OUTPUT.PUT_LINE`.
### Program:
![image](https://github.com/user-attachments/assets/70d387ec-e35a-4939-9869-c7e1d0c93392)

**Expected Output:**  
Sum of first 10 natural numbers is: 55
### Output:
![image](https://github.com/user-attachments/assets/e61f1642-3682-49e9-ad5d-552daff77664)

---

## 3. Write a PL/SQL program to generate Fibonacci series

### Steps:
- Declare the variable `n` to indicate how many terms to generate.
- Initialize the first two Fibonacci numbers (0 and 1).
- Use a loop to generate the next terms using the formula `c = a + b`.
- Print each term in the series.
### Program:
![image](https://github.com/user-attachments/assets/9da9964e-26bb-47f3-84a7-1ec9c44593f9)

**Expected Output:**  
n = 7  
Fibonacci sequence: 0, 1, 1, 2, 3, 5, 8
### Output:
![image](https://github.com/user-attachments/assets/ab326332-1aa4-4d92-8156-c70fdc0469a9)

---

## 4. Write a PL/SQL Program to display the number in Reverse Order

### Steps:
- Declare a variable `n` and assign a value (e.g., 1535).
- Use a loop to extract each digit using modulo and reverse the number.
- Display the reversed number.
### Program:
![image](https://github.com/user-attachments/assets/ba22db27-7098-4b60-958d-6d2ea9588d82)

**Expected Output:**  
n = 1535  
Reversed number is 5351
### Output:
![image](https://github.com/user-attachments/assets/938df7f7-f99c-407b-8347-d214c3b7a173)

---

## 5. Write a PL/SQL program to find the largest of three numbers

### Steps:
- Declare three numeric variables `a`, `b`, and `c`.
- Use nested `IF-ELSIF-ELSE` conditions to find the largest among the three.
- Display the largest number.
### Program:
![image](https://github.com/user-attachments/assets/093dc4e5-c4f3-45ac-8244-2159658e24da)

**Expected Output:**  
a = 10, b = 9, c = 15  
Largest of three number is 15
### Output:
![image](https://github.com/user-attachments/assets/0f36fc5f-d114-4071-8733-3b3d39e80e97)


## RESULT
Thus, the PL/SQL programs using variables, conditionals, and loops were executed successfully.
