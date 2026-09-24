# Agent Instructions

## Repository Layout

- `default/` is the Flatmark sample theme. Edit source in `content/`, `_layouts/`, `_includes/`, `_i18n/`, `_data/`, and `static/`.
- `online-cv/` is an adapted Orbit CV theme. Its source is in `content/`, `_layouts/`, `_includes/`, `_sass/`, `_data/`, and `static/`.
- Keep changes scoped to the theme being worked on.

## Validation

| Task | Command |
| --- | --- |
| Build the default theme | `flatmark build -i default` |
| Check patch formatting | `git diff --check` |

- `default/_site/` and `default/.flatmark-cache/` are generated and ignored; edit source files instead.
- No repository test suite or package manager is configured.

## References

| Need | File |
| --- | --- |
| Repository overview | `README.md` |
| Default site settings | `default/_config.yaml` |
| CV theme provenance and limitations | `online-cv/README.md` |
| CV site settings and unsupported options | `online-cv/_config.yml` |

- `online-cv/README.md` retains upstream Jekyll setup instructions; do not assume they are this repository's build workflow.
