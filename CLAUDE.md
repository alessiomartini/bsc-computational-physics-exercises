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

## Roadmap, idee e progressi

`ROADMAP.md` nella root è l'**unico** file per todo, idee, decisioni e diario del progetto
(niente `FUTURE-ARCHITECTURE.md`, `IDEE.md`, `TODO.md`). È letto da https://alessiomartini.github.io/projects-overview/.
Sezioni: `## <fase>` (checkbox, contano nella percentuale), `## Idee` (checkbox, non contano),
`## Decisioni e cose provate` (prosa: scartato/rimandato e perché, provato e annullato, limiti e bug noti), `## Log`.

- Alla fine di ogni sessione di lavoro (prima del commit finale), aggiorna `ROADMAP.md`:
  - spunta (`- [x]`) i punti completati in questa sessione;
  - aggiungi come `- [ ]` i nuovi compiti nella fase giusta, e le idee non decise in `## Idee`;
  - annota in `## Decisioni e cose provate` ciò che è stato scartato, rimandato o annullato, col perché;
  - aggiungi in cima a `## Log` una riga `- AAAA-MM-GG: <cosa è stato fatto, in una frase>`
    (se esiste già una riga con la data di oggi, estendila invece di crearne un'altra).
- Non riscrivere né riordinare le voci esistenti senza motivo; non cancellare le voci completate.
- Se `ROADMAP.md` non esiste, crealo da `templates/ROADMAP.md` di projects-overview.
- Includi l'aggiornamento di `ROADMAP.md` nello stesso commit del lavoro.
