# pr-with-user-impact

Claude Code skill for generating PRs with concrete User Workflow Impact sections.

## Install

```bash
npx @anthropic-ai/claude-code skills add https://github.com/jorgempenalva/pr-with-user-impact
```

## Usage

When creating PRs, Claude will automatically generate User Workflow Impact sections with:

- **Concrete before/after examples** (not abstract descriptions like "faster" or "better")
- **Emotional language** that makes pain/relief tangible
- **Business outcomes** explaining why the change matters

## Example Output

```markdown
## User Workflow Impact

### Dashboard Loading
**User action:** Opening the analytics dashboard to check daily metrics

| Before | After |
|--------|-------|
| 4.2 second blank screen—users often refresh thinking the page is frozen | 0.8 second load with skeleton UI appearing immediately |

**Impact:** Eliminates the "is it broken?" moment. Users start their day with data instead of frustration.
```

## What Makes This Different

Instead of:
> "Improved page load performance"

You get:
> "Dashboard takes 4.2s → 0.8s. Eliminates the 'is it broken?' moment."

Instead of:
> "Fixed form validation bug"

You get:
> "Entering 'José García' no longer fails silently. Users with accented names don't have to anglicize their input."

## License

Apache 2.0
