# ai-agents-from-scratch
labs from langchain academy


# Install uv if you haven't already
pip install uv
uv venv
# Activate the virtual environment
source .venv/bin/activate
# toml 
uv init --bare
copy from https://raw.githubusercontent.com/langchain-ai/agents-from-scratch/refs/heads/main/pyproject.toml 

# Install the package with development dependencies
uv sync --extra dev
