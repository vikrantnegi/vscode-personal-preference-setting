# VS Code Personal Setup

A personal list of [Visual Studio Code](https://code.visualstudio.com/) packages and resources to keep track of my personal setup.
For more, checkout [Awesome VS Code](https://github.com/viatsko/awesome-vscode)

# Table of Content

- [Extensions](#extensions)
- [Tools](#tools)
- [setting.json](#setting)

## Extensions

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Autoprefixer](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-autoprefixer)
- [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
- [Paste and Indent](https://marketplace.visualstudio.com/items?itemName=Rubymaniac.vscode-paste-and-indent)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [Sort Lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)
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


## Tools

[OpenInCode](https://github.com/sozercan/OpenInCode)


## Setting

To add the below setting go to `Code/File` → `Preferences` → `Settings`. It's easier to enter these settings while editing the `settings.json` file, so click the `{}` icon in the top right corner:

```markdown
{
"editor.fontSize": 16,
"editor.tabSize": 2,
"editor.lineHeight": 25,
"editor.letterSpacing": 0.5,
"editor.fontWeight": "400",
"editor.fontFamily": "Operator Mono, Menlo, Monaco, 'Courier New', monospace",
"editor.renderWhitespace": "boundary",
"editor.wordWrap": "on",
"editor.formatOnPaste": true,
"editor.mouseWheelZoom": false,
"files.trimTrailingWhitespace": true,
"workbench.colorTheme": "One Dark Pro",
"files.associations": {
"\*.scss.liquid": "scss"
},
"editor.dragAndDrop": true,
"editor.cursorBlinking": "solid",
"editor.codeLens": false,
"editor.multiCursorModifier": "ctrlCmd",
"window.nativeTabs": true,
//CSS
// No unit for zero needed
"css.lint.zeroUnits": "warning",
"css.lint.idSelector": "warning",

//SCSS
// No unit for zero needed
"scss.lint.zeroUnits": "warning",
"scss.lint.idSelector": "warning",

//intellisense plugin setting
"path-intellisense.extensionOnImport": true,
"path-intellisense.showHiddenFiles": true,
"path-intellisense.autoSlashAfterDirectory": true,

"workbench.colorCustomizations":{
"tab.activeBackground": "#232833",
"activityBar.background": "#282c34",
"editorGroup.background": "#282c34",
"sideBar.background": "#282c34"
},
"window.zoomLevel": 0,

// Allows to display errors.
"scss.showErrors": false,

// Add vendor prefixes to CSS when you save a file.
"autoprefixer.formatOnSave": false,
"liveServer.settings.donotShowInfoMsg": true,
"prettier.eslintIntegration": true,
"emmet.syntaxProfiles": {
"javascript": "jsx"
},
"workbench.startupEditor": "newUntitledFile",
"workbench.fontAliasing": "auto",
"editor.formatOnSave": true,
"[javascript]": {
"editor.formatOnSave": false
},
"eslint.autoFixOnSave": true,
"prettier.disableLanguages": ["js"],
"editor.tabCompletion": "on",
"prettier.stylelintIntegration": true,
"window.clickThroughInactive": false,
"breadcrumbs.enabled": true,
}
```

## License

Licensed under the [MIT](https://github.com/vikrantnegi/vscode-personal-preference-setting/blob/master/LICENSE).
