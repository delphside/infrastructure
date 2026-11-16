# Infrastructure

What the applications share: the hosts they run on, the networking in front of
them, host security and keeping the hosts current. Application 3 of the
Delphside programme. Each application has hosts of its own, and each depends
on Infrastructure only as its host.

- Its documents are numbered `6.x`. [6.3.4](docs/6.3.4-hosts.md) is the hosts
  document: the hosts, building one, the network, keeping them current and
  making a host change.
- Its records (delivery log, artefact register, capacity plans, workstreams,
  profile) are in the programme repository, under
  [`applications/infrastructure/`](https://github.com/delphside/programme/tree/main/applications/infrastructure).
- Its issues are on the programme board, beside every other application's.
- `programme/` is the programme's submodule: its generic rules, skills and
  tooling. Run `git submodule update --init` after a clone.
