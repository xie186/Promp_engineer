# Summarization Prompts

## Summarize a Long Document

**Use case:** Condense a lengthy article, paper, or report into key points.

**Prompt:**
```
Summarize the following document in <target length, e.g., 3 bullet points / 1 paragraph / 200 words>.

Focus on:
- The main argument or purpose
- Key findings or conclusions
- Any recommended actions

Document:
<paste document text here>
```

---

## Extract Action Items from Meeting Notes

**Use case:** Pull out tasks and owners from raw meeting notes.

**Prompt:**
```
Read the following meeting notes and extract all action items.

For each action item, provide:
- Task description
- Owner (if mentioned)
- Due date (if mentioned)

Format the output as a Markdown table.

Meeting notes:
<paste notes here>
```

---

## Summarize a Research Paper

**Use case:** Get a quick overview of an academic paper.

**Prompt:**
```
Summarize the following research paper for someone with a general science background (not an expert in this field).

Include:
1. Research question / objective
2. Methods used
3. Key results
4. Main conclusions and implications
5. Any notable limitations

Paper:
<paste abstract or full text here>
```

---

## Summarize an Email Thread

**Use case:** Quickly understand a long email chain.

**Prompt:**
```
Summarize the following email thread in 3–5 sentences.

Highlight:
- The main topic being discussed
- Any decisions that were made
- Any open questions or next steps

Email thread:
<paste email thread here>
```

---

## Compare Multiple Sources

**Use case:** Identify agreements and disagreements across several documents.

**Prompt:**
```
I have <N> documents on the topic of <topic>. Compare them and produce a structured summary that covers:

1. Points all sources agree on
2. Points where sources differ (note which source says what)
3. Gaps – important aspects of the topic not addressed by any source

Documents:
--- Document 1 ---
<text>

--- Document 2 ---
<text>

--- Document 3 ---
<text>
```
