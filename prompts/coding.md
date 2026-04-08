# Coding Prompts

## Generate a Function

**Use case:** Ask an LLM to write a new function from a plain-English description.

**Prompt:**
```
Write a <language> function named `<function_name>` that <description of what it should do>.

Requirements:
- <requirement 1>
- <requirement 2>

Include docstrings/comments and a short usage example.
```

---

## Code Review

**Use case:** Get actionable feedback on an existing piece of code.

**Prompt:**
```
Review the following <language> code and provide feedback on:
1. Correctness – are there any bugs or edge cases not handled?
2. Readability – is the code easy to understand?
3. Performance – are there any obvious bottlenecks?
4. Security – are there any vulnerabilities?

Code:
```<language>
<paste your code here>
```

Summarize your findings and suggest specific improvements.
```

---

## Debug an Error

**Use case:** Diagnose and fix a specific error message.

**Prompt:**
```
I am getting the following error when running my <language> code:

Error:
<paste error message and stack trace>

Relevant code:
```<language>
<paste relevant code>
```

Explain what is causing the error and provide a corrected version of the code.
```

---

## Write Unit Tests

**Use case:** Generate tests for an existing function.

**Prompt:**
```
Write unit tests for the following <language> function using <testing framework, e.g., pytest / Jest / JUnit>.

Function:
```<language>
<paste function here>
```

Cover normal cases, edge cases, and any expected exceptions.
```

---

## Add Documentation

**Use case:** Generate docstrings or API documentation for existing code.

**Prompt:**
```
Add <docstring style, e.g., Google-style docstrings / JSDoc comments> to every function and class in the following <language> code. Do not change any logic.

Code:
```<language>
<paste your code here>
```
```
