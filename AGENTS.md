# AGENTS.md

## Cursor Cloud specific instructions

### Project overview

Python project for LLM-based demand estimation, managed with [UV](https://docs.astral.sh/uv/). Configuration is in `pyproject.toml` (requires Python >= 3.11).

### Running code

- Use `uv run python <script>` to run scripts (UV activates the venv automatically).
- Use `uv sync` to install/update dependencies after `pyproject.toml` changes.
- Use `uv add <package>` to add new dependencies.

### Caveats

- UV must be on `$PATH`. It is installed at `$HOME/.local/bin/uv`. The update script ensures it is installed.
- The project is in early stage; there are no tests, linters, or build steps configured yet. When they are added, update this file accordingly.
