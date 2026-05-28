# HyperBricks Starters

YAML starter templates for bootstrapping HyperBricks modules and apps.

## Layout

- `starters.index.json` catalogs starters and versions.
- `starters/<name>/<version>/` contains one installable starter version.
- Each starter version contains a `manifest.json` file and a module-ready YAML file tree.
- Starters use `package.hyperbricks.yaml` and `*.hyperbricks.yaml` sources.

## Included Starters

- `hello-world@1.0.0`: minimal YAML HyperBricks starter with a single route.
