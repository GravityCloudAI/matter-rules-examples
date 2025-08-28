# CODE_REVIEW_RULES

## 1. Code Format & Style
   - Use camelCase for variables and functions
   - Use PascalCase for constructors and classes
   - Use const for immutable values, let for variables
   - Prefer arrow functions for callbacks and short functions

## 2. Modern JavaScript Patterns
   - Use destructuring for object/array extraction
   - Prefer template literals over string concatenation
   - Use optional chaining (?.) for safe property access
   - Use nullish coalescing (??) for default values

## 3. Async Operations
   - Prefer async/await over .then() chains
   - Always handle promise rejections with try/catch
   - Use Promise.all() for parallel async operations
   - Avoid mixing async/await with .then()

## 4. Error Handling
   - Validate function parameters at entry
   - Use meaningful error messages
   - Handle edge cases (null, undefined, empty arrays)
   - Log errors with sufficient context

## 5. Performance & Memory
   - Avoid creating functions inside render loops
   - Use array methods (map, filter, reduce) appropriately
   - Clean up event listeners and timers
   - Minimize DOM manipulation in loops
