# the random module
- if you want the computer to pick a something use the random module.

- **random functions**

- randint - `random.randint(0,5)` picks a random number between 1 and 5.

- if you want a larger number you can multiply.
- `random.randint() *100`

- choice - chose from a list of choices.
-  `random.choice( ['red,' 'black', 'green'] )`

- shuffle 
- `from random import shuffle`
- `x = [[i] for i in range(10)]`
- `shuffle(x)`

## Risk Analysis

- In Software Testing, risk analysis is the process of identifying the risks in applications or software that you built and prioritizing them to test.

- Why use Risk Analysis?
- it helps the developers and managers to mitigate the risks. 
- possible risks you can encounter...
- 1. Use of new hardware
- 2. Use of new technology
- 3. Use of new automation tool
- 4. The sequence of code
- 5. Availability of test resources for the application

- *risk assessment*
- early forecast of unwanted situation in your project
- estimating potential loss of such situation
- making decision to deal with such situation
- avoid the future consequences

- The perspective of Risk Assessment
- Effect – To assess risk by Effect. In case you identify a condition, event or action and try to determine its impact.

- Cause – To assess risk by Cause is opposite of by Effect. Initialize scanning the problem and reach to the point that could be the most probable reason behind that.

- Likelihood – To assess risk by Likelihood is to say that there is a probability that a requirement won’t be satisfied.

big 0 (algorithmic efficiency)
    o(1) constant time with respect to the size of the input.
    o(n) linear time with respect to the size of the input. twice as much data takes twice as much time

if you have two steps in your algorithm you add those steps.
o(a) and o(b) = o(a+b)