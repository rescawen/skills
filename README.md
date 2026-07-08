# Personal Codex Skills

This repo tracks personal/project skills that can be restored across devices with
the [`skills`](https://www.skills.sh/) CLI.

## Restore on a New Device

From the repo root:

```sh
npx skills experimental_install
```

The install is driven by `skills-lock.json`.

## Add a Skill

```sh
npx skills add https://github.com/vercel-labs/agent-skills --skill vercel-react-best-practices --agent codex --copy
```

## Update Skills

```sh
npx skills update -p -y
```

Review the diff after updating, then commit the refreshed skill files and
`skills-lock.json`.
