# Chrome Extension Idea: QuoteKeeper

## Authors

Claire Zhao (clairezz)
Ioannis Kalaitzidis (jokala)
Maria Ramos ()
Chaelsey Park (chaelsey)

## Problem Statement

Researchers and professionals often sift through countless web articles and journals, manually copying, organizing, and citing key quotes and evidence. This process is tedious, error-prone, and fragmented across multiple tabs and note apps. QuoteKeeper streamlines web research by letting users highlight text in-page, automatically storing quotes with their source URLs, and later generating an aggregated prompt for an LLM to analyze—all without leaving the browser.

## Target Audience

- Graduate students writing literature reviews

- Academic researchers gathering evidence for papers

- Journalists compiling quotes and sources

- Analysts conducting market or policy research

- Anyone who frequently reads and annotates long-form web content

## Description

QuoteKeeper is a Chrome extension that lets you highlight passages on any web page and instantly saves them (with URL, title, and timestamp) to a project sidebar. When you’ve finished gathering evidence, click “Generate Prompt” to assemble all your quotes into a single LLM-ready request—automatically synthesizing your annotations, summaries, or thematic insights.

## Selling Points

1. **One‑Click  Highlighting**:  Save quotes and their metadata instantly, without switching applications or tab
2. **Organized Sidebar Dashboard**: View, tag, and search all collected highlights grouped by project. 
3. **LLM-Ready Prompt Generation**: Automatically compile your quotes into a structured prompt for ChatGPT or other LLMs.
4. **Local-First & Privacy-Respecting**: All data is stored in your browser; no cloud upload unless you choose to.
5. **Flexible Export Options**: Export highlights and notes as JSON, Markdown, or CSV for seamless integration with other tools.

## User Stories

1. As a graduate student, I want to highlight key sentences on a journal website so that I can save them with source citations for my thesis.
2. As a researcher, I want to tag highlights with custom labels (e.g. “Method,” “Result”) so that I can filter evidence by theme later.
3.As a journalist, I want to compile all my quotes into a single prompt so that an AI can help draft an article outline.
4. As an analyst, I want to search my saved highlights across multiple web domains so that I can quickly find relevant data. 
5. As a thesis advisor, I want my students’ highlights exported in Markdown so that they can embed them directly into their drafts.

## Notes

- **Potential Challenges**: Ensuring robust highlight detection on dynamically loaded pages (e.g. infinite scroll).
- **Alternative Approaches**:  Integrate with browser’s built-in “reading mode” to stabilize text selection.
- **Future Enhancements**: Collaborative “shared project” mode where teams can pool and comment on highlights.

## References & Inspiration

- Chrome Extension `declarativeNetRequest` API docs: https://developer.chrome.com/docs/extensions/reference/declarativeNetRequest/  
- StayFocusd (existing productivity extension)  
- Articles on digital minimalism and focus techniques  
