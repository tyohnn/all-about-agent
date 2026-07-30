# all-about-agent

## Cursor Cloud specific instructions

As of this writing, this repository is an empty placeholder: the only tracked
file is `README.md` (which contains just the project title). There is no
application code, no dependency manifest, no test suite, no linter, and no
build system yet.

Consequences for environment setup:

- There is nothing to install, lint, test, build, or run. No dev server or
  service exists.
- The startup update script is intentionally a no-op. Once real project
  files are added (for example a `package.json`, `pyproject.toml`,
  `requirements.txt`, `go.mod`, etc.), update the Cursor Cloud update script
  to install those dependencies (e.g. `npm install`, `pip install -r
  requirements.txt`, `uv sync`).
- System tooling already available on the VM includes Node.js (`v22.x`) and
  Python (`3.12.x`), so most JS/TS or Python projects can be bootstrapped
  without extra system-level installs.

When you add the first real code, also document here how to run/lint/test/build
each service (or point to the README / package scripts where those commands
live).
