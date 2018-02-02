# VSCode

Copy paste settings for setting up VS Code on a new machine.

## Settings for VS Code

```
{
  "editor.formatOnSave": true,
  "editor.scrollBeyondLastLine": false,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "es5",
  "editor.tabSize": 2,
  "workbench.colorTheme": "Material Theme",
  "files.exclude": {
    "node_modules": true,
    "package-lock.json": true,
    "dist": true,
    "coverage": true
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "graphql",
    { "language": "typescript", "autoFix": true },
    { "language": "typescriptreact", "autoFix": true }
  ],
  "materialTheme.cache.workbench.settings": {
    "themeColours": "Palenight"
  },
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false
}
```

And install eslint, prettier, material theme
