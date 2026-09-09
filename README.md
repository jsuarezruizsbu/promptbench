# promptbench

Tiny eval harness: run prompt cases, score, compare

## Examples

```bash
python evals.py
# edit cases.json, point run() at your agent
```

## What it does

- Exit code usable as a CI gate
- Swap in any agent function via one line
- Cases defined in plain JSON
- Keyword scoring + latency per case

## Install

```bash
# stdlib only, nothing to install
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── cases.json
└── evals.py
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## License

MIT licensed, see LICENSE.
