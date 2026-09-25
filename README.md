# project_research_agent
LangGraph Full Project Research Agent

```
mkdir src

"pyproject.toml", ".gitignore", ".env" | ForEach-Object {
New-Item -ItemType File -Path $_ -Force
}

python -m venv .venv

.venv\Scripts\Activate.ps1

pip install -e . 
```