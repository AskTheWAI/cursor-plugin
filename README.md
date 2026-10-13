# Ask The W for Cursor

Ask The W is an AI-native productivity suite. This plugin connects Cursor to your Ask The W projects so Cursor can read a project's context and act in it when you ask.

## Install

Open Customize in Cursor, install Ask The W, and choose a project or user scope. Sign in to Ask The W and choose a project.

The connector address is https://my.askthew.com/api/mcp. You can add that address under MCP if you are not installing from the marketplace. Cursor CLI uses the same connector. There is no local package to install, and there is no browser code to confirm.

To test this folder before it is listed, copy it to `~/.cursor/plugins/local/askthew`, reload Cursor, and confirm Ask The W appears in Customize.

## What it sends and reads

- Reads the chosen project: W Card, North Star, outcomes, decisions, next moves, and Workspace files.
- Writes to that project only when you ask, for example a decision, an outcome, a move, or a file.
- Sends only what Cursor passes to the tool you asked for. It never sends transcripts.

`request_world_analysis` starts a paid World analysis. The agent calls it only when you ask. `draft_wire_message` writes a draft for a person to review and never sends.

Data goes only to Ask The W at https://my.askthew.com. Privacy: https://askthew.com/privacy. Terms: https://askthew.com/terms. Support: support@askthew.com.
