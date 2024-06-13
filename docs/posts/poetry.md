---
date: 2024-06-13
categories:
  - Python
---

# poetry

[https://python-poetry.org/](https://python-poetry.org/)

先裝 pipx，再透過 pipx 安裝 poetry。

安裝：

```
pipx install poetry
```

* Linux & macOS 皆安裝至 `~/.local/bin/poetry`

Venv 路徑：

* macOS: `/Users/roy/Library/Caches/pypoetry/virtualenvs`

```
poetry new poetry-demo
poetry add click
poetry add --group dev ruff
poetry remove --group dev ruff
```

顯示 venv 的實際路徑：
```
poetry shell
```

```
poetry build
```
