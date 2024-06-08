# Some tips for unit testings
## 1. Follow Arrange, Act, Assert 
- Step 1: Arrange 
    - Set up variables, instantiate objects, and all other required setup for the test to run 

- Step 2: Act 
    - Invoke the tested function, store its results. 

- Step 3: Assert: 
    - Check to see if the hypothesis is true or not. 

## 2. Keep unit test short and simple
Since unit test is for testing small pieces of code, we want to keep them short. Complex tests will make it hard to see where is the bug. 

## 3. Cover Happy Path First
- It helps polish the code before implementation usin TDD.
- These tests are also simpler to write
- Also acts as documentation. It illustrates how to use the code being tested. 

## 4. Test edge cases:
This is important, in order to make sure that the code works, even in rare cases. 