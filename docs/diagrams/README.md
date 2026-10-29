# Diagrams

> **Template.** Ahmed draws these; the mentor reviews them. Keep diagrams as code (Mermaid preferred, PlantUML if Mermaid can't express something) so they're versioned in Git and render on GitHub. Update a diagram whenever the design changes, and embed each one in `docs/design-doc.md`.

## How to make them

- **Mermaid:** write a fenced code block with the `mermaid` language tag inside a `.md` file; GitHub renders it automatically. Preview while editing with the [Mermaid live editor](https://mermaid.live/) or IntelliJ's Markdown preview. Docs: [mermaid.js.org](https://mermaid.js.org/intro/).
- **PlantUML:** use it for diagram types Mermaid handles poorly (e.g. classic use-case diagrams). Commit the `.puml` source and an exported `.svg` next to it. Docs: [plantuml.com](https://plantuml.com/).
- One diagram per file, named after what it shows (e.g. `domain-class.md`).

## Diagrams to make

| Diagram | File | Shows | When (roadmap) | Status |
|---|---|---|---|---|
| Use-case diagram | _`use-case.md` or `.puml`_ | _Actors (user, admin) and what each can do_ | M1.2 | Not started |
| Domain class diagram | _`domain-class.md`_ | _Core domain objects, their fields and relationships_ | M1.2 | Not started |
| ERD | _`erd.md`_ | _Database tables, keys and relationships_ | M1.3 | Not started |
| Transfer sequence diagram | _`transfer-sequence.md`_ | _A transfer from HTTP request to committed rows, including failure paths_ | M1.3 | Not started |
| Architecture diagram | _`architecture.md`_ | _Frontend, backend layers, database, and later additions_ | M1.4, M2.7 | Not started |
| Auth sequence diagram | _`auth-sequence.md`_ | _Login and an authenticated request with a JWT_ | M3.4 | Not started |

## Checklist for every diagram

- _Does it have a title and a one-line caption explaining what it shows?_
- _Does it match the current code and design doc?_
- _Could someone new understand it without you explaining it?_
