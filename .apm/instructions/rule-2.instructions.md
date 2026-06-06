---
description: TypeScript code quality and type safety standards
applyTo: "**/*.ts"
---

# TypeScript Best Practices

- Enable strict mode in tsconfig.json
- Avoid using `any` type; use `unknown` and type narrowing instead
- Define explicit return types for functions
- Use const assertions for literal types where appropriate
- Prefer interfaces for object types and public APIs
- Use union types for flexible parameter handling
- Keep type definitions close to usage
- Document complex types with JSDoc comments
