# Workaround for `fish` support via `direnv`

Hermit does not currently support `fish` directly, but you can use `direnv` to
achieve similar functionality.

## Manual Installation
1. Install `direnv` via your package manager.
2. Run `./setup.sh` to copy `.direnvrc` to `$HOME/.direnvrc`.
3. Copy `.envrc.example` to `project_dir/.envrc` and modify it to your needs.
4. Use `direnv allow` to activate the environment (usually only needed on
   modification of `.envrc`)

