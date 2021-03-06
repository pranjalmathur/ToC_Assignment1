## CSD303 - Theory Of Computation - Assignment 1

- Group Name: TBD 
- Group Members
  - Pranjal Mathur (1410110296) - [github@pranjalmathur](https://github.com/pranjalmathur/)
  - Vishal Gauba (1410110501) - [github@flamefractal](https://github.com/flamefractal/)
  - Saketh Vallakatla (1410110352) - [github@saketh21v](https://github.com/saketh21v/)
- Modules left:
  - thompson nfa debug (not working yet)



### Question 1

**Problem statement:** *Substring matching*

**Language**: *Java* 

**Description:**

+ Realtime DFA/Transition table formation.
+ Use Knuth-Morris-Pratt construction algorithm to search for the strings
+ Returns Found (along with the index number)/ Not Found based on the criteria.
+ Program ends when user input `END` as the string
> Example implementation and pseudo code: http://people.cs.pitt.edu/~aus/cs1501/KMP_algorithm.pdf



### Question 2

**Problem statement:** *RegEx matching using Thompson NFA*

**Language**: *Python* 

**Description:**

- Infix to Postfix conversion .
- Create small fragments using Thompson's algorithm and joins them
- Matches the input string and returns if matched

> Example code: https://swtch.com/~rsc/regexp/nfa.c.txt



### Question 3

**Problem statement:** *Vending machine implementation with Moore Machine*

**Language**: *python* 

**Description:**

+ The machine has 4 states namely, 
  + `0¢`
  + `5¢`
  + `10¢`
  + `15¢`
+ Input symbols are : `5`, `10`
+ Final State: `15¢`
+ Final Condition: Output string should contain at least one '1'.
+ Program exits after seeing '1' at the last position of output string.
