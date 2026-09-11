---
name: clean-markdown
description: Formats markdown output strictly for clean copy-pasting into Google Docs, wikis, and standard CommonMark/GFM parsers without terminal artifacts.
---

# Clean Markdown Output Instructions

When generating or formatting Markdown content intended for copying into document editors (like Google Docs):

1. **Table Integrity**:
   - Every table row MUST be on a single physical line.
   - Do NOT wrap cell contents across multiple lines.
   - If line breaks are needed inside a cell, use `<br>`.
   - Use standard header dividers (`|---|---|`).

2. **No Terminal Escapes**:
   - Never prefix headings with backslashes (use `### Heading`, not `\### Heading`).
   - Do not escape common Markdown characters (`#`, `*`, `_`, `|`) unless specifically requested.

3. **Standard Horizontal Dividers**:
   - Use three hyphens (`---`) instead of Unicode box-drawing characters (`──────`).

4. **Lists and Indentation**:
   - Use `- ` or `* ` for unordered list items instead of Unicode bullet points (`•`).
   - Avoid unintentional leading whitespace before headings or tables so they are not parsed as code blocks.

