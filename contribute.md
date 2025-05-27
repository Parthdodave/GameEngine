# Contributing to GameEngine

Thank you for considering contributing to **GameEngine**!  
We welcome bug reports, feature requests, code contributions, documentation improvements, and suggestions for better performance or design.

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Development Guidelines](#development-guidelines)
- [Pull Request Process](#pull-request-process)
- [Style Guide](#style-guide)
- [Security](#security)

---

## Code of Conduct

This project follows a [Contributor Covenant](https://www.contributor-covenant.org/) code of conduct.  
Please be respectful and considerate in your communications.

---

## Getting Started

1. **Fork** the repository.
2. **Clone** your fork to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/GameEngine.git
   ```
3. **Create a branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. Install dependencies (CMake, SDL2, etc.) as listed in [`README.md`](./README.md).

---

## Development Guidelines

- All code must build successfully with `CMake` on Linux, Windows, and macOS.
- Write unit tests where applicable (see `/tests` folder).
- Comment complex logic clearly.
- Avoid third-party libraries unless discussed.
- Do not break existing public APIs.

---

## Pull Request Process

1. Open an issue before starting large work (especially new features).
2. Ensure all commits have clear, conventional messages:
   ```
   feat(renderer): add HDR support
   fix(audio): correct spatial sound panning
   refactor(core): simplify event loop
   ```
3. Run tests locally before submitting.
4. Open a pull request with a clear description:
   - What is being changed?
   - Why is the change necessary?
   - Any impact on existing systems?

The PR will be reviewed, and once approved, it will be merged by a maintainer.

---

## Style Guide

### C++ (Engine Core)

- Follow [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
- Indentation: 2 spaces
- Braces on the same line:
  ```cpp
  if (condition) {
    // ...
  }
  ```

### Python (Tools/Scripts)

- Follow [PEP8](https://pep8.org/)
- Use `black` or `autopep8` for formatting

### Lua (Scripting)

- Snake_case for variables
- Avoid global variables

---

## Security

If you find a **security vulnerability**, please **do not** submit a public issue.  
Instead, report it privately to: `your.email@example.com`

---

## Questions?

For general help or discussion:
- Open a [Discussion](https://github.com/yourusername/GameEngine/discussions)
- Or email: `your.email@example.com`

---

Thank you again for contributing to GameEngine!