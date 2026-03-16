# AGENTS.md

Project-specific instructions for coding agents working in `G:\CV-2026`.

## Scope Guardrail

- Do not generate files from `sources` to some other folders of the project.
- The only allowed exception is this `AGENTS.md` file itself.

## Course Layout

- `sources/` is the source-of-truth for LaTeX authoring.
- `Week_01`, `Week_02`, and similar folders are student-facing delivery folders and should not be edited by agents unless the user explicitly overrides this rule.

## LaTeX Notes

- Always use `sources/style.sty` when the lecture format supports the shared course style.
- Always use `sources/references.bib` as the shared bibliography source.
- Prefer shared assets under `sources/figures/` and `sources/references.bib`.
- Keep paths portable so the `sources/` folder can be opened independently in Cursor, Prism, or Overleaf.
