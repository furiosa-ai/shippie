// Additional custom rules

- **Company Style Guide:** Follow our company style guide available at [internal
  link]. All new code must adhere to these standards.
- **Documentation:** Every exported function, class, or interface must have
  JSDoc style comments.
- **Error Handling:** All async functions must implement proper error handling
  with try/catch blocks.
- **Security:** No sensitive information (API keys, passwords, tokens) should be
  committed, even in comments or example code.
- **Performance:** Consider O(n) complexity for all operations. Avoid nested
  loops where possible.
- **Naming Conventions:**
  - Use camelCase for variables and functions
  - Use PascalCase for class names and interfaces
  - Use UPPER_SNAKE_CASE for constants
- **Testing:** All new functionality must have corresponding unit tests with at
  least 80% coverage.
- **Dependencies:** Avoid adding new dependencies unless absolutely necessary.
  Prefer native solutions.
