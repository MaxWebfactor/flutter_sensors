# OpenCode.md

## Build/Lint/Test Commands
- **Build the project**: `flutter build`
- **Run tests**: `flutter test`
- **Run a single test**: `flutter test test/widget_test.dart`
- **Linting**: `flutter analyze`

## Code Style Guidelines
- **Imports**: Group imports into Dart standard, package imports, and project imports.
- **Formatting**: Follow Dart's style guidelines; ensure consistent indentation and line breaks.
- **Types**: Use explicit types for variables and function return types.
- **Naming Conventions**: Use camelCase for variables and methods, PascalCase for classes.
- **Error Handling**: Prefer the use of exceptions over return values for error reporting. Use try-catch blocks where appropriate.
- **Documentation**: Provide comments for public APIs and complex logic.

## Additional Rules
- Ensure compliance with existing coding rules in `.cursor/rules/` or `.github/copilot-instructions.md` if present, for future agent use.