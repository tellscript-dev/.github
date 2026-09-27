# Contributing to Tellscript

Thank you for helping. Tellscript is a format, so the most valuable contributions are reports from real use:
where a rule was unclear, where an agent misread a file, where a check could not be written.

## Ways to help

| You want to | Do this |
|---|---|
| Ask a question or show what you built | Start a thread in [Discussions](https://github.com/tellscript-dev/tellscript/discussions) |
| Propose a change to the format | Open an issue with the **Spec change** form, before any pull request |
| Report an agent that misreads Tellscripts | Open an issue with the **Agent support** form |
| Fix a typo, a broken link or a docs page | Open a pull request directly |
| Report a security problem | Follow [SECURITY.md](SECURITY.md), not a public issue |

## Changing the format

1. Open a **Spec change** issue: the problem, a real example, the proposed wording, and what it breaks.
2. A maintainer labels it `accepted` or explains why not, usually within two weeks.
3. The pull request changes the spec, the schema, the checker, the skill and the docs together. A spec change without
   the matching schema and docs change is incomplete.

## Pull requests

- One topic per pull request. Small is better.
- The title follows [Conventional Commits](https://www.conventionalcommits.org/): `feat(spec): allow text ids in Face`,
  `fix(schema): accept recipe lists`, `docs: explain guided rings`. We squash-merge, so the title becomes the commit
  message and the changelog entry. A check enforces the format.
- Run the checks before you push:

  ```sh
  npm ci
  npm run check
  ```

- Write American English in short sentences. In `spec/`, use MUST, SHOULD and MAY in capitals only where they are
  normative.

## License of contributions

By contributing you agree that your contribution is licensed like the part of the repository it changes: spec and
docs under CC BY 4.0, schema, scripts and skill under Apache 2.0, examples under CC0 1.0. See
[LICENSE.md](https://github.com/tellscript-dev/tellscript/blob/main/LICENSE.md).

## Code of conduct

Everyone taking part follows our [Code of Conduct](CODE_OF_CONDUCT.md).
