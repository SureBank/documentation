# Contribution Guidelines

Thank you for your interest in contributing to SureBank! We encourage contributions that help improve the codebase, add features, and fix bugs. Before you start contributing, please read the following guidelines:

## How to Contribute

1. **Fork the Repository:**
   - Fork the repository to your own GitHub account.
   - Clone the forked repository to your local machine.

2. **Create a Feature Branch:**
   - Create a new branch for each feature or bug fix.
   - Follow the naming convention `feature/<feature-name>` or `bugfix/<issue-number>`.
   
   Example:
   ```bash
   git checkout -b feature/login-system
   ```

3. **Write Clean, Maintainable Code:**
   - Follow [Code Practices](docs/code_practices.md).
   - Ensure your code follows the agreed project structure.
   - Write comments where necessary.

4. **Testing:**
   - Ensure that all code changes are properly tested.
   - Add unit tests for new features.
   - Test your code in both development and staging environments.

5. **Commit Changes:**
   - Write descriptive and concise commit messages.
   - Example: `Add user registration form validation`
   - Avoid unnecessary commits like `fix typo` or `small changes`.

6. **Open a Pull Request:**
   - Push your changes to your branch.
   - Create a Pull Request (PR) to merge into `develop` branch.
   - Add a description of your changes and any related issues.
   - Ensure your PR is small and focused.

7. **PR Review Process:**
   - Your PR will be reviewed by at least one team member.
   - Ensure that the PR is reviewed and approved before merging.
   - Address any comments or requested changes from reviewers.
   
8. **Merge to Develop:**
   - Once approved, the PR will be merged into the `develop` branch.
   - Make sure the code is integrated smoothly with the rest of the project.

9. **No Direct Commits to Develop/Main:**
   - Direct commits to `develop` or `main` are not allowed.
   - All changes must go through the PR review process.
