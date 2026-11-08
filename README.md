# claude-astro-skill

A Claude Code skill for building fast, content-focused websites with the Astro web framework.

## Overview

Astro is designed for websites where content, performance, and flexible rendering matter. Its component-island architecture keeps client-side JavaScript limited to the interactive parts of a page. Astro also supports Markdown and MDX content, server-side rendering, static generation, and components from multiple UI frameworks.

This skill helps plan and implement Astro projects, organize content, integrate interactive components, and make rendering choices based on the needs of the site.

## When to Use This Skill

- Building blogs, documentation sites, portfolios, and marketing websites.
- Creating content-heavy websites with Markdown or MDX.
- Building static sites with selective dynamic routes.
- Integrating React, Vue, Svelte, or other supported UI components.
- Improving loading performance and reducing unnecessary client JavaScript.
- Working with Astro components, content collections, and client directives.
- Configuring server-side rendering or deployment output.

## Core Concepts

### Astro Components

Use `.astro` files for page and component templates. Keep data loading, markup, and component responsibilities clear.

### Islands Architecture

Render static content by default and hydrate interactive components only when required. Choose client directives based on when and where interactivity is needed.

### Content Collections

Organize structured content with schemas and predictable content queries. Validate content fields instead of relying on inconsistent frontmatter.

### Rendering Modes

Choose static generation, server rendering, or a hybrid approach based on data freshness, personalization, and deployment constraints.

### UI Framework Integration

Use a framework component when it provides real value. Avoid shipping a large client runtime for interactions that can be handled with standard HTML and browser capabilities.

## Create a Project

```bash
npm create astro@latest my-site
cd my-site
npm install
npm run dev
```

## Install the Skill

```bash
git clone https://github.com/Brajesh31/claude-astro-skill.git ~/.claude/skills/astro
```

## Usage

Invoke the skill for Astro development tasks:

```text
/astro
```

Include the Astro version, deployment target, rendering requirements, and relevant files when requesting implementation help.

## Recommended Workflow

1. Inspect the existing Astro configuration and project structure.
2. Determine whether the site should be static, server-rendered, or hybrid.
3. Organize pages, layouts, components, and content collections.
4. Keep interactive islands limited to components that need browser-side state.
5. Validate schemas and content data.
6. Check accessibility and responsive behavior.
7. Build for the intended deployment adapter and test the production output.

## Example Project Structure

```text
src/
├── components/
├── layouts/
├── pages/
├── content/
│   └── blog/
└── styles/
public/
astro.config.mjs
package.json
```

Adapt the structure to the project rather than creating unnecessary layers.

## Performance Checklist

- Keep static content server-rendered or pre-rendered where possible.
- Hydrate only genuinely interactive components.
- Select the lightest suitable client directive.
- Optimize images and fonts.
- Avoid unnecessary dependencies in the browser bundle.
- Test production output, not only the development server.
- Measure page performance before and after major changes.

## Repository Contents

- `SKILL.md`: Main Astro development instructions.
- `README.md`: Framework overview, setup, and recommended workflow.

## Maintenance

Astro features and configuration can vary between releases. Confirm the project's installed version before changing configuration or relying on version-specific APIs.
