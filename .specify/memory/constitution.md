<!--
Sync Impact Report:
Version change: N/A (initial version) → 1.0.0
Added sections: Core Principles (6), Additional Constraints, Development Workflow, Governance
Templates requiring updates: N/A (initial creation)
Follow-up TODOs: None
-->

# AI with Embedded Systems: From Fundamentals to Real-World Edge Intelligence Constitution

## Core Principles

### Progressive Learning
All content must follow a beginner-to-advanced learning progression; Each chapter must build on previous concepts without assuming prior knowledge; Complexity increases gradually and intentionally throughout the book.

### Practical-First Approach
Every concept must be reinforced through code and hardware examples; All programming concepts must relate to physical hardware behavior; Theory is only included when directly applicable to embedded implementation.

### Hardware-Aware AI
All AI concepts must be constrained by real embedded limitations; Examples must be reproducible on commonly available hardware; Abstractions must not hide critical embedded constraints.

### Conceptual Clarity Before Optimization
Concepts must be introduced before implementation; Understanding takes priority over performance; Optimization is introduced only after foundational concepts are established.

### Real-World Relevance
All examples must align with industrial and production practices; Content must focus on practical applications rather than theoretical concepts; Use cases must reflect actual embedded AI system implementations.

### Self-Contained Accessibility
The book must remain self-contained and beginner-accessible; No assumption of prior AI or embedded systems expertise; Content must prioritize accessibility and affordability of required hardware.

## Additional Constraints

### Technology Requirements
- Mandatory platforms: Arduino, Raspberry Pi, ESP32 or equivalent
- Programming languages: Python for AI/edge programming, C/C++ for microcontroller programming
- Open-source AI frameworks suitable for edge deployment
- Vendor-neutral content where possible

### Exclusions
- No proprietary or closed-source toolchains as core dependencies
- No cloud-only AI workflows without edge alternatives
- No purely theoretical chapters without practical relevance

### Hardware Selection
- Prioritize accessibility and affordability of hardware
- Cloud dependencies must be optional, not mandatory
- Examples must work on commonly available development boards

## Development Workflow

### Content Creation Standards
- Each chapter must introduce concepts before implementation
- All programming concepts must relate to physical hardware behavior
- Examples must be reproducible on commonly available hardware
- Abstractions must not hide critical embedded constraints
- Complexity must increase gradually and intentionally

### Quality Gates
- All code examples must be tested on actual hardware
- Chapters must support the complete beginner-to-advanced learning journey
- Content must enable readers to build real embedded AI systems
- Examples must be validated for reproducibility

### Structure Requirements
- The book consists of 27 chapters across 8 major parts as specified
- Parts 1-7 focus on technical content, Part 8 on deployment and career guidance
- Content must remain stable throughout the writing process to prevent scope creep

## Governance

This constitution defines the immutable scope, structure, and governing principles for the technical book "AI with Embedded Systems: From Fundamentals to Real-World Edge Intelligence". All content creation, chapter development, and example implementations must comply with these principles. Amendments require explicit documentation of changes, approval from project stakeholders, and a migration plan for existing content. All reviews must verify compliance with these principles before accepting changes.

**Version**: 1.0.0 | **Ratified**: 2025-12-25 | **Last Amended**: 2025-12-25