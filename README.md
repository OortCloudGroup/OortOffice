<div align="center">

# OortOffice

**The whole Office suite on your desktop, with an AI assistant right in the sidebar.**

Word Processing · Spreadsheets · Presentations · PDF · AI Summary / Polish / Formatting

[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-2f6fdb?style=flat-square)](#system-requirements)
[![Version](https://img.shields.io/badge/version-1.0.0-1a9c6b?style=flat-square)](#roadmap)
[![AI](https://img.shields.io/badge/AI-OortCloud-6b4de0?style=flat-square)](#ai-smart-summary)
[![License](https://img.shields.io/badge/license-Proprietary-d97706?style=flat-square)](#license)

[Highlights](#highlights) · [Preview](#preview) · [Feature List](#feature-list) · [AI Smart Summary](#ai-smart-summary) · [Quick Start](#quick-start) · [Roadmap](#roadmap)

English | [简体中文](./README.zh-CN.md)

</div>

---

## Highlights

OortOffice is a native desktop office suite that brings **all the everyday features** of Word, Excel, PowerPoint and PDF into a single application: one ribbon, one file manager, one set of keyboard shortcuts. Documents can be copy-pasted and cross-referenced freely, with no more jumping between windows.

On top of the complete office experience, OortOffice adds the **OortCloud AI assistant**, whose flagship capability is **AI Smart Summary** — ask it "summarize the main content and key points of this document" in the sidebar, and the AI reads the currently open document, organizes the result into a hierarchical structured summary, and displays it right beside the text for side-by-side reading.

- **One app, four document types**: text, spreadsheet, presentation and PDF share the same UI and the same account system.
- **The full classic ribbon**: File / Home / Insert / Draw / Design / Layout / References / Review / View, aligned item by item with Office habits.
- **AI right next to your document**: summary, polishing, formatting and Q&A all happen in the sidebar — no jumping, no copy-pasting.
- **Track Changes**: every AI edit can enter revision mode first, and is only accepted after human confirmation.
- **Auto-save + cloud collaboration**: written to disk in real time locally, synced automatically after sign-in, with multi-user simultaneous editing.

---

## Preview

![OortOffice desktop UI: document editing area with the OortCloud AI summary sidebar](assets/oortoffice-ui-preview.png)

> On the left is the **OortCloud** sidebar: after you type your request, the AI summarizes the currently open `论坛问题.docx` and outputs results layered by categories such as "Feature Defects" and "Feature Removal & Simplification", tagging each item with its position in the source text (e.g. "Block 0", "Block 4", "Block 13") so you can click through to the matching paragraph. On the right is the standard document editing area, whose top ribbon provides three entries: AI Summary, AI Polish and AI Formatting.

---

## Feature List

### Word Processing (Word equivalent)

- Rich text editing: font, size, bold / italic / underline, strikethrough, superscript and subscript, font color and highlighting.
- Paragraph layout: multi-level bullets and numbering, indentation, line and paragraph spacing, Chinese typography conventions, first-line indent.
- Style system: built-in heading / body styles, a **Styles Pane** for visual style editing, and one-click application across the whole document.
- Page capabilities: pagination and sections, headers and footers, page numbers, columns, page borders and watermarks, ruler and print preview.
- Referencing: automatic table of contents, footnotes and endnotes, captions and cross-references, bibliography and citation management.
- Review: **Track Changes**, comments, accept / reject revisions, document compare and merge, restrict editing.
- Tables and graphics: cell merge and split, table styles, mixed layout of images / shapes / SmartArt / charts / text boxes, wrapping and alignment.
- Find and replace: wildcards, regular expressions and format-based search.

### Spreadsheets (Excel equivalent)

- Virtual scrolling grid at ten-million-row scale, freeze panes, grouping and outlining, multiple worksheets and cross-sheet references.
- Complete function library: math and statistics, text, date and time, lookup and reference, logical, financial and engineering functions.
- Data capabilities: sort and filter, conditional formatting, data validation, text to columns, remove duplicates.
- Pivot tables and pivot charts, sparklines, linked PivotChart.
- Full chart family: column / line / pie / bar / area / scatter / radar / combo charts, with fine-grained control over styles and data labels.
- Formula bar, Name Manager, iterative calculation, what-if analysis and Goal Seek.

### Presentations (PowerPoint equivalent)

- Slide masters and layouts, section management, drag-and-drop thumbnail ordering.
- Layout-aware formatting suggestions, snap-to-align and smart guides, Selection Pane and layer management.
- Transitions, animation timeline, custom shows and rehearsal timing.
- Presenter View, speaker notes, laser pointer and ink annotations.

### PDF and General Capabilities

- PDF reading, annotation, bookmarks, page management (split / merge / rotate / rearrange).
- Conversion between Office documents and PDF, plus OCR text recognition for scans.
- Version history and timeline rollback, auto-save and crash recovery.
- Multi-tab workspace: open several documents side by side in one window, and drag a tab out into a new window.

---

## AI Smart Summary

This is the flagship new feature of OortOffice 1.0: **hand "read it once, then summarize it" over to the AI in the sidebar.**

### How to use

1. Open any document (Word / PDF / spreadsheet / presentation all work).
2. Type your question directly in the OortCloud input box on the left, for example:
   - `Summarize the main content and key points of this document`
   - `Organize this test feedback into Bug / Optimization categories`
   - `List all the to-do items and owners in the document`
3. Results stream into the sidebar while the document stays visible, so you can read the summary against the source as you go.
4. Every conclusion carries a source locator — click it to jump to the matching paragraph, so you never end up with "what the AI said and what I'm reading are not the same thing."

### Capability boundaries

| Capability | Description |
| --- | --- |
| Long-document comprehension | Breaks past the single-turn context limit; over-long documents are summarized in segments, then merged and deduplicated |
| Structured output | Automatically detects document structure and outputs hierarchical headings plus bullet lists, instead of one big blob of text |
| Traceable to source | Conclusions carry paragraph locators, so you can jump back and verify item by item |
| Multi-turn follow-up | Ask deeper questions based on what has already been summarized — no need to re-upload the document |
| Format agnostic | Word, PDF, spreadsheets, presentations and scanned files are all handled uniformly |

### Other AI capabilities in the same sidebar

- **AI Polish**: rewrite the selected paragraph with style instructions such as "more formal / more concise / more conversational / government & enterprise official".
- **AI Formatting**: normalize heading levels, paragraph spacing, numbering schemes and whole-document style consistency in one click.
- **AI Q&A and drafting**: describe the edit or the writing you need in the input box, and content is generated right at the cursor.
- **Track Changes**: with "Track Changes" enabled, all AI modifications are marked as revisions and can be accepted or rejected one by one.
- **Selectable models**: switch models from the right side of the input box (`gpt-5.4` in the screenshot), choosing per task size.

---

## Quick Start

### Download and install

Go to [Releases](../../releases/latest) and download the installer for your platform:

| Platform | Installer |
| --- | --- |
| Windows 10/11 x64 | `OortOffice-1.0.0-win-x64.exe` |
| macOS 12+ (Apple Silicon / Intel) | `OortOffice-1.0.0-mac-universal.dmg` |
| Linux x64 (deb / AppImage) | `OortOffice-1.0.0-linux-x64.deb` |

### Build from source

```bash
# Requirements: Node.js >= 20, pnpm >= 9, Rust >= 1.78
git clone https://gitcode.com/OortCloudGroup/OortOffice.git
cd oortoffice
pnpm install
pnpm build            # build the frontend and document cores
pnpm tauri build      # package the desktop installers
pnpm dev              # dev mode with hot reload
```

Common scripts:

```bash
pnpm test             # unit tests and format-compatibility cases
pnpm lint             # code style checks
pnpm docs:preview     # preview this README and the product docs locally
```

### System requirements

- **Windows**: Windows 10 1809 or later, 4 GB RAM minimum, 8 GB recommended.
- **macOS**: macOS 12 Monterey or later.
- **Linux**: mainstream distributions with glibc 2.31 or later; common Chinese fonts required.
- Using AI features requires signing in to an OortCloud account; purely offline editing does not depend on the network.

---

## Common Shortcuts

| Action | Shortcut |
| --- | --- |
| New / Open / Save | `Ctrl+N` / `Ctrl+O` / `Ctrl+S` |
| Find / Replace | `Ctrl+F` / `Ctrl+H` |
| Open AI sidebar | `Ctrl+Shift+A` |
| Summarize current document | `Ctrl+Shift+S` |
| Toggle Track Changes | `Ctrl+Shift+E` |
| Undo / Redo | `Ctrl+Z` / `Ctrl+Y` |

> On macOS, replace `Ctrl` with `Cmd`.

---

## Technical Architecture

```
oortoffice/
├── apps/
│   ├── desktop/          # Tauri desktop shell: windows, tabs, file associations, auto-update
│   └── cloud/            # Accounts, sync, collaboration and AI gateway
├── packages/
│   ├── doc-core/         # Text layout engine: pagination, line breaking, style inheritance
│   ├── sheet-core/       # Spreadsheet engine: formula parsing, dependency graph, incremental recalculation
│   ├── slide-core/       # Presentation engine: masters, timeline, rendering
│   ├── pdf-core/         # PDF parsing, rendering and OCR
│   ├── ui-ribbon/        # Ribbon, styles pane, multi-tab workspace
│   └── ai-agent/         # OortCloud assistant: chunking, retrieval, structured summary, revision generation
└── assets/               # Icons, templates and document imagery
```

- The document cores are decoupled from the UI layer, so the same core runs on both desktop and web.
- Editing is built entirely on incremental operations (OT/CRDT): local-first persistence, incremental sync once online.
- AI changes enter the document model as first-class "revision records", which makes undo, rejection and version rollback work naturally.

---

## Roadmap

- [x] **1.0** Desktop release: full-featured text / spreadsheet / presentation / PDF, plus AI summary, polish, formatting and Track Changes
- [ ] **1.1** Mobile reading and light editing, batch AI processing across multiple documents
- [ ] **1.2** AI generation for spreadsheets and presentations (natural language to a table or a first PPT draft)
- [ ] **1.3** Team knowledge base: cross-document retrieval Q&A, summaries that cite external sources
- [ ] **2.0** Plugin marketplace and open APIs

---

## Contributing

Issues and pull requests are welcome. Please read `CONTRIBUTING.md` before you start, and make sure that:

1. New features come with test cases;
2. Changes touching document formats pass the format-compatibility cases;
3. Commit messages follow the Conventional Commits specification.

## License

Copyright © 2026 OortCloud. All rights reserved.

This repository is the product page for OortOffice. The product code is closed-source commercial software; see `LICENSE` for the specific terms.

<div align="center">

**[⬆ Back to top](#oortoffice)**

</div>