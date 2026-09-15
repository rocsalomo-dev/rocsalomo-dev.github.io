# Roc Salomo - AI Engineer Portfolio

An engineering-notebook portfolio for grounded LLM applications, agentic
workflows and production data systems.

**Live:** [rocsalomo-dev.github.io](https://rocsalomo-dev.github.io/)

## Design

"Dark technical" uses a near-black, blue-tinted base, a teal interactive
accent and amber for measured results. Space Grotesk provides display type,
Inter is used for body copy and JetBrains Mono identifies system details.

Each project is presented at two levels:

1. The homepage explains its purpose, user outcome and AI engineering concepts.
2. A long-form engineering note documents architecture, implementation,
   production controls, trade-offs and lessons learned.

## Structure

```text
index.html                        # Portfolio and case-study summaries
projects/fieldnote-ai/index.html  # Fieldnote AI engineering note
projects/gravelradar/index.html   # GravelRadar engineering note
styles.css                        # Shared responsive design system
script.js                         # Scroll-reveal behavior
```

No build step, no dependencies. Open `index.html` or serve with any static server.

## Projects

| Project | Category | Status |
|---|---|---|
| **Fieldnote AI** | RAG, grounding, model routing | Working system and [public source](https://github.com/rocsalomo-dev/personal-ai-rag) |
| **GravelRadar** | Agents, structured data, feedback loops | [Live product](https://thegravelradar.com) |

## Run locally

```bash
python3 -m http.server 8080
# http://localhost:8080
```

## Deploy

GitHub Pages deploys the repository from `main` at the site root.
