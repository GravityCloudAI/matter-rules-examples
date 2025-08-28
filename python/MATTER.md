# CODE_REVIEW_RULES

## 1. Code Format & Style (PEP 8)
   - Use snake_case for functions and variables
   - Use PascalCase for class names
   - Maximum line length of 88 characters
   - Use 4 spaces for indentation

## 2. Type Hints & Documentation
   - Add type hints for all public functions
   - Use docstrings for modules, classes, and functions
   - Follow Google or NumPy docstring format
   - Include type hints for complex data structures

## 3. Error Handling
   - Use specific exception types, avoid bare except
   - Implement proper exception hierarchies
   - Use context managers (with statements) for resources
   - Log exceptions with traceback information

## 4. Python Idioms
   - Use list/dict comprehensions when appropriate
   - Prefer enumerate() over range(len())
   - Use pathlib for file system operations
   - Follow EAFP (Easier to Ask for Forgiveness than Permission)

## 5. Performance & Best Practices
   - Use generators for large datasets
   - Avoid premature optimization
   - Use dataclasses or pydantic for structured data
   - Implement __str__ and __repr__ for custom classes
