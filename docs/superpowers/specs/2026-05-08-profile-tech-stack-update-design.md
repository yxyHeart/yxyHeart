# Profile Tech Stack Update Design

## Context

The GitHub profile README (`yxyHeart/yxyHeart`) currently only shows frontend technology badges. The user has expanded their skill set to cover frontend, backend, and AI engineering. The README needs to be updated to reflect the full stack.

## Design

### Layout: Flat Grouped Badges

Maintain the existing style — shields.io Markdown badges arranged in flat groups, separated by blank lines. No section headers, no emojis. Each group represents one category on its own line.

### Badge Groups (top to bottom)

1. **Languages:** Go, Java, Python, TypeScript, JavaScript, Node.js, HTML5, CSS3
2. **Frontend:** React, Vue.js, TailwindCSS, Sass, Less
3. **Backend:** Spring Boot, Gin, FastAPI, NestJS
4. **AI Engineering:** LangChain, OpenAI, Claude, LlamaIndex
5. **Database:** MySQL, PostgreSQL, MongoDB, Redis
6. **DevOps:** Docker, Kubernetes, Nginx, GitHub Actions
7. **Tooling:** Vite, Webpack, ESLint, Prettier, Git, VS Code

### Changes from Current README

- **Add:** Go, Java, Python, Node.js (languages); Spring Boot, Gin, FastAPI, NestJS (backend); LangChain, OpenAI, Claude, LlamaIndex (AI); MySQL, PostgreSQL, MongoDB, Redis (database); Docker, Kubernetes, Nginx, GitHub Actions (DevOps)
- **Remove:** Rollup (redundant with Vite/Webpack)
- **Keep:** All existing frontend and tooling badges
- **Remove:** Commented-out template text (the "ideas to get started" block)

### Badge Style

All badges use shields.io with `style=flat-square`, matching the existing convention. Each badge follows the format:

```markdown
![Label](https://img.shields.io/badge/-Label-Color?style=flat-square&logo=logo-slug&logoColor=logoColor)
```

Colors and logo slugs will follow shields.io conventions for each technology.

### File Modified

- `README.md` — full rewrite of badge section, remove template comments

### Verification

1. Open the repo on GitHub and verify the profile README renders correctly
2. Check that all badge images load (no broken images)
3. Confirm grouping and ordering matches the design above
