# AI Software Development Framework

This framework provides a structure for developing AI software using Behavior-Driven Development (BDD), Test-Driven Development (TDD), and following best coding practices. It is designed to be language-agnostic and guide an LLM through the development process.

## Framework Structure

1. `bdd_scenarios.md`: Write BDD scenarios here before implementation.
2. `tdd_development.md`: Follow the TDD process outlined in this file.
3. `best_practices.md`: Adhere to the coding best practices described here.
4. `main_application.txt`: Implement the main application code here.
5. `test_suite.txt`: Write and maintain tests here.

## Development Process

1. Start by creating BDD scenarios in `bdd_scenarios.md`.
2. Follow the TDD process outlined in `tdd_development.md`.
3. Implement features in `main_application.txt` only when all existing tests pass.
4. Write and update tests in `test_suite.txt`.
5. Adhere to best practices described in `best_practices.md`.

Remember to always run the regression tests before implementing new features to ensure existing functionality is not broken.

## Project Structure

Maintain a clear and organized project structure as follows:

```
project_root/
│
├── src/
│   ├── main_application.txt
│   ├── utils/
│   │   └── helpers.txt
│   └── models/
│       └── ai_model.txt
│
├── tests/
│   ├── test_suite.txt
│   ├── unit/
│   │   └── test_helpers.txt
│   └── integration/
│       └── test_ai_model.txt
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── models/
│
├── docs/
│   └── api_documentation.md
│
├── bdd_scenarios.md
├── tdd_development.md
├── best_practices.md
├── README.md
└── requirements.txt
```

### Directory Explanations:

- `src/`: Contains the main application code and related modules.
  - `utils/`: Utility functions and helper modules.
  - `models/`: AI model implementations.
- `tests/`: Houses all test-related files.
  - `unit/`: Unit tests for individual components.
  - `integration/`: Integration tests for testing interactions between components.
- `data/`: Stores data used in the project.
  - `raw/`: Raw, unprocessed data.
  - `processed/`: Cleaned and preprocessed data.
  - `models/`: Trained model files or model checkpoints.
- `docs/`: Documentation files, including API documentation.

### Maintaining the Project Structure:

1. Keep related files together in their respective directories.
2. Use clear, descriptive names for files and directories.
3. Separate concerns: keep data processing, model training, and inference in different modules.
4. Keep the `requirements.txt` file updated with all project dependencies.
5. Use relative imports within the project to maintain modularity.
6. As the project grows, consider breaking down large modules into smaller, more manageable files.
7. Regularly review and refactor the project structure to ensure it remains clean and efficient.

By following this structure and these guidelines, you'll maintain a clean, organized, and scalable AI software project.
