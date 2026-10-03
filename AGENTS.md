> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- Seiten sind auf Deutsch, in einfacher Sprache für nicht technisch versierte Nutzer, mit „Sie“-Anrede.
- „Person“ = jemand, dessen Daten verwaltet werden; „Benutzer“ = jemand mit Zugang zum Wehrmanager.
- Menü- und Schaltflächennamen exakt wie im Programm (Quelle: Repo muehleis/wehrmanager2026) und fett schreiben.

## Style preferences

- Jede Modulseite beginnt mit einem `<Info>`-Kasten „Wo finden Sie das? …“ mit dem Menüpfad.
- Jede Seite hat `description` und `keywords` im Frontmatter, damit die Suche Begriffe findet.
- Neue Begriffe auch im Stichwortverzeichnis (`stichwortverzeichnis-a-z.mdx`) ergänzen.
- Use active voice and second person ("Sie")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
