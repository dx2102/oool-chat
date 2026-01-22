# OoolChat

### Try the app online: https://dx2102.github.io/ooolchat/

This is a simple web app to call LLM APIs. 

It aims to create a clean and fast UI baseline, while remaining a single HTML file.

Simply paste the code into LLMs to safety-check/customize it.

Main Goals:
- Concise, single-file code
- Easy to customize with LLMs or check for safety
- Design:
  - Consistent layout and color (tailwind)
  - Readable, high-contrast text

---

Todos:

## 1. Basics
- [x] Streaming output
- [x] Multi-line input bar

## 2. Better Markdown
- [x] Markdown rendering (markdown-it)
- [x] Code highlighting (highlight.js)
- [x] Math rendering (katex)
- [x] Store chat history locally (IndexedDB)

## 3. Better Utilities
- [x] Search bar
- [ ] Improved search
- [ ] Resize / Hide sidebar

## 4. Even Better Utilities
- [x] Fast CDN loading/caching
- [x] Auto-scrolling (disabled by default)
- [ ] Auto-focus
- [ ] Stop Generation
- [ ] Memorize scrolling position

## 5. Even Better Markdown
- [x] Copy button
- [ ] Correct LaTeX Copying
- [ ] Support the checklist syntax
- [x] Skip CJK "Enter" button in input box 
- [ ] Fix CJK characters bolding in markdown

## 6. Chat management
- [ ] Edit message
- [ ] Branching
- [ ] Allow parallel generation

## 7. Settings / Customization
- [x] Change API Keys
- [ ] Manage models (api keys, base url, system prompts, temperature, top_p, max_tokens)
- [ ] Manage appearance (font, color, darkmode preset)
- [ ] Shortcut keys

## 8. Advanced usage
- [ ] List and jump to messages
- [ ] Metadata (pricing, token count)
- [ ] Image uploads
- [ ] Show thinking trace
- [ ] Code Execution / Artifacts (WebAssembly)
