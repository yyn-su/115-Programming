# AGENTS.md

- 回應一律使用繁體中文。
- 程式語言為 Python；以 conda 管理套件，環境名稱為 `iem_python`（例：`conda run -n iem_python python <file>`、`conda install -n iem_python <pkg>`）。
- Empty course codebase (`115-1 computer programming`). Only `README.md` + Python `.gitignore` exist; no source, manifests, tests, lint, CI, or OpenCode config yet.

- Language: Python (per `.gitignore`). No toolchain, dependencies, or build/test commands established — do not assume pytest, ruff, venv, or package layout.
- If adding Python code: use stdlib only unless user requests otherwise; verify with `conda run -n iem_python python <file>` or `conda run -n iem_python python -m py_compile <file>`.
- Keep new files course-sized and dependency-free; don't scaffold monorepo tooling, CI, or formatters unprompted.
