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
    "console-ninja.featureSet": "Community",
    "editor.bracketPairColorization.enabled": true,
    /* Autocompletado de JavaScript, TypeScript y React */
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": "explicit",
        "source.sort.json": "always",
        "source.sortImports": "explicit"
    },
    "editor.cursorBlinking": "expand",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.cursorWidth": 4,
    "editor.fontFamily": "'Fira Code', menlo",
    "editor.fontLigatures": true,
    "editor.guides.bracketPairs": "active",
    "editor.guides.bracketPairsHorizontal": true,
    "editor.guides.highlightActiveBracketPair": true,
    "editor.guides.highlightActiveIndentation": true,
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
    "editor.suggest.preview": true,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "on",
    /* estilos de VS Code: temas, colores, etc  */
    "editor.tokenColorCustomizations": {
        "comments": "#e67e22"
    },
    "editor.wordBasedSuggestions": "matchingDocuments",
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
    /* extension de VS Code htmlhint - linter de HTML */
    "htmlhint.options": {
        "attr-lowercase": false,
        "attr-no-duplication": true,
        "attr-value-double-quotes": true,
        "doctype-first": false,
        "id-unique": true,
        "spec-char-escape": true,
        "src-not-empty": true,
        "tag-pair": true,
        "tagname-lowercase": false,
        "title-require": true
    },
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
    "tabnine.experimentalAutoImports": true,
    /* Tailwind */
    "tailwindCSS.experimental.configFile": "src/styles/global/tailwind.css", /* cambiar por la ruta donde se importa Tailwind 4 en archivo .css, necesario para q funcione auto-completado en Tailwind 4 */
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
    "terminal.integrated.env.windows": {},
    "typescript.npm": "C:\\Program Files\\nodejs\\npm.cmd",
    "typescript.updateImportsOnFileMove.enabled": "always",
    "workbench.activityBar.location": "hidden",
    "workbench.colorCustomizations": {
        "[Material Theme Ocean High Contrast]": {},
        "editorLineNumber.activeForeground": "#E34234",
        "editorLineNumber.foreground": "#FFFFFF"
    },
    "workbench.colorTheme": "Tokyo Night",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.tree.enableStickyScroll": true
}
```

# Atajos de VS Code

![extensiones_vs_code](/readme_img/1_atajo.PNG)

![extensiones_vs_code](/readme_img/2_atajo.PNG)

# Extensiones de VS Code

![extensiones_vs_code](/readme_img/extensiones_vs_code.png)
