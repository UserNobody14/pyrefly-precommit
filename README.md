# Pyrefly Pre-commit Hooks

This repository contains pre-commit hooks for pyrefly.

## Installation

```yaml
  - repo: https://github.com/UserNobody14/pyrefly-precommit
    rev: '0.0.2'
    hooks:
      - id: pyrefly
        args: ["--python-interpreter", ".venv/bin/python3"]
```

## Usage

```bash
pre-commit run --all-files
```