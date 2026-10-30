# askdb plugin

One plugin with two skills for askdb.

| Skill | Command | What it does |
| :- | :- | :- |
| create-db-configs | `/askdb:create-db-configs <sqlite-file>` | Creates the askdb database YAML for a SQLite file |
| create-eval-dataset | `/askdb:create-eval-dataset <sqlite-file> <config-yaml>` | Creates an evaluation set with confirmed expected SQL |

## Requirements

- The Claude Code project must be the askdb repository, or a checkout of it, because both skills run `uv run` against the `askdb` package.
- SQLite databases only.
