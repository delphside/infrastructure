# Infrastructure: the rules that are its own

@programme/CLAUDE.md

## Where the programme lives

- The generic rules, skills and agents are in the `programme/` submodule
  (`delphside/programme`), pinned at a commit of this repository's choosing.
  `.claude/skills` and `.claude/agents` link into it. Run
  `git submodule update --init` after a clone or a pull that moves the pin.
- **The `docs/1.x` paths in the imported rules are read in `programme/`.**
- **Records are in the live checkout.**
  - `records/` and `applications/` paths are read and changed in the programme
    repository's live checkout, never in the pinned submodule.
  - The checkout is beside this repository's main worktree at `../programme`
    or wherever `PROGRAMME_DIR` says. Changes go on its `main`; a cloud session
    makes them by a short-lived pull request.
  - Infrastructure's records are under `applications/infrastructure/`.

## The session on the web

- The application's own notes issue, where a web session leaves its note for
  the local session when no issue concerns the work, is delphside/infrastructure#6, *Notes for the local session*.

## Changes

- Every subject starts with this application's stamp, `INF:`, and a space.
- A host change is a delivery of this application, route `Other`, numbered by
  date; [6.3.4](docs/6.3.4-hosts.md#making-a-host-change) says how it is made.
- Every host step is the owner's to run, and no address of a host goes in a
  file: the repositories are public.
