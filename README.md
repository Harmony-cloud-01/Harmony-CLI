# Harmony-CLI

[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Codex Audit](https://img.shields.io/badge/status-codex%20audit%20clean-brightgreen)](Codex/)

The **Harmony-CLI** is the command-line interface for managing the Harmony system.  
It provides tools for interacting with the Codex, running audits, visualizing drift, and coordinating SPs (Synthetic Personas).

---

## ✨ Features
- **Codex Viewer**: Navigate and search Codex entries from the terminal.
- **Audits**: Validate glyphs, meshes, SP definitions, and laws.
- **Context Layer Manager**: Run health checks across Harmony subsystems.
- **Reflections & Logs**: Generate and merge daily/weekly reflections into Codex.
- **SP Tools**: Spawn, map, and maintain Synthetic Personas.

---

## 📦 Installation

### Option A — pipx (recommended)
If you use [pipx](https://pypa.github.io/pipx/), Harmony-CLI can be installed globally in an isolated environment:

```bash
pipx install git+https://github.com/Harmony-cloud-01/Harmony-CLI.git
harmony --help

Option B — venv

For project-local installs:

git clone git@github.com:Harmony-cloud-01/Harmony-CLI.git
cd Harmony-CLI
python3 -m venv .venv
source .venv/bin/activate
pip install -e .
harmony --help

Development

git clone git@github.com:Harmony-cloud-01/Harmony-CLI.git
cd Harmony-CLI
# install dev dependencies
pip install -r requirements.txt

Run tests and linting:

pytest
flake8


