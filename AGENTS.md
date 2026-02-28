```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines detail the principles and requirements for development of AI coding agents within this repository. Adherence to these principles is crucial for maintaining code quality, maintainability, and reliability.

## 1. DRY (Don't Repeat Yourself)

*   All code snippets, functions, and classes should be self-contained and reusable.
*   Avoid duplicating logic across multiple files.
*   When necessary, create reusable components and modules with clear interfaces.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize clarity and readability.
*   Favor straightforward solutions over overly complex ones.
*   Strive for minimal code and unnecessary complexity.
*   Ensure each line of code serves a defined purpose.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one, and only one, reason to change.
*   **Open/Closed Principle:**  The system should be extensible without modifying the existing code.  New functionality should be added through new classes/modules, not by modifying the core code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to cater to interfaces they don't use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules; they should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   Do not introduce functionality that is not currently required.
*   Refactor only when a new requirement emerges.
*   Focus on implementing the necessary functionality for the immediate task.

## 5. Code Structure & Formatting

*   **File Length:** Each file should maintain a maximum of 180 lines of code.
*   **Comments:**  Provide clear and concise comments explaining the *why* behind the code, not just the *what*.  Avoid commenting on trivial details.
*   **Naming Conventions:** Follow established naming conventions (e.g., camelCase for methods and variables).
*   **Whitespace:** Use consistent whitespace for readability.
*   **Indentation:** Use 2 spaces for indentation.

## 6. Testing & Coverage

*   **Unit Tests:** All code must include comprehensive unit tests covering all critical functions and classes.
*   **Test Coverage:** Aim for at least 80% test coverage using existing test frameworks (e.g., `pytest`).
*   **Test Case Design:**  Tests should be designed to isolate and verify specific aspects of the code's behavior.
*   **Test Data:** Test cases should use realistic and diverse data sets.

## 7. Development Practices

*   **Version Control:** Utilize Git for version control and commit frequently.
*   **Code Review:**  All code changes should be reviewed by another team member before merging.
*   **Documentation:**  Include README files with clear explanations of each file and its purpose.
*   **Error Handling:** Implement robust error handling and logging.
*   **Logging:** Use appropriate logging levels for debugging and monitoring.

## 8. Specific Guidelines for AI Coding Agents

*   **State Management:**  Clearly define and manage agent state effectively.
*   **Prompt Engineering:**  Ensure prompts are well-designed and consistently applied.
*   **Output Validation:**  Implement mechanisms to validate agent outputs.
*   **Error Handling for Failure:**  When an agent fails, provide informative error messages and diagnostic information.


These guidelines are intended to serve as a foundational framework for the AGENTS.md repository.  Continuous refinement and adherence to these principles will contribute to the overall quality and maintainability of the AI coding agent system.  Any deviations should be discussed and approved by the team lead.
```