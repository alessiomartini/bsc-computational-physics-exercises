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

## Roadmap e progressi

Questo progetto è tracciato in https://alessiomartini.github.io/projects-overview/ tramite il file `ROADMAP.md`
nella root del repo. Mantienilo aggiornato:

- Alla fine di ogni sessione di lavoro (prima del commit finale), aggiorna `ROADMAP.md`:
  - spunta (`- [x]`) i punti completati in questa sessione;
  - aggiungi come `- [ ]` i nuovi compiti emersi, nella fase giusta (titoli `##`);
  - aggiungi in cima alla sezione `## Log` una riga `- AAAA-MM-GG: <cosa è stato fatto, in una frase>`
    (se esiste già una riga con la data di oggi, estendila invece di crearne un'altra).
- Non riscrivere né riordinare le voci esistenti senza motivo; non cancellare le voci completate.
- Se `ROADMAP.md` non esiste, crealo con le fasi `## ...`, le checkbox e una sezione `## Log`.
- Includi l'aggiornamento di `ROADMAP.md` nello stesso commit del lavoro.
