## Configure o .vscode/settings.json

<pre>
  <code>
    {
      "workbench.colorTheme": "Dracula",
      "workbench.iconTheme": "material-icon-theme",
      "editor.formatOnSave": false,
      "eslint.format.enable": true,
      "git.autofetch": true,
      "security.workspace.trust.untrustedFiles": "open",
      "yaml.schemas": {
        "file:///c%3A/Users/Cliente/.vscode/extensions/atlassian.atlascode-2.9.1/resources/schemas/pipelines-schema.json": "bitbucket-pipelines.yml"
      },
      "atlascode.bitbucket.enabled": false,
      "workbench.startupEditor": "none",
      // Good for Recording
      // "editor.quickSuggestions": false,
      "editor.mouseWheelZoom": true,
      "editor.renderLineHighlight": "gutter",
      "breadcrumbs.enabled": true,
      "explorer.compactFolders": false,
      "window.titleBarStyle": "native", // "native" on Linux, "custom" on Windows
      "window.menuBarVisibility": "compact",
      // Disable JS auto-import behavior
      "javascript.updateImportsOnFileMove.enabled": "never",
      // Editor Behavior
      "editor.selectionClipboard": false, // Only for Linux
      "javascript.suggest.autoImports": false,
      "editor.suggestSelection": "first",
      "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true,
        "source.fixAll.tslint": true
      },

      // Explorer Behavior
      "explorer.confirmDragAndDrop": false,
      "explorer.confirmDelete": false,
      // Sets the Font size and family
      "editor.fontFamily": "Fira Code",
      "editor.fontWeight": "400",
      "editor.fontSize": 16,
      "editor.lineHeight": 20,
      "editor.fontLigatures": true,
      // Editor indentation settings
      "editor.tabSize": 2,
      "editor.insertSpaces": true,
      "editor.detectIndentation": true,
      // Auto applies editor rules for long lines of code
      "editor.rulers": [80, 120],
      // Increases terminal font size
      "terminal.integrated.fontSize": 14,
      // ESLint configuration
      "eslint.packageManager": "yarn",
      "eslint.codeActionsOnSave.mode": "all",
      "prettier.singleQuote": true,
      "prettier.trailingComma": "es5",
      "eslint.validate": [
      "javascript",
      "javascriptreact",
      "typescript",
      "typescriptreact"
      ],
      // Emmet
      "emmet.syntaxProfiles": {
      "javascript": "jsx" // Defines auto closing tags in JSX
      },
      "emmet.includeLanguages": {
      "javascript": "javascriptreact"
      },
      // Git settings
      "git.enableSmartCommit": true,
      "git.confirmSync": false,
      // Extensions
      "extensions.ignoreRecommendations": false, // Do not ignore recommendations
      // Colorize settings
      "colorize.languages": ["javascript", "typescript", "typescriptreact", "javascriptreact", "json", "html", "css"],
      // Peacock colors (customizable)
      "peacock.favoriteColors": [
      {
      "name": "Rocketseat Purple",
      "value": "#7159C1"
      },
      {
      "name": "Dracula Dark",
      "value": "#0B0A10"
      }
      ],
      // Pretier settings
      "[json]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
      },
      "[javascript]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
      },
      "[html]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
      },
      "[yaml]": {
      "editor.defaultFormatter": "dbaeumer.vscode-eslint"
      },
      "[typescriptreact]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
      },
      "[typescript]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
      },
      "sync.autoDownload": true,
      "sync.autoUpload": true,
      "sync.quietSync": true,
      "sync.gist": "5d025c8bfa361f3532735ea50f95a6a1",
      "bracket-pair-colorizer-2.colors": [
      "Gold",
      "Orchid",
      "LightSkyBlue"
      ],
      "cSpell.userWords": [
      "PAYPAL",
      "RCHLO",
      "Ruan",
      "grayscale",
      "mischka",
      "testid"
      ],
      "cSpell.language": "en,pt,pt-BR,en-US",
      "redhat.telemetry.enabled": true,
      "terminal.external.windowsExec": "C:\\Windows\\System32\\bash.exe",
      "window.zoomLevel": 1,
    }
  </code>
</pre>
