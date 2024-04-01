**This program allows users to select a mathematical problem from a menu and plots the sanswer. Users can choose from various problems, including polynomials and trigonometric functions, and visualize the results individually or all at once.**

**Process:**

The code starts by importing the matplotlib.pyplot lib to access graphing for the code. A menu of choices(problems 1 to 10) is displayed to the user using the print() function. The user is prompted to input their choice by entering a number corresponding to the problem they want to graph, or they can choose option 11 to plot all problems at once. The user's input is stored in the variable choice using the input() function. Ten functions (problem1() to problem10()) are defined, each representing a specific mathematical problem. Each function reads values of x from a file named xvalue.txt, computes the corresponding solution(s) based on the selected problem's formula, and stores the result(s) in a list. Additionally, the calculated results are saved into separate output files (output1.txt to output10.txt). Conditional statements (if statements) are used to determine the user's choice and execute the corresponding block of code. If the user selects a specific problem (choices 1 to 10), the script calls the corresponding problem-solving function and generates a plot of the results using matplotlib.pyplot. If the user selects option 11 to plot all problems, a dedicated function named displayPlot() is defined to create a plot displaying the results of all 10 problems.


**Here are the 10 graphs for each problem and the graph that contains all problems:**

**1. Problem 1**

![image](https://github.com/CharlesJustinAbellera/DataStructuresAndAlgorithm/assets/143912877/894b1a4d-68a8-4832-a1ca-eb8cf5da4357)


**2. Problem 2**

![image](https://github.com/CharlesJustinAbellera/DataStructuresAndAlgorithm/assets/143912877/48f50bdc-58b8-45f0-a0d5-861e5dfe3d81)


**3. Problem 3**

![image](https://github.com/CharlesJustinAbellera/DataStructuresAndAlgorithm/assets/143912877/294f3d1e-0cf4-469d-af0e-aefcf0382fd9)


**4. Problem 4**

![image](https://github.com/CharlesJustinAbellera/DataStructuresAndAlgorithm/assets/143912877/6155c23e-4167-402b-b694-1ec3a7760931)


**5. Problem 5**

![image](https://github.com/CharlesJustinAbellera/DataStructuresAndAlgorithm/assets/143912877/79b0ccd3-d2c5-4623-b215-5103079a5875)


**6. Problem 6**

![image](https://github.com/CharlesJustinAbellera/DataStructuresAndAlgorithm/assets/143912877/560d0840-39bd-45d4-9fb3-80fbd640150a)

**7. Problem 7**

![image](https://github.com/CharlesJustinAbellera/DataStructuresAndAlgorithm/assets/143912877/7e55a4e6-b1b5-42c2-b103-a95aa0c0500d)

**8. Problem 8**

![image](https://github.com/CharlesJustinAbellera/DataStructuresAndAlgorithm/assets/143912877/7eb87591-a675-45c5-bd0c-69c1b84f173c)

**9. Problem 9**

![image](https://github.com/CharlesJustinAbellera/DataStructuresAndAlgorithm/assets/143912877/359eec8a-263e-4ea4-a11c-655a7f7c9bac)

**10. Problem 10**

![image](https://github.com/CharlesJustinAbellera/DataStructuresAndAlgorithm/assets/143912877/48883f41-8e6d-434b-a62c-4e0784fe8b6b)

**11. All Problems**

![image](https://github.com/CharlesJustinAbellera/DataStructuresAndAlgorithm/assets/143912877/8a28ea30-e01c-4cee-8807-8eab68fa1fea)






