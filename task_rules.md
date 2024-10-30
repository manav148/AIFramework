# LLM Rules and Best Practices

## Major Points (Absolutely Neccesary)

1. Regression Testing
   - Before adding new code, existing code should be tested to check for regression.
   - Ensure all existing tests pass before implementing new features or making changes.

2. Unit Testing for New Code
   - All new code should have corresponding unit tests.
   - Run these new unit tests after adding the new code to ensure functionality.

3. File Size Limit
   - The number of lines of code in a single file should be less than 100.
   - If a file exceeds this limit, consider refactoring or splitting the code into multiple files.

4. Use Chain of thought reasoning for coming up with a solution and implementing it

## Best Coding Practices

1. Code Readability
   - Use clear and descriptive variable and function names.
   - Add comments to explain complex logic or algorithms.
   - Follow consistent indentation and formatting.

2. DRY (Don't Repeat Yourself) Principle
   - Avoid code duplication by creating reusable functions or classes.

3. SOLID Principles
   - Single Responsibility: Each class or module should have one reason to change.
   - Open-Closed: Open for extension, closed for modification.
   - Liskov Substitution: Derived classes must be substitutable for their base classes.
   - Interface Segregation: Many client-specific interfaces are better than one general-purpose interface.
   - Dependency Inversion: Depend on abstractions, not concretions.

4. Error Handling
   - Implement proper error handling and logging.
   - Use try-catch blocks where appropriate.

5. Security
   - Follow security best practices, such as input validation and sanitization.
   - Avoid hardcoding sensitive information like passwords or API keys.

6. Performance
   - Optimize code for performance where necessary.
   - Use appropriate data structures and algorithms.

7. Version Control
   - Use meaningful commit messages.
   - Create feature branches for new development.

## File Structure Guidelines

1. Project Organization
   - Separate concerns by using directories for different parts of the application (e.g., src/, tests/, docs/).
   - Keep related files together.

2. Configuration Files
   - Store configuration files (e.g., .gitignore, package.json) in the root directory.

3. Source Code
   - Organize source code in a logical structure (e.g., components/, services/, utils/).
   - Use consistent file naming conventions.

4. Test Files
   - Store test files close to the code they're testing, or in a separate 'tests' directory mirroring the source structure.

5. Documentation
   - Keep a README.md file in the root directory with project overview and setup instructions.
   - Store detailed documentation in a 'docs' directory.

6. Assets
   - Store static assets (images, fonts, etc.) in an 'assets' or 'public' directory.

7. Build Output
   - Use a 'dist' or 'build' directory for compiled or built files.
   - Add this directory to .gitignore to avoid versioning built files.

Remember to adapt these guidelines as needed based on the specific requirements and nature of each project.
