# Puzzle Column

Newspaper style puzzles with answers, a PDF and a paste-in snippet.

It's a hosted MCP server, so there's nothing to install. This repo is just the listing. The server code isn't here.

## Add it

Connector URL: `https://column.rowhousesoftware.com/mcp`

In Claude: open Settings, then Connectors, then Add custom connector. Paste the URL.

In Claude Code:

```
claude mcp add -t http puzzle-column https://column.rowhousesoftware.com/mcp
```

## Tools

- `make_puzzle`: Makes one puzzle: mini crossword, word search, sudoku, word ladder, cryptogram or maze.
- `list_puzzle_types`: Lists the puzzles and levels.
- `pro_status`: Says what the plans on the site add.

## Free and paid

Free here: make puzzles in chat. On the site, a free account gets a daily feed with 2 puzzle types. Site is $19 a month for all 7 types and your logo. Pro is $49 a month for 5 feeds. Try it all free for 14 days.

## Sign in

None. It's open. No key and no sign in.

## Help

- Site: https://column.rowhousesoftware.com
- Email: support@rowhousesoftware.com

Made by [Rowhouse Software](https://rowhousesoftware.com).
