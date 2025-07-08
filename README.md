# ⚙️ .configs

Centralized configuration files for Python projects and VS Code environment

This repository contains a collection of shared configuration files for maintaining consistent development standards across all Python pet-projects.
It is designed to be added as a **Git submodule** in each repository where these configurations are needed.

## Initialization

Add submodule if it doesn't exist yet:
```bash
git submodule add https://github.com/AKrekhovetskyi/.configs.git
```

Initialize and update submodule on a cloned repo with a submodule:
```bash
git submodule update --init
```

For more details, read the official [Git Submodule documentation](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

## Usage

After the submodule is initialized successfully, create symlinks of configuration files. A command example:
```bash
ln -s .configs/.vscode/ .
```
