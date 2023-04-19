A personal code snippet collection, mainly for TypeScript, Rust and Dart.

This is meant for personal use, so it is expected to be incomplete.

Some snippets are from other open source repositories, such as [friendly-snippets](https://github.com/rafamadriz/friendly-snippets) and [flutter-riverpod-snippets](https://github.com/RobertBrunhage/flutter-riverpod-snippets).

So feel free to use or modify the codebase if you want.

For neovim, clone the repo into your local machine, and use [Luasnip](https://github.com/L3MON4D3/LuaSnip) to load the snippets:

```lua
require("luasnip.loaders.from_vscode").lazy_load({paths = "path/to/your/snippets/folder"})
```

For VS Code, you need to install the `vsce` npm package globally with:

```bash
npm install --global @vscode/vsce
```

and then clone the repo, and build it into extension via:

```bash
cd snippets
npm run build
```

then in your VS Code, click extensions tab, click the top right icon, then click `install from VSIX` to select the extension file.
