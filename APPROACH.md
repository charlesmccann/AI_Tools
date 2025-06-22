# Development Guidelines
Concise principles for maintainable, AI-assisted development

## Core Principles
1. Documentation First
Document key decisions before implementation
Keep docs versioned with code
Focus on "why" not just "what"

2. Clean Architecture
Business logic independent of frameworks
Testable, modular components
Minimal, well-defined dependencies

3. AI Collaboration
Generate small, focused changes
Document all AI-generated code
Follow existing patterns

## Project Structure
### Documentation
`/docs/` - General documentation, overview, and system architecture
`/docs/systems/` - System documentation (usually by feature)

### Code Organization
Group by feature/domain
Keep files focused (<500 lines)
Follow language conventions

## Mermaid Diagrams

Use Class and Sequence Mermaid documentation for simple, maintainable diagrams. Keep them focused and avoid unnecessary complexity.

### Best Practices
Use simple, clear node names
Group related components
Keep diagrams focused on one aspect
Update when architecture changes

## Development Workflow

1. Plan
Document requirements
Document Design based on Good Design Patterns, Reuse, and Existing systems
Review approach

2. Implement
Make small, focused changes
Document as you go

3. Review
Verify and Ensure consistency

## AI Guidelines
### Effective Prompts
```
Context: [File/Component]
Task: [Specific change]
Requirements:
- [Clear criteria]
- [Examples if needed]
Related: [References]
```

### Debugging Methodology

### Logging Strategy
Use configurable log levels
Support structured logging for machine processing
Enable/disable logging per module/component
Log rotation
Prevent loops from overlogging

### Debug Tools
Implement system status overlay (Example: F1 for debug menu for applications)
Support runtime configuration changes

## Documentation Standards
### System Documentation
Document architecture decisions (ADRs)
Keep API documentation current
Include sequence diagrams for complex flows
Maintain data dictionary

### Code Documentation
Document public interfaces
Explain "why" not just "what"
Keep examples minimal but relevant
Use consistent formatting

## Code Review
Follows project patterns
Includes documentation
Handles errors gracefully
Performance considered
Security reviewed