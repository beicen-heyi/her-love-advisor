# HER Love Advisor

`her-love-advisor` is a Chinese-language Codex Skill for dating conversations: reading the situation without mind-reading, drafting natural messages, planning low-pressure invitations, comparing user-chosen routes, and handling replies without promising a result.

## Install

Copy the `her-love-advisor` directory into your Codex skills directory, keeping `SKILL.md`, `agents/`, and `references/` together. Restart or reload Codex if your environment does not discover new skills automatically.

The Skill has no additional runtime dependency. PyYAML and the official `skill-creator` `quick_validate.py` were used only for development validation; neither is bundled, and installing or using the Skill does not require them.

Invoke it as `$her-love-advisor`, for example:

```text
使用 $her-love-advisor 帮我判断局面，并按我想走的路线给具体回复和下一步。
```

## What it does

- Separates observable facts, plausible interpretations, and unknowns.
- Serves the route the user chooses: continue pursuing, clarify, stay in contact, reduce investment, or exit.
- Produces one sendable message, likely reply branches, and the costs and uncertainty of the chosen route.
- Allows playful and attractive expression while rejecting coercion, deception, surveillance, harassment, or workarounds around explicit refusal.
- Loads safety guidance only when the facts trigger it, so ordinary dating questions are not displaced by crisis checklists.

## Boundaries

This Skill does not guarantee attraction or relationship outcomes, diagnose another person's motives, provide legal or medical advice, or replace emergency and professional support. It does not provide methods to bypass explicit refusal, exploit minors or power differences, manipulate through jealousy or punishment, access accounts, track people, or increase danger.

The source map documents evidence limits and public safety references. Those sources support bounded safety routing; they do not prove that a particular message or dating tactic works.

## Version

Current release candidate: `0.3.0`.

## Source and license

Derived from `shengjidaguai-china/goutoujunshi` at [commit `6c32b8dbe28268e26d6cd0bb7de1e28ff5dd203f`](https://github.com/shengjidaguai-china/goutoujunshi/tree/6c32b8dbe28268e26d6cd0bb7de1e28ff5dd203f) under the [upstream MIT License](https://github.com/shengjidaguai-china/goutoujunshi/blob/6c32b8dbe28268e26d6cd0bb7de1e28ff5dd203f/LICENSE); modified release maintained by GitHub user `beicen-heyi`.

The existing upstream MIT license and copyright notice are preserved in [LICENSE](LICENSE). No legal-name copyright claim is added by this release package.

See [ATTRIBUTION.md](ATTRIBUTION.md) for the per-file provenance table and the maintainer's licensing confirmation for new and modified material.
