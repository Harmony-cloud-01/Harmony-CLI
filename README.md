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

Run from anywhere:
harmony --help

Option B — venv (development mode)

This keeps the CLI inside a local virtual environment. Useful if you want to develop or modify the CLI itself.

git clone https://github.com/Harmony-cloud-01/Harmony-CLI.git
cd Harmony-CLI

# create local venv
python3 -m venv .venv

# activate the environment
source .venv/bin/activate   # macOS/Linux
# .venv\Scripts\activate    # Windows PowerShell

# install in editable mode
pip install -e .

# run the CLI
harmony --help

Note: with venv, you must source .venv/bin/activate in every new terminal session.



Features
	•	CodexViewer → Retrieve Codex entries with RAG + aura filters
	•	Drift Logs → Track symbolic deltas, with auto-summary for SPs
	•	Context Layer Manager → Inject glyph states and SP resonance into prompts
	•	Audit Tools → Run glyph/mesh/SP health checks

⸻

Development
	•	Code lives under SDK/harmony_cli/
	•	Entry point is main.py
	•	Install locally with:

pip install -e .


