# stats-allowlist

Network allowlists for AI coding agents working on the lab's statistics and teaching repositories.

- `allowlist.txt`: the allowlist for GitHub Copilot's coding agent.
  Each entry is a host or URL followed by a comma.
- `claude-allowlist.txt`: the allowlist for Claude Code cloud sessions,
  one host per line.
  A leading `*.` matches subdomains only, so a site often needs both
  `example.org` and `*.example.org`.

When an agent's network proxy refuses a host it needs, add the host to the list for that agent.
If the other agent needs the host too, add it to both lists.
