# Flatmark themes

Themes and sample content for [Flatmark](https://github.com/sake92/flatmark).

| Theme | Description | Main files |
| --- | --- | --- |
| `default/` | Sample site with documentation and blog pages | `default/content/`, `default/_layouts/`, `default/_includes/`, `default/static/` |
| `online-cv/` | Work-in-progress port of the [Orbit CV theme](https://github.com/sharu725/online-cv) | `online-cv/content/`, `online-cv/_layouts/`, `online-cv/_includes/`, `online-cv/_sass/` |

## Build the default theme

With the `flatmark` CLI installed, run from the repository root:

```sh
flatmark build -i default
```

The generated site is in `default/_site/`. Site settings are in `default/_config.yaml`; sample pages are in `default/content/`. The `_site/` output and `.flatmark-cache/` are ignored by Git.

## CV theme status

The `online-cv/` theme requires the `sass` executable on `PATH` to compile its SCSS. Its Flatmark build has not been verified end to end. The `theme_skin` and `chrome_mobile_color` settings in `online-cv/_config.yml` are marked unsupported.

The instructions in `online-cv/README.md` come from the upstream Jekyll theme and do not describe this repository's Flatmark workflow.
