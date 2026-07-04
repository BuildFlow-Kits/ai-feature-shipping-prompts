# AI Feature Shipping Prompts

Free AI coding prompts for developers using ChatGPT, Claude, Cursor, and Copilot to plan, build, test, debug, and ship features faster.

Most developers do not need more random AI prompts.

They need a repeatable workflow:

```text
clarify → plan → build → test → debug → refactor
```

This repo is a free sample from **BuildFlow Kits**, a digital product brand creating practical AI workflow kits, templates, and systems for developers, freelancers, and creators.

---

## What’s included

### 1. Feature Clarifier Prompt

Use this before asking AI to write code.

```text
Act as a senior full-stack developer.

Before writing any code, ask clarifying questions about this feature.

Ask about:
- user flow
- expected behavior
- edge cases
- data requirements
- API or database changes
- security concerns
- error states
- tests needed

Do not write code yet.

Feature:
[describe your feature here]
```

---

### 2. Implementation Planner Prompt

Use this after the feature is clear.

```text
Based on the clarified requirements, create a step-by-step implementation plan.

Include:
- files that may need to change
- new functions, components, or modules needed
- database or API changes
- possible risks
- edge cases
- tests that should be written

Do not write the full code yet.
```

---

### 3. Edge Case Finder Prompt

Use this before building the feature.

```text
Analyze this feature and list possible edge cases.

Group them by:
- user input issues
- permission/access issues
- empty or missing data
- API/database failures
- performance concerns
- security risks
- UI/UX confusion

For each edge case, suggest how it should be handled.
```

---

### 4. Debugging Assistant Prompt

Use this when something breaks.

```text
Act as a debugging assistant.

Analyze this error step by step.

First:
- explain the most likely causes
- list what information is needed to confirm the issue
- suggest the safest fix
- warn about changes that may create new bugs

Do not rewrite unrelated code.

Error/context:
[paste error and relevant code here]
```

---

### 5. Test Generator Prompt

Use this after implementation.

```text
Generate test cases for this feature.

Cover:
- normal successful flow
- invalid input
- missing data
- permission issues
- edge cases
- failure cases

For each test, explain:
- what it verifies
- why it matters
- expected result
```

---

## Recommended AI coding workflow

```text
1. Clarify the feature
2. Plan the implementation
3. Identify edge cases
4. Build one part at a time
5. Generate tests
6. Debug carefully
7. Review and refactor
```

---

## Full prompt pack

This is the free sample.

Get the complete AI Coding Prompt Pack for Developers here:

https://samuelhany.gumroad.com/l/ship-features-faster-prompts

---

## About BuildFlow Kits

BuildFlow Kits creates practical AI workflow kits, templates, and digital systems for developers, freelancers, and creators.

The goal is simple:

**Ship faster. Work cleaner. Stop starting from scratch.**

---

## Disclaimer

AI-generated code should always be reviewed, tested, and adapted to your project. These prompts are workflow tools, not a guarantee of bug-free code.
