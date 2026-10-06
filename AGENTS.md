# AGENTS.md

- 回應一律使用繁體中文。
- 程式語言為 Python；以 conda 管理套件，環境名稱為 `iem_python`（例：`conda run -n iem_python python <file>`、`conda install -n iem_python <pkg>`）。
- Empty course codebase (`115-1 computer programming`). Only `README.md` + Python `.gitignore` exist; no source, manifests, tests, lint, CI, or OpenCode config yet — do not assume pytest, ruff, venv, or package layout.
- 新增程式碼僅用 stdlib（除非另有要求）；驗證用 `conda run -n iem_python python <file>` 或 `conda run -n iem_python python -m py_compile <file>`；保持課程規模、無依賴，勿擅自搭建 monorepo、CI 或 formatter。
