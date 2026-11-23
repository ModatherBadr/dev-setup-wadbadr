# Setup Notes

## Environment Setup
- Installed VS Code on Windows.
- Enabled `Format On Save` and set Font Size to 15.
- Installed Extensions: Python, GitLens, WSL.
- Set default terminal to WSL.

## Issues & Solutions
- **Issue:** WSL wasn't showing in VS Code terminal dropdown.
  - **Solution:** Manually added WSL to `settings.json` (and fixed a JSON syntax error).
- **Issue:** SQL Exception (CHECK constraint on Role).
  - **Solution:** Ensured the Role passed from C# Enum matches the database allowed values.
- **Issue:** SQL Exception (UNIQUE KEY constraint on Email).
  - **Solution:** Used a different email for testing to avoid duplicate key violation.

## Python Environment
- Installed Python 3.11 via deadsnakes PPA.
- Created virtual environment using `python3.11 -m venv venv`.