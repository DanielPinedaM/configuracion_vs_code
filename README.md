# Archivo settings.json para configurar VS Code

```javascript
{
    /* Prettier: formateador de codigo */
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
    "prettier.arrowParens": "always",
    "prettier.bracketSameLine": false,
    "prettier.bracketSpacing": true,
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

    /* code-runner: ejecutar codigo */
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
    "code-runner.runInTerminal": true,
    "code-runner.saveAllFilesBeforeRun": true,

    /* estilos de VS Code: temas, colores, etc  */
    "editor.tokenColorCustomizations": {
        "comments": "#e67e22"
    },
    "workbench.colorCustomizations": {
        "[Material Theme Ocean High Contrast]": {},
        "editorLineNumber.activeForeground": "#E34234",
        "editorLineNumber.foreground": "#FFFFFF"
    },
    "editor.renderWhitespace": "all",
    "editor.stickyScroll.enabled": true,
    "editor.parameterHints.enabled": true,
    "editor.minimap.enabled": false,
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.cursorWidth": 4,
    "editor.fontFamily": "'Fira Code', menlo",
    "editor.fontLigatures": true,
    "editor.bracketPairColorization.enabled": true,
    "editor.cursorBlinking": "expand",
    "editor.wordBasedSuggestions": "matchingDocuments",
    "editor.guides.bracketPairs": "active",
    "editor.guides.bracketPairsHorizontal": true,
    "editor.guides.highlightActiveBracketPair": true,
    "editor.guides.highlightActiveIndentation": true,
    "workbench.colorTheme": "Tokyo Night",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.tree.enableStickyScroll": true,
    "typescript.updateImportsOnFileMove.enabled": "always",
    "workbench.activityBar.location": "hidden",

    /* Git y GitHub */
    "gitlens.advanced.messages": {
        "suppressCommitHasNoPreviousCommitWarning": true
    },
    "gitlens.views.branches.branches.layout": "list",
    "git-graph.integratedTerminalShell": "C:\\Program Files\\Git\\bin\\bash.exe",
    "git.autofetch": true,

    /* Autocompletado de JavaScript, TypeScript y React */
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": "explicit",
        "source.sort.json": "always",
        "source.sortImports": "explicit"
    },
    "editor.quickSuggestions": {
        "comments": false,
        "other": true,
        "strings": true
    },
    "editor.linkedEditing": true,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "on",
    "editor.quickSuggestionsDelay": 1,
    "editor.suggest.preview": true,
    "tabnine.experimentalAutoImports": true,
    "console-ninja.featureSet": "Community",
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

    /* emmet */
    "emmet.includeLanguages": {
        "javascript": "javascriptreact",
        "jsx-sublime-babel-tags": "javascriptreact",
        "typescript": "typescriptreact"
    },
    "emmet.triggerExpansionOnTab": true,

    /* eslint */
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

    /* Tailwind */
    "tailwindCSS.emmetCompletions": true,
    "tailwindCSS.includeLanguages": {
        "javascript": "javascript",
        "javascriptreact": "javascriptreact",
        "plaintext": "html",
        "typescript": "typescript",
        "typescriptreact": "typescriptreact"
    },
    "headwind.prependCustomClasses": true,

    /* Otros */
    "files.hotExit": "off",
    "terminal.explorerKind": "external",
    "terminal.integrated.defaultProfile.windows": "Git Bash",
    "terminal.integrated.env.windows": {},
    "typescript.npm": "C:\\Program Files\\nodejs\\npm.cmd",
    "liveServer.settings.donotShowInfoMsg": true,
}
```

# Atajos de VS Code

![extensiones_vs_code](/readme_img/1_atajo.PNG)

![extensiones_vs_code](/readme_img/2_atajo.PNG)

# Extensiones de VS Code

![extensiones_vs_code](/readme_img/extensiones_vs_code.png)
