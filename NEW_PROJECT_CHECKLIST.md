# New Project Checklist

Work through this before making a repository public. It takes about fifteen minutes
and is the difference between a repo that reads as finished work and one that reads
as an abandoned homework folder.

## Before the first push

- [ ] **Repository name is in English and `kebab-case`** — `sensor-fusion-ekf`, not
      `SensorFusionProject_TR`. Lowercase, hyphens, no underscores, no language tags.
- [ ] **`.gitignore` is in place before the first commit.** Build output (`bin/`,
      `obj/`, `__pycache__/`, `node_modules/`) committed in the first commit stays in
      git history forever, even after you delete it.
- [ ] **No secrets.** No `.env`, no API keys, no connection strings, no service-account
      JSON. Check twice — rotating a leaked key is much more work than avoiding it.
- [ ] **No personal identifiers.** Student numbers, national ID numbers, phone numbers
      and home addresses do not belong in filenames or documents in a public repo.
- [ ] **Default branch is `main`**, and it is the branch that actually has your work.

## README

- [ ] **First sentence says what the project does** — not what course it was for.
- [ ] **A screenshot, GIF, or diagram** near the top. Visual repos get read; text-only
      repos get scrolled past.
- [ ] **Quick Start block that actually works** on a clean machine. Test it by cloning
      into a fresh folder and following your own instructions literally.
- [ ] **Requirements stated** — language version, dependencies, OS constraints.
- [ ] **Results section with real numbers** if the project measures anything. Include a
      baseline for comparison; a number with nothing to compare against means little.
- [ ] **One paragraph interpreting the results.** Say what the numbers mean, including
      where the approach is weak. Naming a limitation reads as confidence, not doubt.
- [ ] **Project structure tree** so readers know where to look.
- [ ] **Written in English**, spell-checked.

## Metadata

- [ ] **Description filled in** — one line, English, appears in search results.
- [ ] **Topics added** — 8 to 15 tags. This is the main way strangers discover a repo.
- [ ] **Homepage URL set** if there is a live demo, published site, or paper.
- [ ] **LICENSE file present.** Without one, nobody may legally reuse your code. MIT is
      a reasonable default. If you bundle third-party assets or datasets, say so
      explicitly and name their licences.

## Code quality

- [ ] **It runs from a clean clone.** No absolute paths like `C:\Users\musta\...`.
- [ ] **Dependencies pinned** — `requirements.txt`, `package.json`, `pubspec.yaml`.
- [ ] **CI passes** (see `.github/workflows/ci.yml`).
- [ ] **Internal working notes removed** — scratch files, AI session logs, TODO dumps,
      and `.idea/` or `.vscode/` folders.

## After publishing

- [ ] **Pin it** if it is among your best six.
- [ ] **Link it from your profile README.**
- [ ] **Write about it** — a short post explaining one decision you made is worth more
      than another repo nobody reads.
