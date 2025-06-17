
# Contributing to Ludelix Connect

We welcome contributions to Ludelix Connect! To ensure a smooth and collaborative development process, please follow these guidelines.

## How to Contribute

1.  **Fork the Repository:** Start by forking the `ludelix-connect` repository on GitHub.

2.  **Clone Your Fork:** Clone your forked repository to your local machine:

    ```bash
    git clone https://github.com/YOUR_USERNAME/ludelix-connect.git
    cd ludelix-connect
    ```

3.  **Create a New Branch:** Create a new branch for your feature or bug fix. Use a descriptive name:

    ```bash
    git checkout -b feature/your-feature-name
    # or
    git checkout -b bugfix/issue-description
    ```

4.  **Install Dependencies:** Install the project dependencies:

    ```bash
    npm install
    ```

5.  **Make Your Changes:** Implement your feature or fix the bug. Ensure your code adheres to the project's coding style and conventions.

6.  **Run Tests:** Before committing, run the tests to ensure everything is working as expected and that your changes haven't introduced any regressions:

    ```bash
    npm test
    ```

7.  **Write Tests (if applicable):** If you're adding a new feature, please write corresponding tests to cover its functionality. If you're fixing a bug, add a test that reproduces the bug and verifies the fix.

8.  **Lint and Format:** Ensure your code is properly linted and formatted:

    ```bash
    npm run lint
    npm run format
    ```

9.  **Commit Your Changes:** Commit your changes with a clear and concise commit message. Follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification if possible.

    ```bash
    git commit -m "feat: Add new feature"
    # or
    git commit -m "fix: Fix bug in X"
    ```

10. **Push to Your Fork:** Push your changes to your forked repository:

    ```bash
    git push origin feature/your-feature-name
    ```

11. **Create a Pull Request:** Go to the original `ludelix-connect` repository on GitHub and create a new pull request from your forked branch to the `main` branch. Provide a detailed description of your changes.

## Code Style

We use ESLint and Prettier to enforce code style and formatting. Please ensure your code passes linting and formatting checks before submitting a pull request.

## Reporting Bugs

If you find a bug, please open an issue on GitHub. Provide a clear description of the bug, steps to reproduce it, and expected behavior.

## Feature Requests

If you have an idea for a new feature, please open an issue on GitHub to discuss it. This helps ensure that the feature aligns with the project's goals and avoids duplicate efforts.

Thank you for contributing to Ludelix Connect!


