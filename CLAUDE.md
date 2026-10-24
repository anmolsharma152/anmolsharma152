# anmolsharma152 (GitHub profile README)

This is the special `anmolsharma152/anmolsharma152` repo: its `README.md` is rendered at the top of https://github.com/anmolsharma152. There is no application code.

## Files
- `README.md`: the profile page, plain GitHub-flavored Markdown (no badges, emojis or animations). Sources for project claims: the resume at `/home/omarchy/Documents/Resumes/Resume_Master.md` and each project's code.
- `.agents/AGENTS.md`: Antigravity-only rule (copy planning artifacts into a docs folder). Not relevant to README edits.

## Setup / Run / Test
- No build, dependencies, tests, linters or formatters are configured.
- Preview (verified): `gh api markdown -f mode=gfm -f context=anmolsharma152/anmolsharma152 -f text="$(< README.md)"` returns the rendered HTML; or push and view the profile.
- Check that linked repos exist (verified):
  `for r in $(grep -oE 'github.com/anmolsharma152/[A-Za-z0-9_.-]+' README.md | sort -u | cut -d/ -f3); do gh repo view anmolsharma152/$r --json name -q .name >/dev/null 2>&1 || echo "missing: $r"; done`

## Conventions
- Commit messages use Conventional Commits (`docs(readme): ...`, `fix(readme): ...`, `ci: ...`).
- Every project claim (language, "zero-deps", model size, dataset size, results) should match the linked repo's code. Check the local clone under `/home/anmol/Projects/<name>` before you write a claim. Local folder names often differ from repo names, e.g. `Fine-tuning Sarvam-1` → `sarvam-1-indic-instructor`, `Nimbus` → `nimbus`, `Delusion Calculator` → `Delusion-Calculator`.

## Gotchas
- `/home/omarchy/Projects` is a symlink to `/home/anmol/Projects`; both paths are this same clone.
- The Pac-Man contribution workflow was removed; the remote `output` branch that held its SVGs may still exist and is unused.
- CanonData is private (`/home/omarchy/Work/Startup Project`); mention it without a link.
- Profile pinned repos and bio are set in GitHub settings, not in this repo. Keep them consistent with the README.
- Only list projects with real code in a public repo. Excluded as of 2026-10-24 because they are empty or docs-only: ML-Foundations, microgguf, switchyard.
