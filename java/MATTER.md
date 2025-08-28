# CODE_REVIEW_RULES

## 1. Code Format & Naming
   - Use camelCase for methods and variables
   - Use PascalCase for class names
   - Constants should be UPPER_SNAKE_CASE
   - Package names must be lowercase

## 2. Documentation & Comments
   - All public methods require JavaDoc with @param and @return
   - Complex business logic must have inline comments
   - Class-level JavaDoc required for public classes

## 3. Error Handling
   - Never catch and ignore exceptions without logging
   - Use specific exception types, avoid generic Exception
   - Always close resources using try-with-resources
   - Validate method parameters at entry points

## 4. Code Quality
   - Methods should not exceed 50 lines
   - Classes should follow Single Responsibility Principle
   - Use Optional instead of returning null
   - Prefer composition over inheritance

## 5. Performance & Memory
   - Use StringBuilder for string concatenation in loops
   - Close streams and connections explicitly
   - Avoid creating unnecessary objects in tight loops
   - Use appropriate collection types (ArrayList vs LinkedList)
