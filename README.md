# Non-data pixels

An agent skill for removing extra text without losing useful meaning.

It helps write and review interface copy, product pages, articles, and client updates. It cuts repeated labels, filler, and internal build notes while keeping useful instructions, states, facts, and context.

## Install

```sh
npx skills add d7mtg/non-data-pixels --skill non-data-pixels
```

Add `--global` to install across projects. Select your agent when prompted.

## Use

Ask your agent:

> Use non-data-pixels to clean up this screen without losing meaning.

Or:

> Use non-data-pixels to write the copy for this form.

Claude Code: `/non-data-pixels`  
Codex: `$non-data-pixels`

## What it checks

- Does the text add information the reader needs here?
- Does a nearby label, value, or action already explain it?
- Should the information appear in another state or help view?
- Does the wording match what the product actually does?
- Will a deletion hide a useful next step, limit, or consequence?

The skill includes examples for interfaces and guidance for longer writing. It follows review-only requests and keeps edits within the requested scope.

[Read the skill](SKILL.md) · [Browse on skills.sh](https://skills.sh/d7mtg/non-data-pixels/non-data-pixels)
