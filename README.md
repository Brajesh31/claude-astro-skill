# claude-astro-skill

A Claude Code skill for building fast, content-focused websites with Astro.

## Overview

Astro is designed for content-heavy websites, portfolios, documentation, blogs, and marketing sites. Its islands architecture limits client-side JavaScript to interactive parts of a page. This skill supports Astro components, Markdown and MDX, content collections, rendering modes, UI framework integrations, and deployment configuration.

## When to Use This Skill

- Building blogs, documentation sites, portfolios, and marketing websites.
- Creating content-heavy websites with Markdown or MDX.
- Integrating React, Vue, Svelte, or other supported UI components.
- Improving loading performance and reducing unnecessary client JavaScript.
- Configuring server-side rendering, static generation, or deployment output.

## Quick Start

Create an Astro project:

```bash
npm create astro@latest my-site
cd my-site
npm install
npm run dev
```

Install this skill:

```bash
git clone https://github.com/Brajesh31/claude-astro-skill.git ~/.claude/skills/astro
```

## Recommended Workflow

1. Inspect the Astro version, configuration, and project structure.
2. Choose static generation, server rendering, or a hybrid approach.
3. Organize pages, layouts, components, and content collections.
4. Hydrate only interactive components that need browser-side state.
5. Validate schemas, accessibility, and responsive behavior.
6. Build for the intended deployment adapter and test production output.

## Core Concepts

- **Astro components:** Use `.astro` files for page and component templates.
- **Islands architecture:** Render static content by default and hydrate interactive components only when required.
- **Content collections:** Organize structured content with schemas and predictable queries.
- **Rendering modes:** Choose static or server output based on data freshness and personalization.
- **UI integrations:** Add framework components when they provide real value.

## Performance Checklist

- Keep static content pre-rendered where possible.
- Hydrate only genuinely interactive components.
- Optimize images and fonts.
- Avoid unnecessary browser dependencies.
- Test production output, not only the development server.
- Measure performance before and after major changes.

## Repository Contents

- `SKILL.md`: Main Astro development instructions.
- `README.md`: Installation, concepts, and workflow.

## Maintenance

Confirm the project's installed Astro version before changing configuration or relying on version-specific APIs.

## Creator and maintainer

Created and maintained by **Brajesh Kumar**.
