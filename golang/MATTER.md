# CODE_REVIEW_RULES

## 1. Code Format & Naming
   - Use camelCase for private fields/functions
   - Use PascalCase for exported fields/functions
   - Keep package names short and lowercase
   - Use gofmt/goimports for consistent formatting

## 2. Error Handling
   - Always check and handle errors explicitly
   - Return errors as the last return value
   - Use meaningful error messages with context
   - Wrap errors with additional context using fmt.Errorf

## 3. Interface Design
   - Keep interfaces small and focused
   - Accept interfaces, return concrete types
   - Use empty interface{} sparingly
   - Define interfaces at point of use, not declaration

## 4. Concurrency & Goroutines
   - Use channels for communication between goroutines
   - Always handle channel closing and context cancellation
   - Use sync.WaitGroup or context for goroutine coordination
   - Avoid shared memory, prefer message passing

## 5. Performance & Memory
   - Use defer for cleanup operations
   - Pre-allocate slices with known capacity
   - Use sync.Pool for frequently allocated objects
   - Profile code before optimizing
