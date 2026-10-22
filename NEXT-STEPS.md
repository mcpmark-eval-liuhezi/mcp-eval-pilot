# Pilot checklist

1. Star the upstream repository (done)
2. Review EVALUATION.md and confirm the research snapshot for the architecture review
3. Decide pilot scope: which toolsets (repos, issues, PRs, actions) and which users
4. Provision credentials (PAT or GitHub App) with the minimum permissions needed for the pilot
5. Install the GitHub MCP Server for 2-3 pilot users (remote server or local Go binary)
6. Run representative workflows: repository browsing, issue/PR automation, Actions monitoring, code analysis
7. Review security posture: toolset policies, read-only vs. write access, audit logging
8. Collect feedback and time-savings data from pilot users
9. Present pilot results and recommend adopt / hold / decline

Upstream: https://github.com/github/github-mcp-server
Pilot workspace: https://github.com/mcpmark-eval-liuhezi/mcp-eval-pilot
