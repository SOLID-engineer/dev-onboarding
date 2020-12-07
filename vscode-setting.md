# VSCODE Configuration

Below is the configuration for VSCode. Since we are working as a **team**, the workflow needs to be unified between developers.

1. Open your VSCODE
2. Press `CMD + P` (on *MacOS*) or `Ctrl + P` (on *Windows*) and type `>Preferences: Open Settings (JSON)`
3. Copy the configuration below and paste it into your setting window.

```
{
  "files.autoSave": "onFocusChange",
  "extensions.ignoreRecommendations": true,
  "editor.formatOnSave": true,
  "typescript.validate.enable": false,
  "typescript.suggestionActions.enabled": false,
  "typescript.format.enable": false,
  "javascript.validate.enable": false,
  "json.format.enable": false,
  "git.autofetch": true,
  "editor.renderWhitespace": "all",
  "editor.smoothScrolling": true,
  "workbench.tree.indent": 16,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
  },
  "files.associations": {
    "*.js": "javascriptreact",
  },
  "explorer.openEditors.visible": 10,
  "editor.minimap.renderCharacters": false,
  "editor.minimap.maxColumn": 200,
  "editor.minimap.showSlider": "always",
  "editor.cursorSmoothCaretAnimation": true,
  "files.insertFinalNewline": true,
  "files.trimTrailingWhitespace": true,
  "editor.tabSize": 2,
  "todohighlight.isEnable": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
  },
  "javascript.format.enable": false,
}
```
4. Save your file changes.
