# Infrastructure

Infrastructure is application 3 of the Delphside programme, whose
applications [2.1](https://github.com/delphside/programme/blob/main/records/2.1-applications.md)
lists. It holds the hosts the other applications run on, one or more each, and
their capacity, networking and host security
([programme 1.3](https://github.com/delphside/programme/blob/main/docs/1.3-workstreams.md))
and their currency
([programme 1.4](https://github.com/delphside/programme/blob/main/docs/1.4-programme-activities.md)).
What the applications share is in its
[profile](https://github.com/delphside/programme/blob/main/applications/infrastructure/3.3.6-profile.md).

| Item | Holds |
| --- | --- |
| [`docs/6.3.4-hosts.md`](docs/6.3.4-hosts.md) | the hosts: building one, the network, keeping them current and making a host change |
| [`docs/6.1.6-document-map.md`](docs/6.1.6-document-map.md) | the generated map of this repository's documents |
| [`CLAUDE.md`](CLAUDE.md) | the rules that are Infrastructure's own |
| [`app-profile.toml`](app-profile.toml) | the technical profile the programme's tooling reads |
| `programme/` | the [programme](https://github.com/delphside/programme) as a submodule: its generic rules, skills and tooling |

Its documents are numbered `6.x`.

| Elsewhere | Holds |
| --- | --- |
| [`applications/infrastructure/`](https://github.com/delphside/programme/tree/main/applications/infrastructure) | its records, numbered `3.3.x` as the programme's [2.1](https://github.com/delphside/programme/blob/main/records/2.1-applications.md#what-each-applications-folder-holds) gives them |
| [delphside/infrastructure](https://github.com/delphside/infrastructure/issues) | its issues, on the programme board, which [1.6](https://github.com/delphside/programme/blob/main/docs/1.6-github-project-board.md) describes |

Run `git submodule update --init` after a clone or a pull that moves the
submodule's pin
([programme 1.1](https://github.com/delphside/programme/blob/main/docs/1.1-programme-tooling.md#two-kinds-of-tooling)).
