# claude-mods

Claude Code mods by Rahadul.

| Mod | What it does |
| --- | --- |
| [SF Guardian](./sf-guardian) | Salesforce helper: production deploy guard, org badge, live Files sidebar with diffs, compact `sf` output, Apex test tracking, coverage and org limits |

## Install

```bash
claude plugin marketplace add rahadulx1/claude-mods
claude plugin install sf-guardian@rahadul-mods
echo '{"prod_orgs":"your-prod-alias, admin@yourcompany.com"}' | claude plugin configure sf-guardian@rahadul-mods --values-stdin
```

Restart Claude Code, start it from inside your Salesforce project folder, and type `/sffiles`.

Requires:

- Claude Code 2.1.287 or later (`claude --version`)
- `git`
- The Salesforce CLI (`sf`)

## Update

```bash
claude plugin marketplace update rahadul-mods
claude plugin update sf-guardian@rahadul-mods
```

Then restart Claude Code. Your settings are kept.

To update automatically: in Claude Code open `/plugin`, choose **Marketplaces**, select `rahadul-mods`, and choose **Enable auto-update**.

## License

MIT
