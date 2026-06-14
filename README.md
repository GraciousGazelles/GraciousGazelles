# GraciousGazelles

I build systems for moving quickly with AI agents without pretending they are safe by default.

My public AI lab is [Sedna Labs](https://github.com/sednalabs), where the current work focuses on Rust infrastructure for autonomous-agent operations: [Model Context Protocol](https://modelcontextprotocol.io/) tooling, operator-controlled automation, local credential control, observability, and verification paths that humans can audit.

The operating assumption is simple: agents are useful because they move quickly, and risky because they make mistakes. The work is about keeping the speed while adding boundaries, provenance, review points, and fail-closed behavior when evidence is missing.

## Public Work

- [Sedna Labs](https://github.com/sednalabs) - public AI lab and home for the MCP/tooling ecosystem.
- [mcp-toolkit-rs](https://github.com/sednalabs/mcp-toolkit-rs) - reusable Rust foundations for MCP servers and clients.
- [cloudflare-mcp](https://github.com/sednalabs/cloudflare-mcp), [postgres-mcp](https://github.com/sednalabs/postgres-mcp), and related servers - operator-facing MCP tools for real systems.
- [android-computer-use-mcp](https://github.com/sednalabs/android-computer-use-mcp) and [codex](https://github.com/sednalabs/codex) - computer-use and coding-agent workflows.

I prefer small tools with clear contracts, local control, explicit review boundaries, and audit trails over broad promises of autonomous correctness.
