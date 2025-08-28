# CODE_REVIEW_RULES

## 1. Code Format & Naming
   - Use camelCase for functions and properties
   - Use PascalCase for class names
   - Use lowercase with underscores for package names
   - Prefer val over var when possible

## 2. Null Safety & Types
   - Use nullable types (?) only when necessary
   - Prefer safe calls (?.) over explicit null checks
   - Use elvis operator (?:) for default values
   - Avoid !! operator unless absolutely certain

## 3. Function Design
   - Use single-expression functions when appropriate
   - Prefer extension functions over utility classes
   - Use default parameters instead of function overloading
   - Document public APIs with KDoc

## 4. Kotlin Idioms
   - Use data classes for simple data holders
   - Prefer sealed classes for restricted hierarchies
   - Use when expressions instead of multiple if-else
   - Leverage scope functions (let, run, with, apply, also)

## 5. Coroutines & Async
   - Always use structured concurrency
   - Handle coroutine exceptions properly
   - Use appropriate dispatchers (IO, Default, Main)
   - Cancel coroutines to prevent memory leaks
