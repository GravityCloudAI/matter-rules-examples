# CODE_REVIEW_RULES

## 1. Chart Structure & Organization
   - Use consistent indentation (2 spaces) in YAML
   - Organize templates by resource type
   - Use meaningful file names for templates
   - Include proper Chart.yaml metadata

## 2. Templating & Values
   - Always provide default values in values.yaml
   - Use descriptive comments for complex template logic
   - Validate required values with fail function
   - Quote string values to prevent type conversion issues

## 3. Security & Best Practices
   - Never hardcode secrets in templates
   - Use proper RBAC configurations
   - Set resource limits and requests
   - Include security context specifications

## 4. Configuration Management
   - Use range loops efficiently in templates
   - Implement proper conditionals with if/else
   - Use include/template functions for reusability
   - Separate environment-specific configurations

## 5. Testing & Validation
   - Include chart tests in templates/tests/
   - Validate generated manifests with helm lint
   - Use helm template --debug for troubleshooting
   - Test with different value combinations
