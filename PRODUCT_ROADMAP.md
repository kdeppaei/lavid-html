# Lavid Product Roadmap

Lavid is positioned as an AI-assisted code workspace for users who copy output from multiple AI models, organize it into project layers, and turn fragments into runnable or exportable code assets.

## Current Interview Narrative

### Client Persona

The target company needs an internal tool that helps non-linear AI coding workflows become auditable, reusable, and presentation-ready.

Business needs:
- Reduce copy/paste chaos when developers use multiple AI assistants.
- Keep project context, imported resources, code snippets, and export history in one workspace.
- Make AI-assisted coding easier to review during interviews, demos, and team handoffs.
- Provide a path from single-user local storage to team-ready cloud sync.

### Builder Response

Implemented in the current static version:
- Browser-only Lavid workspace deployable on GitHub Pages.
- Local password gate with salted hash storage.
- Optional 30-day remembered-device login proof without storing plaintext password.
- Interview showcase mode for a 60-second product walkthrough.
- One-click demo project with code blocks, imported resources, and an executable presentation flow.
- Desktop keyboard shortcuts with built-in help.
- Mobile-friendly action bar replacing desktop keyboard workflows.
- Project/layer workflow, batch capture, drag/import resources, dependency scan, export, and session save.

## Next Iterations

### P1: Portfolio Polish
- Add a guided first-run tour that walks through the showcase panel, demo project, and export flow.
- Add exportable project report with screenshots, dependency list, and code summary.
- Add a public "case study" route for reviewers who only want the narrative, not the full tool.

### P2: Team Product Direction
- Add Supabase or Firebase Auth for real Google/GitHub login.
- Add cloud project sync across devices.
- Add shareable read-only project links for reviewers.

### P3: Company-Grade Developer Utility
- Add backend compiler runners for Python, C/C++, LaTeX, and HTML previews.
- Add job history and execution logs.
- Add resource integrity checks for missing images, data files, and LaTeX assets.

### P4: Review And Governance
- Add diff view between AI-generated versions.
- Add approval states such as Draft, Reviewed, Accepted, Deprecated.
- Add prompt provenance and AI model source labels.

## Design Principle

Lavid should feel like a focused engineering console, not a landing page. The product value is in turning messy AI coding iterations into a structured, reviewable workspace.
