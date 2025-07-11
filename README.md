# 📦vscode-config

## Déscription

**vscode-config** est une repo qui contient ma configuration personnalisée et préférence concerant[Visual Studio Code](https://code.visualstudio.com/) visant à améliorer ma productivité, la lisibilité du code, et l’ergonomie générale.

## 🔧 Fonctionnalités

- 🎨 Thème personnalisé et police de programmation
- ⚙️ Fichier `settings.json` optimisé (auto-save, linting, format on save, etc.)
- 📁 Workspace presets
- ⌨️ Raccourcis clavier personnalisés
- 🧩 Liste d’extensions utiles (auto-installables)
- 📚 Snippets prédéfinis pour JS/TS, HTML, CSS, Python…

## 🚀 Installation

1. Clone le dépôt :

```bash
git clone https://github.com/votre-nom/vscode-config.git
```

2. Copie les fichiers dans ton dossier VS Code :

- **Linux/macOS**

  ```bash
  cp -r vscode-config/* ~/.config/Code/User/
  ```

- **Windows**

  ```powershell
  Copy-Item vscode-config\* "$env:APPDATA\Code\User\" -Recurse
  ```

3. (Optionnel) Installe les extensions listées :

```bash
cat extensions.json | xargs -L 1 code --install-extension
```

## 🛠️ Personnalisation

Tu peux adapter les fichiers `.json` pour ton environnement ou ajouter d'autres snippets dans le dossier `snippets/`.---
