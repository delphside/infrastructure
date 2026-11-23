# Infrastructure: the rules that are its own

@programme/CLAUDE.md

## Where the programme lives

- The generic rules, skills and agents are in the `programme/` submodule
  (`delphside/programme`), pinned at a commit of this repository's choosing.
  `.claude/skills` and `.claude/agents` link into it. Run
  `git submodule update --init` after a clone or a pull that moves the pin.
- **The `docs/` paths and the root README in the imported rules are the
  programme's**, read in `programme/`.
- **Records are in the live checkout.**
  - `records/` and `applications/` paths are read and changed in the programme
    repository's live checkout, never in the pinned submodule.
  - The checkout is beside this repository's main worktree at `../programme`
    or wherever `PROGRAMME_DIR` says. Changes go on its `main`.
  - Infrastructure's records are under `applications/infrastructure/`.

## The session on the web

- The application's own notes issue is
  delphside/infrastructure#6 *Notes for the local session*.

## Changes

- Every commit subject in this repository starts with this application's
  stamp, `INF:`, and a space.
- A host change is this application's `Other` delivery, numbered by date:
  [6.3.4](docs/6.3.4-hosts.md#making-a-host-change) says how it is made, who
  runs each step and
  [how each application verifies itself](docs/6.3.4-hosts.md#how-an-application-verifies-itself)
  afterwards.
- No address of a host goes in a repository file or a record: the repositories
  are public.
