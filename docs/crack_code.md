



## 🧠 Prompt: Build the Mental Model First

```
You are a senior Rust systems engineer.

I have downloaded an entire Rust repository locally.
I will paste the Cargo.toml and the src directory structure.

Your job:

1) Identify what kind of project this is (CLI, library, web server, async system, data tool, etc.)
2) Explain the likely architecture based on module layout.
3) Identify:
   - Entry point
   - Core modules
   - Data model layer
   - Business logic layer
   - I/O layer
4) Tell me the best reading order of files.
5) Highlight which files are “low value” vs “high value” for understanding the core logic.

Do NOT explain line by line yet.
Focus only on architecture and reading strategy.

Here is Cargo.toml and folder structure:
<PASTE HERE>

```


## 🔍 Step 2 — File-by-File Deep Dive

```
Act as a Rust code mentor.

Explain this file in 3 passes:

PASS 1 – High Level
- What is this file responsible for?
- How does it connect to other modules?
- What problem does it solve?

PASS 2 – Structural Breakdown
- Explain all structs/enums/traits.
- Explain function signatures before bodies.
- Identify ownership/lifetime patterns.
- Identify async/concurrency patterns if any.

PASS 3 – Line-by-Line
Quote small chunks (1–5 lines) and explain what each does.

Track:
- Key symbols introduced
- Important data flow
- Error handling strategy

If something depends on another file, pause and tell me exactly which file to open next.

Here is the file:
<PASTE FILE>
```