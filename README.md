# OoolChat

This is a webpage to call LLM APIs. 

It provides a clean, fast, and simple baseline for LLM chat interfaces/GUI.

All the code is in a single html file. 

Simply paste the code into LLMs to check/customize it.

Goals:
- Concise, single-file code
- Easy to customize with LLMs or check for safety
- Design:
  - Consistent layout and color (tailwind)
  - Readable, high-contrast text

---

More goals (Done):
- Streaming output
- Stop Generation
- Multi-line input bar
- Store chat history locally (IndexedDB)
- Search bar
- Markdown rendering (markdown-it)
- Code highlighting (highlight.js)
- Math rendering (katex)
- Fast CDN loading/caching
- Copy button

---

Future goals:
- Auto-focus
- Fix CJK characters in markdown
- Edit message / Branching
- List and jump to messages
- Change API Keys
- Multiple APIs
- Presets (system prompts, `temperature`, `top_p`, `max_tokens`)

- Metadata (pricing, token count)
- Dark Mode
- Image uploads
- Code Execution / Artifacts (WebAssembly)
