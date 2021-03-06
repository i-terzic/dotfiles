# Visual Studio Configuration

## Font

- 'iosevka','Anonymous Pro', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'
- Font size: 16

## Extensions

See full list in extensions.txt-file.

## Themes/Color

- One Dark Pro
- Material Icon Theme
- Bracket Pair Colorizer

## Workflow
 
- Auto Close Tag
- Auto Rename Tag

## Settings

### settings.json

```JSON
{
  "workbench.iconTheme": "material-icon-theme",
  "editor.fontFamily": "'iosevka','Anonymous Pro', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",

  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },

  "[python]": {
    "editor.defaultFormatter": "ms-python.python",
    "editor.tabSize": 4
  },
  "workbench.editorAssociations": {
    "*.ipynb": "jupyter-notebook"
  },
  "notebook.cellToolbarLocation": {
    "default": "right",
    "jupyter-notebook": "left"
  },
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "workbench.colorTheme": "One Dark Pro",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "[handlebars]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "debug.console.fontFamily": "Anonymous Pro,default",
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "files.exclude": {
    "**/.classpath": true,
    "**/.project": true,
    "**/.settings": true,
    "**/.factorypath": true
  },
  "terminal.integrated.profiles.linux": {
    "bash": {
      "path": "bash",
      "icon": "terminal-bash"
    },
    "zsh": {
      "path": "zsh"
    },
    "tmux": {
      "path": "tmux",
      "icon": "terminal-tmux"
    },
    "pwsh": {
      "path": "pwsh",
      "icon": "terminal-powershell"
    }
  },

  "redhat.telemetry.enabled": false,
  "workbench.editor.showTabs": true,
  "editor.cursorBlinking": "smooth",
  "editor.renderWhitespace": "none",
  "workbench.editor.enablePreview": true,
  "editor.codeActionsOnSave": {
    "source.organizeImports": true
  },
  "eslint.enable": true,
  "prettier.jsxSingleQuote": true,
  "prettier.singleQuote": true,
  "editor.fontSize": 16,
  "vetur.format.defaultFormatter.js": "none",

  "vetur.format.defaultFormatter.ts": "vscode-typescript"
}
```

### keybindings.json

```JSON
{
  "workbench.iconTheme": "material-icon-theme",
  "editor.fontFamily": "'iosevka','Anonymous Pro', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",

  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },

  "[python]": {
    "editor.defaultFormatter": "ms-python.python",
    "editor.tabSize": 4
  },
  "workbench.editorAssociations": {
    "*.ipynb": "jupyter-notebook"
  },
  "notebook.cellToolbarLocation": {
    "default": "right",
    "jupyter-notebook": "left"
  },
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "workbench.colorTheme": "One Dark Pro",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "[handlebars]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "debug.console.fontFamily": "Anonymous Pro,default",
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "files.exclude": {
    "**/.classpath": true,
    "**/.project": true,
    "**/.settings": true,
    "**/.factorypath": true
  },
  "terminal.integrated.profiles.linux": {
    "bash": {
      "path": "bash",
      "icon": "terminal-bash"
    },
    "zsh": {
      "path": "zsh"
    },
    "tmux": {
      "path": "tmux",
      "icon": "terminal-tmux"
    },
    "pwsh": {
      "path": "pwsh",
      "icon": "terminal-powershell"
    }
  },

  "redhat.telemetry.enabled": false,
  "workbench.editor.showTabs": true,
  "editor.cursorBlinking": "smooth",
  "editor.renderWhitespace": "none",
  "workbench.editor.enablePreview": true,
  "editor.codeActionsOnSave": {
    "source.organizeImports": true
  },
  "eslint.enable": true,
  "prettier.jsxSingleQuote": true,
  "prettier.singleQuote": true,
  "editor.fontSize": 16,
  "vetur.format.defaultFormatter.js": "none",

  "vetur.format.defaultFormatter.ts": "vscode-typescript"
}
```
