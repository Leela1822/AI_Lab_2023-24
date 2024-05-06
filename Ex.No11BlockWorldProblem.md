# Ex.No: 11  Planning –  Block World Problem 
### DATE: 01.04.2024                                                                            
### REGISTER NUMBER : 212221040088
### AIM: 
To find the sequence of plan for Block word problem using PDDL  
###  Algorithm:
Step 1 :  Start the program <br>
Step 2 : Create a domain for Block world Problem <br>
Step 3 :  Create a domain by specifying predicates clear, on table, on, arm-empty, holding. <br>
Step 4 : Specify the actions pickup, putdown, stack and un-stack in Block world problem <br>
Step 5 :  In pickup action, Robot arm pick the block on table. Precondition is Block is on table and no other block on specified block and arm-hand empty.<br>
Step 6:  In putdown action, Robot arm place the block on table. Precondition is robot-arm holding the block.<br>
Step 7 : In un-stack action, Robot arm pick the block on some block. Precondition is Block is on another block and no other block on specified block and arm-hand empty.<br>
Step 8 : In stack action, Robot arm place the block on under block. Precondition is Block holded by robot arm and no other block on under block.<br>
Step 9 : Define a problem for block world problem.<br> 
Step 10 : Obtain the plan for given problem.<br> 
     
### Program:

![image](https://github.com/Leela1822/AI_Lab_2023-24/assets/106167639/2ad73adc-556e-44e7-ade6-ef3806878640)








### Input 

![image](https://github.com/Leela1822/AI_Lab_2023-24/assets/106167639/79e3be72-2696-4308-a664-fc1b7b230c4f)

### Output/Plan:

![image](https://github.com/Leela1822/AI_Lab_2023-24/assets/106167639/dae10bff-129b-4425-853d-cd1b07ede736)


### Result:
Thus the plan was found for the initial and goal state of block world problem.
