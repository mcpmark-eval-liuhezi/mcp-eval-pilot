# Adoption evaluation: github/github-mcp-server

## Latest release

- **Tag:** `v2.0.3` (release name: "GitHub MCP Server 2.0.3")
- **Published:** 2026-10-21T09:52:29Z

The release notes cover a maintenance release: two UI dependency bumps by Dependabot (`@modelcontextprotocol/client` 2.2.0 to 2.3.1 and `@vitejs/plugin-react` 6.1.1 to 6.1.2), a fix for UTF-8 encoding in repository resource URIs, a fix that returns a resource link for files over 1 MB in `get_file_contents`, cursor pagination added to `list_label`, an upgrade to Go 1.27.3 for compromised CA mitigation, and three first-time contributors.

## Project overview

The GitHub MCP Server connects AI tools directly to GitHub's platform. It gives AI agents, assistants, and chatbots the ability to read repositories and code files, manage issues and pull requests, analyze code, and automate workflows — all through natural language interactions.

## Project health

- Stars: 33,840
- Forks: 5,212
- Open issues: 382
- Recent commit subjects on the default branch (`main`):
  1. "upgrade to Go 1.27.3 for compromised CA mitigation (#3540)"
  2. "Add cursor pagination to list_label (#3505)"
  3. "fix(repos): return a resource link for files over 1 MB in get_file_contents (#3419)"
