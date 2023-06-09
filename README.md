# Archivo settings.json para configurar Visual Studio Code

```javascript
{
    /* Prettier: formateador de codigo */
    "prettier.editor.defaultFormatter": "esbenp.prettier-vscode",
    "prettier.arrowParens": "always",
    "prettier.bracketSameLine": false,
    "prettier.bracketSpacing": true,
    "prettier.embeddedLanguageFormatting": "auto",
    "prettier.htmlWhitespaceSensitivity": "css",
    "prettier.insertPragma": false,
    "prettier.jsxSingleQuote": true,
    "prettier.proseWrap": "preserve",
    "prettier.quoteProps": "as-needed",
    "prettier.requirePragma": false,
    "prettier.semi": true,
    "prettier.singleQuote": true,
    "prettier.tabWidth": 2,
    "prettier.trailingComma": "es5",
    "prettier.useTabs": false,
    "prettier.vueIndentScriptAndStyle": false,
    "prettier.printWidth": 100,
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[jsonc]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },

    /* Autocompletado de JavaScript, TypeScript y React */
    "tabnine.experimentalAutoImports": true,

    "editor.tabCompletion": "on",
    "editor.wordBasedSuggestionsMode": "allDocuments",
    "editor.quickSuggestionsDelay": 1,
    "editor.wordBasedSuggestions": true,
    "editor.parameterHints.enabled": true,
    "editor.suggest.preview": true,

    "emmet.includeLanguages": {
        "javascript": "javascriptreact",
        "typescript": "typescriptreact",
        "jsx-sublime-babel-tags": "javascriptreact",
    },
    "emmet.triggerExpansionOnTab": true,

    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true,
        "source.sortImports": true,
    },

    "eslint.options": {
        "extensions":  [".js", ".ts", ".jsx", ".tsx"]
    },
    "eslint.validate": ["javascript", "typescript", "jsx", "javascriptreact", "typescriptreact"],

    "typescript.npm": "C:\\Program Files\\nodejs\\npm.cmd",

    "js/ts.implicitProjectConfig.checkJs": true,

    // "typescript.inlayHints.enumMemberValues.enabled": true,
    // "typescript.inlayHints.functionLikeReturnTypes.enabled": true,
    // "typescript.inlayHints.parameterNames.enabled": "all",
    // "typescript.inlayHints.propertyDeclarationTypes.enabled": true,
    // "typescript.inlayHints.parameterTypes.enabled": true,
    // "typescript.inlayHints.variableTypes.enabled": true,

    "javascript.suggest.completeFunctionCalls": true,
    //"typescript.suggest.completeFunctionCalls": true,

    "intellicodeCompletions.language.javascript": true,
    "intellicodeCompletions.language.typescript": true,

    "editor.quickSuggestions": {
        "other": true,
        "comments": false,
        "strings": true
    },

    "editor.suggestSelection": "first",

    /* code-runner: ejecutar codigo */
    "code-runner.runInTerminal": true,
    "code-runner.saveAllFilesBeforeRun": true,
    "code-runner.executorMap": {
        "html": "\"C:\\Program Files (x86)\\Google\\Chrome\\Application\\chrome.exe\"",
        "javascript": "node",
        "python": "python -u",
        "powershell": "powershell -ExecutionPolicy ByPass -File",
        "bat": "cmd /c",
        "shellscript": "bash",
        "fsharp": "fsi",
        "csharp": "scriptcs",
        "vbscript": "cscript //Nologo",
        "typescript": "ts-node",
        "coffeescript": "coffee",
        "applescript": "osascript",
        "clojure": "lein exec",
        "haxe": "haxe --cwd $dirWithoutTrailingSlash --run $fileNameWithoutExt",
        "racket": "racket",
        "scheme": "csi -script",
        "ahk": "autohotkey",
        "autoit": "autoit3",
        "dart": "dart",
        "d": "cd $dir && dmd $fileName && $dir$fileNameWithoutExt",
        "haskell": "runhaskell",
        "nim": "nim compile --verbosity:0 --hints:off --run",
        "lisp": "sbcl --script",
        "kit": "kitc --run",
        "v": "v run",
        "sass": "sass --style expanded",
        "scss": "scss --style expanded",
        "less": "cd $dir && lessc $fileName $fileNameWithoutExt.css",
        "FortranFreeForm": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fortran-modern": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fortran_fixed-form": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fortran": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt"
    },

    /* Git y GitHub */
    "gitlens.advanced.messages": {
        "suppressCommitHasNoPreviousCommitWarning": true
    },
    "git.autofetch": true,
    "gitlens.views.branches.branches.layout": "list",

    /* estilos de VS Code: temas, colores, etc  */
    "editor.tokenColorCustomizations": {
        "comments": "#e67e22"
    },
    "editor.guides.bracketPairsHorizontal": true,
    "editor.renderWhitespace": "all",
    "editor.fontLigatures": true,
    "editor.fontFamily": "'Fira Code', menlo",
    "editor.cursorBlinking": "expand",
    "editor.cursorWidth": 4,
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs": "active",
    "editor.stickyScroll.enabled": true,
    "editor.minimap.enabled": false,

    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Material Theme Ocean High Contrast",
    "workbench.colorCustomizations": {
        "editorLineNumber.activeForeground": "#E34234",
        "editorLineNumber.foreground": "#FFFFFF",
        "[Material Theme Ocean High Contrast]": {}
    },

    /* Tailwind */
    "tailwindCSS.emmetCompletions": true,
    "tailwindCSS.includeLanguages": {
        "plaintext": "html",
        "javascript": "javascript",
        "javascriptreact": "javascriptreact",
        "typescript": "typescript",
        "typescriptreact": "typescriptreact",
    },

    /* Otros */
    "files.hotExit": "off",
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
    "liveServer.settings.donotShowInfoMsg": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "terminal.integrated.tabs.enabled": false,
    "editor.linkedEditing": true,
    "editor.cursorSmoothCaretAnimation": "on",
    "headwind.prependCustomClasses": true,
    "workbench.activityBar.visible": false,
    "window.zoomLevel": 2,
}
```
