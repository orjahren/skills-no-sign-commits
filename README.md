# no-sign-commits

A Claude Code skill that enforces `--no-gpg-sign` on every `git commit` command.

## What it does

When installed, this skill ensures Claude always includes `--no-gpg-sign` in every `git commit` invocation — including `--amend`, `--fixup`, and all other commit variants. No exceptions.

This is useful when GPG signing is configured in your global or repo git config but you don't want Claude's commits to be signed.

## Installation

```bash
claude plugin install orjahren/skills-no-sign-commits
```

## Usage

Once installed, no configuration is needed. Claude will automatically apply `--no-gpg-sign` to every commit it runs.

## License

MIT
