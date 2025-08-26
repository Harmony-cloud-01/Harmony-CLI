# Harmony CLI

The **Harmony CLI** is the entrypoint for interacting with the Harmony Codex, symbolic layers, and context-engine features (CodexViewer, Drift Logs, SP orchestration).

---

## Requirements
- Python 3.11+
- macOS / Linux recommended (Windows supported with PowerShell)
- `git` installed

---

## Installation

### Option A — pipx (recommended)
This installs the CLI in an isolated global environment, callable from anywhere:

```bash
pip install pipx
pipx ensurepath

git clone https://github.com/Harmony-cloud-01/Harmony-CLI.git
cd Harmony-CLI

pipx install .
