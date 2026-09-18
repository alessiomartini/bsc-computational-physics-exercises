# Claude Code instructions

## Project

C/C++ computational-physics exercises and reports. Each exercise is kept in
its own directory; preserve that organization.

## Verification

- Read `README.md` and the target exercise before editing.
- Compile and run the smallest affected exercise with the compiler/options
  already used in that directory or documented by the repository.
- Check numerical output against the stated problem and existing conventions.

## Workflow

- Prefer clear, minimal changes; do not silently change units, algorithms, or
  numerical tolerances.
- Do not add build systems or dependencies without approval.
- Keep generated binaries, plots, and temporary data out of git unless tracked.
- Inspect the diff and report the exact verification command before committing.
