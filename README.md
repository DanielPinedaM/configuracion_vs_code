# Archivo settings.json para configurar VS Code

```javascript
{
    "[css]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[json]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[jsonc]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[scss]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "code-runner.executorMap": {
        "ahk": "autohotkey",
        "applescript": "osascript",
        "autoit": "autoit3",
        "bat": "cmd /c",
        "clojure": "lein exec",
        "coffeescript": "coffee",
        "csharp": "scriptcs",
        "d": "cd $dir && dmd $fileName && $dir$fileNameWithoutExt",
        "dart": "dart",
        "fortran": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fortran-modern": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fortran_fixed-form": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "FortranFreeForm": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fsharp": "fsi",
        "haskell": "runhaskell",
        "haxe": "haxe --cwd $dirWithoutTrailingSlash --run $fileNameWithoutExt",
        "html": "\"C:\\Program Files (x86)\\Google\\Chrome\\Application\\chrome.exe\"",
        "javascript": "node",
        "kit": "kitc --run",
        "less": "cd $dir && lessc $fileName $fileNameWithoutExt.css",
        "lisp": "sbcl --script",
        "nim": "nim compile --verbosity:0 --hints:off --run",
        "powershell": "powershell -ExecutionPolicy ByPass -File",
        "python": "python -u",
        "racket": "racket",
        "sass": "sass --style expanded",
        "scheme": "csi -script",
        "scss": "scss --style expanded",
        "shellscript": "bash",
        "typescript": "ts-node",
        "v": "v run",
        "vbscript": "cscript //Nologo"
    },
    /* code-runner: ejecutar codigo */
    "code-runner.runInTerminal": true,
    "code-runner.saveAllFilesBeforeRun": true,
    "editor.bracketPairColorization.enabled": true,
    "editor.cursorBlinking": "expand",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.cursorWidth": 4,
    "editor.fontFamily": "'Fira Code', menlo",
    "editor.fontLigatures": true,
    "editor.guides.bracketPairs": "active",
    "editor.guides.bracketPairsHorizontal": true,
    "editor.linkedEditing": true,
    "editor.minimap.enabled": false,
    "editor.parameterHints.enabled": true,
    "editor.quickSuggestions": {
        "comments": false,
        "other": true,
        "strings": true
    },
    "editor.quickSuggestionsDelay": 1,
    "editor.renderWhitespace": "all",
    "editor.stickyScroll.enabled": true,
    "workbench.tree.enableStickyScroll": true,
    "editor.suggest.preview": true,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "on",
    /* estilos de VS Code: temas, colores, etc  */
    "editor.tokenColorCustomizations": {
        "comments": "#e67e22"
    },
    "editor.wordBasedSuggestions": "matchingDocuments",
    "editor.wordBasedSuggestionsMode": "allDocuments",
    "emmet.includeLanguages": {
        "javascript": "javascriptreact",
        "jsx-sublime-babel-tags": "javascriptreact",
        "typescript": "typescriptreact"
    },
    "emmet.triggerExpansionOnTab": true,
    "eslint.options": {
        "extensions": [
            ".js",
            ".ts",
            ".jsx",
            ".tsx"
        ]
    },
    "eslint.validate": [
        "javascript",
        "typescript",
        "jsx",
        "javascriptreact",
        "typescriptreact"
    ],
    /* Otros */
    "files.hotExit": "off",
    "git-graph.integratedTerminalShell": "C:\\Program Files\\Git\\bin\\bash.exe",
    "git.autofetch": true,
    /* Git y GitHub */
    "gitlens.advanced.messages": {
        "suppressCommitHasNoPreviousCommitWarning": true
    },
    "gitlens.views.branches.branches.layout": "list",
    "headwind.prependCustomClasses": true,
    //"typescript.suggest.completeFunctionCalls": true,
    "intellicodeCompletions.language.javascript": true,
    "intellicodeCompletions.language.typescript": true,
    // "typescript.inlayHints.enumMemberValues.enabled": true,
    // "typescript.inlayHints.functionLikeReturnTypes.enabled": true,
    // "typescript.inlayHints.parameterNames.enabled": "all",
    // "typescript.inlayHints.propertyDeclarationTypes.enabled": true,
    // "typescript.inlayHints.parameterTypes.enabled": true,
    // "typescript.inlayHints.variableTypes.enabled": true,
    "javascript.suggest.completeFunctionCalls": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "js/ts.implicitProjectConfig.checkJs": true,
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": "explicit",
        "source.sortImports": "explicit"
    },
    "json.sortOnSave.enable": true,
    "liveServer.settings.donotShowInfoMsg": true,
    "prettier.arrowParens": "always",
    "prettier.bracketSameLine": false,
    "prettier.bracketSpacing": true,
    /* Prettier: formateador de codigo */
    "prettier.editor.defaultFormatter": "esbenp.prettier-vscode",
    "prettier.embeddedLanguageFormatting": "auto",
    "prettier.htmlWhitespaceSensitivity": "css",
    "prettier.insertPragma": false,
    "prettier.jsxSingleQuote": true,
    "prettier.printWidth": 100,
    "prettier.proseWrap": "preserve",
    "prettier.quoteProps": "as-needed",
    "prettier.requirePragma": false,
    "prettier.semi": true,
    "prettier.singleQuote": true,
    "prettier.tabWidth": 2,
    "prettier.trailingComma": "es5",
    "prettier.useTabs": false,
    "prettier.vueIndentScriptAndStyle": false,
    /* Autocompletado de JavaScript, TypeScript y React */
    "tabnine.experimentalAutoImports": true,
    /* Tailwind */
    "tailwindCSS.emmetCompletions": true,
    "tailwindCSS.includeLanguages": {
        "javascript": "javascript",
        "javascriptreact": "javascriptreact",
        "plaintext": "html",
        "typescript": "typescript",
        "typescriptreact": "typescriptreact"
    },
    "terminal.explorerKind": "external",
    "terminal.integrated.defaultProfile.windows": "Git Bash",
    "typescript.npm": "C:\\Program Files\\nodejs\\npm.cmd",
    "typescript.updateImportsOnFileMove.enabled": "always",
    "workbench.colorCustomizations": {
        "[Material Theme Ocean High Contrast]": {},
        "editorLineNumber.activeForeground": "#E34234",
        "editorLineNumber.foreground": "#FFFFFF"
    },
    "workbench.colorTheme": "Material Theme Ocean High Contrast",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.activityBar.location": "hidden",
    "terminal.integrated.env.windows": {},
    "console-ninja.featureSet": "Community",
    "window.zoomLevel": 1,
}
```

# Atajos de VS Code

![extensiones_vs_code](/readme_img/1_atajo.PNG)

![extensiones_vs_code](/readme_img/2_atajo.PNG)

# Extensiones de VS Code

![extensiones_vs_code](/readme_img/extensiones_vs_code.png)
