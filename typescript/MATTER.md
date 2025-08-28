# CODE_REVIEW_RULES

## 1. Type Safety
   - Always define return types for public functions
   - Use interfaces for object shapes and contracts
   - Prefer unknown over any for better type safety
   - Use type guards for runtime type checking

## 2. Interface & Type Design
   - Use readonly for immutable properties
   - Prefer union types over enums when appropriate
   - Define strict types for API responses
   - Use generic types for reusable components

## 3. Code Organization
   - Export types and interfaces from dedicated files
   - Use barrel exports (index.ts) for clean imports
   - Organize imports: external, internal, types
   - Use path mapping for cleaner import paths

## 4. Error Handling & Validation
   - Use discriminated unions for error states
   - Validate external data with type predicates
   - Handle async operations with proper error types
   - Use Result/Either patterns for error handling

## 5. Advanced TypeScript
   - Use utility types (Partial, Pick, Omit) appropriately
   - Implement proper generic constraints
   - Use const assertions for literal types
   - Ensure exhaustive checking in switch statements
