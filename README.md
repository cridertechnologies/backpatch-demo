# Backpatch demo

Public demo of [`cridertechnologies/backpatch-action`](https://github.com/cridertechnologies/backpatch-action) on an **after-only** fixture:

- `@sailshq/request@2.88.3` already declares exact `tough-cookie@4.1.3`
- An `overrides` pin of `tough-cookie@4.1.3` remains — Backpatch reports **SafeToRemove**
- Workflow uses **`fail-on: never`** (report-only — you review; you decide)

This is **not** a delete guarantee and **not** a before→after flip story.

## See it run

1. Follow the **[Action quickstart](https://backpatch.dev/action?utm_source=github&utm_medium=demo_repo&utm_campaign=action_try)** (`fail-on: never` → Pro trial).
2. Then check the [latest Actions run](https://github.com/cridertechnologies/backpatch-demo/actions) on this repo for the job summary (report-only — a green check needs a valid `BACKPATCH_API_KEY` secret).

## Try it in 5 minutes

**[Action quickstart →](https://backpatch.dev/action?utm_source=github&utm_medium=demo_repo&utm_campaign=action_try)** — `fail-on: never` → Pro trial (14-day · $0 due today).

## Fixture

```json
{
  "dependencies": { "@sailshq/request": "2.88.3" },
  "overrides": { "tough-cookie": "4.1.3" }
}
```

## Claim bar

Trial + report-only. Default Action path is `fail-on: never`. Review before you delete.
