# VS Code Personal Setup

A personal list of [Visual Studio Code](https://code.visualstudio.com/) packages and resources to keep track of my personal setup.
For more, checkout [Awesome VS Code](https://github.com/viatsko/awesome-vscode)

# Table of Content

- [Theme](#theme)
- [Extensions](#extensions)
- [Tools](#tools)
- [setting.json](#setting)

# Theme

- [Moonlight](https://marketplace.visualstudio.com/items?itemName=atomiks.moonlight)

## Extensions

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Paste and Indent](https://marketplace.visualstudio.com/items?itemName=Rubymaniac.vscode-paste-and-indent)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)
- [SCSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-scss)
- [Placeholder Images](https://marketplace.visualstudio.com/items?itemName=JakeWilson.vscode-placeholder-images)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Prettier - JavaScript formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets)
- [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [Polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)
- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [Color Highlight](https://github.com/vikrantnegi/vscode-personal-preference-setting.git)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
- [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
- [TabNine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)

## Tools

[OpenInCode](https://github.com/sozercan/OpenInCode)

## Setting

To add the below setting go to `Code/File` → `Preferences` → `Settings`. It's easier to enter these settings while editing the `settings.json` file, so click the `{}` icon in the top right corner:

```markdown
{
// Place your settings in this file to overwrite the default settings
"editor.fontSize": 16,
"editor.tabSize": 2,
"editor.lineHeight": 25,
"editor.letterSpacing": 0.5,
"editor.fontWeight": "400",
"editor.fontFamily": "Operator Mono, Menlo, Monaco, 'Courier New', monospace",
"editor.renderWhitespace": "all",
"editor.wordWrap": "on",
"editor.formatOnPaste": true,
"editor.mouseWheelZoom": false,
"files.trimTrailingWhitespace": true,
"files.associations": {
"_.scss.liquid": "scss",
"_.liquid": "html"
},
"editor.dragAndDrop": true,
"editor.cursorBlinking": "solid",
"editor.codeLens": false,
"editor.multiCursorModifier": "ctrlCmd",
"window.nativeTabs": true,
//intellisense plugin setting
"path-intellisense.extensionOnImport": true,
"path-intellisense.showHiddenFiles": true,
"path-intellisense.autoSlashAfterDirectory": true,
"workbench.colorCustomizations": {
"tab.activeBackground": "#232833",
"activityBar.background": "#282c34",
"sideBar.background": "#282c34"
},
"window.zoomLevel": 0,
"emmet.syntaxProfiles": {
"javascript": "jsx"
},
"colorize.languages": ["javascript", "javascriptreact"],
"workbench.startupEditor": "newUntitledFile",
"workbench.fontAliasing": "auto",
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.formatOnSave": true,
"[javascript]": {
"editor.formatOnSave": false
},
"[javascriptreact]": {
"editor.formatOnSave": false
},
"prettier.disableLanguages": ["javascript", "javascriptreact"],
"editor.tabCompletion": "on",
"window.clickThroughInactive": false,
"breadcrumbs.enabled": true,
"css.validate": false,
"scss.validate": false,
"sync.autoDownload": true,
"sync.autoUpload": true,
"sync.lastDownload": "",
"sync.forceDownload": false,
"sync.anonymousGist": false,
"sync.host": "",
"sync.pathPrefix": "",
"sync.quietSync": false,
"sync.askGistName": false,
"editor.snippetSuggestions": "top",
"sync.removeExtensions": true,
"sync.syncExtensions": true,
"terminal.integrated.rendererType": "dom",
"files.autoSave": "off",
"javascript.updateImportsOnFileMove.enabled": "always",
"workbench.colorTheme": "Moonlight II",
"editor.suggestSelection": "first",
"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
"files.exclude": {
"**/.classpath": true,
"**/.project": true,
"**/.settings": true,
"**/.factorypath": true
},
"java.errors.incompleteClasspath.severity": "ignore",
"sync.forceUpload": true,
"prettier.useEditorConfig": false,
"prettier.vueIndentScriptAndStyle": true,
"cSpell.userWords": [
"dayjs",
"flexbox"
],
"editor.codeActionsOnSave": {
"source.fixAll.eslint": true
},
"java.semanticHighlighting.enabled": true,
"tabnine.experimentalAutoImports": true
}
```

## License

Licensed under the [MIT](https://github.com/vikrantnegi/vscode-personal-preference-setting/blob/master/LICENSE).
