# Security policy

Tellscript is a text format, but the tools around it (the checker, the agent skill, the plugin manifests) run on
your machine and inside your agent. We take problems in them seriously.

## Reporting a vulnerability

Please report privately through GitHub: open the repository, choose **Security**, then **Report a vulnerability**.
Do not open a public issue.

Include what you found, how to reproduce it and what an attacker could do with it. We confirm receipt within three
working days and keep you informed until it is fixed. We credit reporters in the release notes unless you prefer
otherwise.

## In scope

- `scripts/`, `schema/`, `skills/` and `.claude-plugin/` in
  [tellscript-dev/tellscript](https://github.com/tellscript-dev/tellscript)
- Instructions in the skill or docs that could lead an agent to run harmful commands, leak secrets or ignore a user's
  instructions
- The website [tellscript.com](https://tellscript.com)

## Supported versions

Only the latest release is supported. The format is a draft; security fixes are released as patch versions.
