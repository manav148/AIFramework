# Test-Driven Development (TDD) Process

Follow this guide to implement features using the TDD approach. The TDD cycle consists of three steps: Red, Green, Refactor.

## TDD Cycle

1. Red: Write a failing test
2. Green: Write the minimum amount of code to make the test pass
3. Refactor: Improve the code without changing its functionality

## Steps

1. Choose a BDD scenario from `bdd_scenarios.md` to implement.
2. Write a failing test in `test_suite.txt` that corresponds to the chosen scenario.
3. Run the test suite to ensure the new test fails (Red).
4. Implement the minimum code necessary in `main_application.txt` to make the test pass.
5. Run the test suite again to ensure all tests, including the new one, pass (Green).
6. Refactor the code if needed, ensuring all tests still pass after refactoring.
7. Repeat the process for the next test case or scenario.

## Example

```
[LLM: Replace this example with actual test cases and code snippets as you develop your AI software. Follow the Red-Green-Refactor cycle for each feature or functionality.]

# Red: Write a failing test
def test_user_login():
    assert login("user", "password") == True

# Green: Implement the minimum code to make the test pass
def login(username, password):
    return True

# Refactor: Improve the code without changing its functionality
def login(username, password):
    # Add actual login logic here
    return check_credentials(username, password)

def check_credentials(username, password):
    # Implement credential checking logic
    pass
```

Remember to always run the entire test suite before implementing new features to ensure existing functionality is not broken.
