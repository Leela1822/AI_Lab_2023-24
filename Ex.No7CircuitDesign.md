# Ex.No: 7  Logic Programming –  Logic Circuit Design
### DATE: 23-03-2024                                                                           
### REGISTER NUMBER : 212221040088
### AIM: 
To write a logic program to design a circuit like half adder and half subtractor.
###  Algorithm:
1. Start the Program
2. Design a AND gate logic if both inputs are 1 then output is 1.
3. Design a OR gate logic if any one of input is 1 then output is 1.
4. Design a XOR gate logic if both inputs are different then output is 1.
5. Design a NOT gate logic if input is 0 then output is 1.
6. Design a half adder and half subtractor using the rules.
7. Test the logic.
8. Stop the program.

### Program:

```
 /*
 :- discontiguous and/3.
 :- discontiguous xor/3.
 :- discontiguous not/2.
 and(0, 0, 0).
 and(0, 1, 0).
 and(1, 0, 0).
 and(1, 1, 1).
 xor(0, 0, 0).
 xor(0, 1, 1).
 xor(1, 0, 1).
 xor(1, 1, 0).
 not(0, 1).
 not(1, 0).
 % Define half adder
 halfadder(A, B, Sum, Carry) :
xor(A, B, Sum),
 and(A, B, Carry).
 % Define half subtractor
 halfsubtractor(A, B, Diff, Borrow) :
xor(A, B, Diff),
 not(B, B_Not),
 and(A, B_Not, Borrow).
 /*
```









### Output:

![image](https://github.com/Leela1822/AI_Lab_2023-24/assets/106167639/4312ab9d-997c-4ceb-b3af-5fb8565fa5a9)

![image](https://github.com/Leela1822/AI_Lab_2023-24/assets/106167639/77b36f9d-52ec-41f4-935a-4da7ae4709db)


### Result:
Thus the truth table of circuit verified sucessfully.
