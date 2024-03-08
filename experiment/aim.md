### Objective

Objective of 4 bit arithmetic logic unit (with AND, OR, XOR, ADD operation):

1. Understanding behaviour of arithmetic logic unit from working module and the module designed by the student as part of the experiment

2. Designing an arithmetic logic unit for given parameter

**Examining behaviour of arithmetic logic unit for the working module and module designed by the student as part of the experiment (refer to the circuit diagram):
Loading data in the arithmetic logic unit (refer to procedure tab for further detail and experiment manual for pin numbers):**

- load the two input numbers as:
    - A(A3 A2 A1 A0): A3=1, A2=1, A1=0, A0=0
    - B(B3 B2 B1 B0): B3=1, B2=0, B1=0, B0=1
    - carry in(C0)=0

<b>Examining the AND behaviour:</b>

- load data in select input as:
    - S1=0, S0=0 

- check output:
    - F3=1, F2=0, F1=0, F0=0
    - cout=0 

<b>Examining the OR behaviour:</b>

- load data in select input as:
    - S1=0, S0=1 

- check output:
    - F3=1, F2=1, F1=0, F0=1
    - cout=0 

<b>Examining the XOR behaviour:</b>

- load data in select input as:
    - S1=1, S0=0

- check output: 
    - F3=0, F2=1, F1=0, F0=1
    - cout=1 

<b>Recommended learning activities for the experiment:</b>  Leaning activities are designed in two stages, a basic stage and an advanced stage. Accomplishment of each stage can be self-evaluated through the given set of quiz questions consisting of multiple type and subjective type questions. In the basic stage, it is recommended to perform the experiment firstly, on the given encapsulated working module, secondly, on the module designed by the student, having gone through the theory, objective and procuder. By performing the experiment on the working module, students can only observe the input-output behavior. Where as, performing experiments on the designed module, students can do circuit analysis, error analysis in addition with the input-output behavior. It is recommended to perform the experiments following the given guideline to check behavior and test plans along with their own circuit analysis. Then students are recommended to move on to the advanced stage. The advanced stage includes the accomplishment of the given assignments which will provide deeper understanding of the topic with innovative circuit design experience. At any time, students can mature their knowledge base by further reading the references provided for the experiment.

- color configuration of wire for 5 valued logic supported by the simulator:
    - if value is UNKNOWN, wire color= maroon
    - if value is TRUE, wire color= blue
    - if value is FALSE, wire color= black
    - if value is HI IMPEDENCE, wire color= green
    - if value is INVALID, wire color= orange

<b>likewise the 16 bit arithmetic logic unit can be designed and tested</b>
    - by cascading 4 bit ALUs only the carry will propagate to the next level for ADD operation

<b>Test Plan:</b>

1. Set inputs 0101 and 0011 and check output for all possible select input combinations.
2. Set any two 16-bit number and check output for all possible select input combinations.
Use Display units for checking output. Try to use minimum number of components to build. The pin configuration of the canned components are shown when mouse hovered over a component.

<b>Assignment Statements :</b>

1. Design a 4 bit ALU comprising only the AND, OR, XOR and Add operations.
2. Design a 16-bit ALU with capabilities similar to 74181
