# gipsic/homebrew-tap

Homebrew tap for GIPSIC's open-source tools.

```bash
brew tap gipsic/tap
brew install claude-usage
```

## claude-usage

Local usage, limit and cost dashboard for Claude Code — real percentages from
Anthropic's own usage endpoint, exact reset times, burn rate and months of
history, all on your own machine.

- Source and issues: <https://github.com/gipsic/claude-usage>
- The formula here is generated from
  [`packaging/homebrew/claude-usage.rb`](https://github.com/gipsic/claude-usage/blob/main/packaging/homebrew/claude-usage.rb)
  in that repository; open pull requests there, not here.

After installing:

```bash
claude-usage install-daemon      # background tracker, starts at login
claude-usage serve --open        # http://127.0.0.1:4778
```

MIT licensed, same as the tools it ships.
