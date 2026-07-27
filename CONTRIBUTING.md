# Contributing

Thanks for your interest in this project. Contributions of all sizes are welcome.

## Reporting a bug

Open an issue using the **Bug report** template. The most useful reports include the
exact steps to reproduce, what you expected, what actually happened, and your
environment (OS, language version). A minimal reproduction is worth more than a long
description.

## Suggesting a feature

Open an issue using the **Feature request** template. Explain the problem you are
trying to solve before proposing a specific solution — there may be a simpler approach.

## Submitting a pull request

1. Fork the repository and create a branch from `main`:
   `git checkout -b feature/short-description`
2. Make your changes. Keep the commit history readable — one logical change per commit.
3. Match the existing code style. If the project has a linter configured, run it.
4. Verify the project still builds and any tests still pass.
5. Push your branch and open a pull request using the template.

Small, focused pull requests get reviewed faster than large ones. If you are planning
a substantial change, open an issue first so we can agree on the approach before you
invest the time.

## Commit messages

Write in the imperative mood, describing what the commit does:

```
Add magnetometer fallback for EMI blackout zones
Fix off-by-one error in polygon edge crossing count
Update README with Monte Carlo results
```

Explain *why* in the commit body when the reason is not obvious from the diff.

## Questions

If something is unclear, open an issue and ask. An unclear README is a bug worth
reporting.
