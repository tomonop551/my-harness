---
name: writing-tech-blog
description: Advanced strategies and technical writing principles for creating high-impact technical blog posts in 2026. Use this skill to plan, structure, and optimize technical content for deep learning, community engagement, and AI-driven search (AEO/GEO).
---

# Technical Blogging: Advanced Skillset & Strategies

This skill provides a comprehensive framework for technical writing, architecture visualization, and content distribution optimized for the 2026 technical landscape.

## 1. Foundational Habits & Cognitive Strategy
Technical blogging is a mechanism for deep learning (Learning by Teaching).

- **Friction Removal:** Optimize your environment. Pin docs, bookmark tools, and outline your next day's task at the end of a session to avoid "Analysis Paralysis."
- **Code Review Mindset:** Review your prose and code with the same critical eye you use for others' pull requests.
- **Why vs. How:** Focus on the "Why" (rationale) as much as the "How" (implementation).

## 2. Topic Selection & Audience Resolution
Avoid the "Curse of Knowledge"—don't assume the reader knows what is obvious to you.

- **Ultimate Persona:** Write for your "past self" (who struggled with the problem) or your "future self" (who will forget the solution).
- **Content Gaps:** Identify and fill voids in the community (e.g., niche migration guides, RFC-style deep dives).
- **Passion/Urgency Matrix:** Select topics based on high urgency (immediate problem solved) or high passion (deep technical interest).

## 3. Structural Design (The SDS Method)
Readers "scan" before they read. Use a conclusion-first approach.

- **Summary (S):** State the topic and conclusion immediately. Hook the reader.
- **Details (D):** Provide step-by-step procedures, architecture diagrams, and code snippets.
- **Summary/Reason (S):** Reiterate the conclusion and explain the technical/business rationale.

### Standard Outlines
- **How-to:** Intro (Problem) -> Numbered Steps -> Conclusion (Reflection/CTA).
- **Explainer:** Intro (Significance) -> Concept Sections (Definition/Example) -> Conclusion (Future Outlook).
- **Listicle:** Intro (Facts) -> Numbered List (Independent items) -> Conclusion (Insight/CTA).

## 4. Technical Writing Principles (Google Style)
- **One Idea per Sentence:** Keep sentences short and focused.
- **Active Voice:** Clearly state who/what performs the action.
- **Paragraph Focus:** Use a strong "Topic Sentence" at the start of each paragraph.
- **SDS Flow:** Ensure every section follows the Summary-Details-Summary logic.

## 5. Visual Communication & C4 Model
Abstract processes must be visualized to reduce cognitive load.

- **C4 Model Levels:**
  - **L1 (Context):** System scope and external actors.
  - **L2 (Container):** Major components (Web App, DB, Microservices).
  - **L3 (Component):** Internal responsibilities (Service layers, Controllers).
- **Diagram-as-Code:** Prefer **Mermaid.js** (AI-friendly, text-based) or **PlantUML** for structured diagrams. Use **Excalidraw** for conceptual sketches.

## 6. Code Snippet Optimization
- **Self-Explanatory Naming:** Use nouns for variables/classes, verbs for methods.
- **Why-Focused Comments:** Explain the *intent* behind the logic, especially for non-idiomatic hacks.
- **Strategic Highlighting:** Use a minimalist syntax highlighting style (e.g., Alabaster) to focus attention on comments and key logic transitions.

## 7. AI-Era Distribution (GEO/AEO)
Optimize for being cited by Generative Search (SearchGPT, Google AI Overviews).

- **AEO (Answer Engine Optimization):** Structure content as clear, direct answers to specific user intents.
- **GEO (Generative Engine Optimization):** Use semantic clarity and expert-level technical terminology that LLMs can easily parse.
- **Structured Data (Schema.org):** Implement `Article`, `Person` (E-E-A-T), `Organization`, and `FAQPage` markup.
- **Long-tail Focus:** Target specific, conversational queries (e.g., "Best CRM for small B2B teams") rather than broad keywords.

## 8. Governance & RFC Culture
Treat your technical blog draft as a **Public RFC (Request for Comments)**.

- **Peer Review:** Submit drafts to colleagues or specialized "Review Boards" to verify technical accuracy.
- **RFC Template:** Use a structured format to solicit feedback on technical approaches.
- **Pre-Publish Checklist:**
  - [ ] Verify technical accuracy and security (e.g., no secrets).
  - [ ] Check metadata (Title, Favicon, OpenGraph).
  - [ ] Prepare social snippets (Who is this for? What is the core insight?).
