# CODE_REVIEW_RULES

## 1. Component Design
   - Use functional components with hooks
   - Keep components small and single-purpose
   - Use PascalCase for component names
   - Prefer composition over inheritance

## 2. Hooks & State Management
   - Use useState for simple local state
   - Use useEffect with proper dependency arrays
   - Use useCallback/useMemo for expensive computations
   - Clean up effects with return functions

## 3. Props & TypeScript
   - Define interfaces for all component props
   - Use optional props with default values
   - Destructure props at component entry
   - Validate prop types in development

## 4. Performance Optimization
   - Avoid creating objects/functions in render
   - Use React.memo for expensive re-renders
   - Implement proper key props for lists
   - Use lazy loading for large components

## 5. Testing & Accessibility
   - Write tests for component behavior, not implementation
   - Include proper ARIA labels and roles
   - Ensure keyboard navigation support
   - Test with screen readers and accessibility tools
