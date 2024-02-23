# Git Commit Convention

This project follows a structured git commit convention to ensure clarity and consistency in commit messages. Below is the format for writing commit messages:

```bash
<type>(<scope>): <subject>
```

### Type
The type specifies the nature of the commit. It can be one of the following:

- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation changes
- **style**: Changes that do not affect the meaning of the code (e.g., formatting, white-space, etc.)
- **refactor**: Code refactorings
- **test**: Adding or modifying tests
- **chore**: Changes to the build process, auxiliary tools, or project configurations

### Scope
The scope indicates the scope of the commit, such as a module, component, or feature affected by the change.

### Subject
The subject succinctly describes the change being made. It should be clear and concise.

#### Examples:
- `feat(auth): add login functionality`
- `fix(navbar): resolve issue with menu alignment`
- `docs(readme): update project documentation`
- `style(button): adjust button spacing`
- `refactor(api): optimize endpoint handling`
- `test(login): add unit tests for login form`
- `chore(deps): update dependencies`
