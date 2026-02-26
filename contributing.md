# Contributing to Awesome AI Image Tools

Thank you for your interest in contributing! This list aims to be the most comprehensive, up-to-date resource for AI-powered image tools.

## How to Submit

1. Fork this repository
2. Create a new branch: `git checkout -b add-tool-name`
3. Make your changes to `README.md`
4. Commit: `git commit -m "Add ToolName to CategoryName"`
5. Push: `git push origin add-tool-name`
6. Open a Pull Request and fill out the [PR template](.github/pull_request_template.md)

## Rules

### Adding a New Tool

1. **One tool per PR** — Keep pull requests focused. Adding multiple tools? Submit separate PRs.
2. **Check for duplicates** — Search the list first to make sure the tool isn't already included.
3. **Active tools only** — The tool must be currently maintained and publicly accessible. No dead links.
4. **No closed beta** — The tool must be available to the general public (waitlists are OK if publicly accessible).
5. **Provide real value** — Not just a thin wrapper around another tool's API.
6. **Disclose affiliations** — If you're affiliated with the tool, say so in the PR.

### Required Information

Every tool entry **must** include:

| Field | Required | Example |
|-------|----------|---------|
| Logo | Yes | Via Google Favicon API |
| Name + Link | Yes | Official website URL |
| Free Tier | Yes | See labels below |
| API Available | Yes | ✅ or ❌ |
| Description | Yes | One sentence, factual |

### Table Format

Use this exact format (with logo):

```markdown
| <img src="https://www.google.com/s2/favicons?domain=example.com&sz=32" width="16"> | [Tool Name](https://example.com) | ✅ Limited | ✅ | Short description in one sentence. |
```

### Free Tier Labels

Use the appropriate label:

| Label | When to Use |
|-------|-------------|
| `✅ Free` | Completely free, no limits |
| `✅ Free & Open Source` | Free and open source |
| `✅ Limited` | Free tier with limitations (credits, watermark, low-res, etc.) |
| `✅ Limited (detail)` | Free tier with specific limitation noted, e.g. `✅ Limited (low-res)` |
| `✅ X free credits` | Provides specific initial free credits |
| `✅ Free tier` | Has a usable free plan |
| `❌ Paid` | No free tier at all |
| `❌ Trial` | Only offers a time-limited trial |
| `❌ From $X/mo` | Paid only, with starting price |

### Description Guidelines

- **One sentence only** — Be concise
- **Factual, not promotional** — Describe what it does, not why it's "amazing"
- **Highlight differentiators** — What makes this tool unique vs. others in the same category

Good:
> AI background remover with batch processing and e-commerce templates.

Bad:
> The best and most amazing background removal tool that everyone loves!

### Placement

- Add the tool to the **correct category**
- Place it in a logical position within the category (alphabetical or grouped by type)
- If unsure about the category, note it in the PR and we'll discuss

## Updating Existing Entries

- If a tool has changed pricing, API availability, or features — submit a PR with the update
- Include a brief note in the PR description about what changed and a source link if possible

## Suggesting a New Category

- Open an issue first to discuss whether a new category makes sense
- New categories should have at least **3 tools** to justify a separate section

## Removing a Tool

If a tool is no longer maintained, has shut down, or the link is dead:

- Submit a PR removing the entry
- Include evidence (e.g. "website returns 404", "announced shutdown on Twitter")

## Code of Conduct

- Be respectful in discussions and PR reviews
- Disclose any affiliations with tools you're adding
- Focus on helping users find the best tools for their needs
- No spam or self-promotion without disclosure

## Questions?

Open an [issue](../../issues) if you have any questions about contributing.
