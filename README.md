# Effective Java Codex Skill

A Codex skill that distills the practical guidance of *Effective Java* into a reusable review and refactoring workflow.

It is designed for:

- Java API design
- Code review and refactoring
- Teaching and mentoring
- Mapping code smells to Effective Java principles

This repository contains paraphrased guidance and original workflow design. It does not reproduce the book text.

## Repository Layout

```text
.agents/skills/effective-java/
├── SKILL.md
├── agents/openai.yaml
└── references/
    ├── item-map.md
    └── review-checklist.md
```

## What This Skill Covers

- Object creation, builders, static factories, and dependency injection
- Immutability, equality contracts, and object methods
- Class and interface design
- Generics, enums, and annotations
- Lambdas, streams, and method design
- Exceptions, concurrency, and serialization

## How To Use

### Option 1: Use the repository directly in Codex

If you open this repository in Codex, the skill lives under `.agents/skills/effective-java` and can be discovered from the project.

### Option 2: Install as a personal skill

Copy the skill directory into your personal Codex skills folder:

```bash
mkdir -p ~/.codex/skills
cp -R .agents/skills/effective-java ~/.codex/skills/effective-java
```

Then restart Codex.

## Example Prompts

- `Use $effective-java to review this Java service class.`
- `Use $effective-java to refactor this DTO builder and constructor design.`
- `Use $effective-java to explain which Effective Java items apply to this code.`
- `用 $effective-java 审查这段 Java 代码的 API 设计问题。`
- `用 $effective-java 把这段 Java 重构得更符合 Effective Java。`

## Publishing This Repository

Suggested repository name:

- `effective-java-codex-skill`

Suggested GitHub description:

- `A Codex skill for reviewing and refactoring Java code with Effective Java principles.`

Suggested tags:

- `codex`
- `skill`
- `java`
- `effective-java`
- `code-review`
- `refactoring`

## Notes

- The skill is optimized for practical engineering guidance, not for chapter-by-chapter book summary.
- Recommendations are intentionally context-sensitive: it does not force every constructor into a builder or every loop into a stream.
