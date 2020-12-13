# NeoVim config.

My NeoVim settings with built-in LSP support.

## features
Built-in LSP support.
floaterm
fzf
telescope
...

Reference:
https://github.com/awesome-streamers/awesome-streamerrc
https://github.com/theniceboy/nvim
https://github.com/ChristianChiarulli/nvim

## LSP server install.
Refer to https://github.com/neovim/nvim-lspconfig

### vim
npm install -g vim-language-server

### lua
Run cmd :LspInstallInfo sumneko_lua.

### python
pip3 install python-language-server

### java
Run cmd :LspInstall jdtls. Need java 11 to run jdtls plugin.

### typescript
npm install -g typescript-language-server
or
:LspInstall tsserver



