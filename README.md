# ECE444-lab5

Jiangshan Cui

## Pros and Cons of Test Driven Developement (TDD)
### TDD Pros: 
1. Less bugs: 
	Since all the scenarios of the requirement are included and implemented as tests before the development, the test cases become the blueprint of the implementation of the requirement. The developer would not easily forget some of the scenarios. Thus, the biggest advantages of Test Driven Development is to ensure the integrity and performance of the project, reducing the future expense on bug fixes. Furthermore, if the tests were approved by the team before development, there could be less missing corner cases. 

2. Less regression:
	TDD has the potential to notify developers about regressions prior to merging changes into the entire codebase. For instance, when a developer completes part 1 and progresses to part 2, any code in part 2 that disrupts the functionality of part 1 would trigger the previously established test cases for part 1, serving as an early warning system for regressions.

3. Code readability: 
	The test cases become documentation after the requirement is implemented. It could provide the team a way to easily understand the code and functionality of the requirements.
   
### Cons of TDD:
1. Slow development cycle:
    Since the developer needs to develop the tests and ask approval from the team before requirement implementation, the development requires extra time. When there is a closed deadline or emergent feature request from customers, TDD would be the best procedure to follow.
