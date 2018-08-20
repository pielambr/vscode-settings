# Settings
```json
{
  "workbench.colorTheme": "Solarized Light",
  "editor.tabSize": 2,
  "workbench.startupEditor": "newUntitledFile",
  "workbench.editor.enablePreview": false,
  "rust.mode": "legacy",
  "go.gopath": "/Users/pieterjan/Documents/projects",
  "files.exclude": {
      "**/.git": true,
      "**/.svn": true,
      "**/.hg": true,
      "**/CVS": true,
      "**/.DS_Store": true,
      "**/node_modules/**": true
  },
  "[go]": {},
  "files.associations": {
      "*.css": "postcss",
      "*.axlsx": "ruby"
  },
  "css.validate": false,
  "less.validate": false,
  "scss.validate": false,
  "window.zoomLevel": 0,
  "workbench.iconTheme": "vscode-icons",
  "stylelint.configOverrides": {
      "ignoreFiles": ["**/*.js"],
  },
  "editor.acceptSuggestionOnCommitCharacter": false,
  "editor.acceptSuggestionOnEnter": "off"
}
```

# Extensions
Output via `code --list-extensions | xargs -L 1 echo code --install-extension`

```
code --install-extension CraigMaslowski.erb
code --install-extension HookyQR.beautify
code --install-extension ZakCodes.rust-snippets
code --install-extension bungcip.better-toml
code --install-extension dbaeumer.vscode-eslint
code --install-extension Hridoy.rails-snippets
code --install-extension ionut-botizan.theme-rusty-icons
code --install-extension kalitaalexey.vscode-rust
code --install-extension mikeburgh.xml-format
code --install-extension mikestead.dotenv
code --install-extension misogi.ruby-rubocop
code --install-extension monokai.theme-monokai-pro-vscode
code --install-extension ms-python.python
code --install-extension ms-vscode.Go
code --install-extension naumovs.color-highlight
code --install-extension rebornix.ruby
code --install-extension ricard.postcss
code --install-extension robertohuertasm.vscode-icons
code --install-extension ronnidc.nunjucks
code --install-extension rust-lang.rust
code --install-extension samuelcolvin.jinjahtml
code --install-extension shd101wyy.markdown-preview-enhanced
code --install-extension shinnn.stylelint
code --install-extension tommasov.hosts
code --install-extension wholroyd.jinja
code --install-extension wix.vscode-import-cost
```
