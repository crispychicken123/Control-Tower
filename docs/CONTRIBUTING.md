# Contributing Guidelines

## Code Standards

### 1. Naming Conventions

- **Components**: PascalCase (`UserProfile.tsx`)
- **Functions**: camelCase (`getUserData()`)
- **Constants**: UPPER_SNAKE_CASE (`MAX_RETRIES = 3`)
- **Files**: kebab-case for utilities (`user-helper.ts`)

### 2. Git Workflow

```bash
# Create a feature branch
git checkout -b feature/feature-name

# Make your changes
git add .
git commit -m "feat: add new feature"

# Push and create PR
git push origin feature/feature-name
```

### 3. Commit Messages

Use conventional commits:
- `feat:` - New feature
- `fix:` - Bug fix
- `docs:` - Documentation
- `style:` - Code style (formatting, etc)
- `refactor:` - Code refactoring
- `test:` - Adding tests
- `chore:` - Dependency updates

Example:
```bash
git commit -m "feat: add user authentication"
```

### 4. Code Review Checklist

- [ ] Code follows project style guide
- [ ] All tests pass
- [ ] No unnecessary console logs
- [ ] Comments added for complex logic
- [ ] Documentation updated if needed
- [ ] No breaking changes

## Development Process

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests and linter
5. Submit a pull request
6. Wait for review and approval

## Questions?

Feel free to open an issue for questions or discussions.
