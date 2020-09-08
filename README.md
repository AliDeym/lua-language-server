# GLua (Garry's Mod Lua) Language Server

![build](https://github.com/sumneko/lua-language-server/workflows/build/badge.svg)

This is a modified version of [lua-language-server](https://github.com/sumneko/lua-language-server/).

This version implements Garry's Mod lua completely, along with all the modifications of the language such as C style comments and C style operators (`&&, !, ||`).

Every documentation of Garry's Mod is already implemented. To generate the documentations, visit:

[glua-vscode-langserver-generator](https://github.com/AliDeym/glua-vscode-langserver-generator)

## Steps to produce:

- Install the latest version of stable Rust using Rustup.
- Run [glua-vscode-langserver-generator](https://github.com/AliDeym/glua-vscode-langserver-generator) using:
    - `cargo run`
- Install [lua-language-server](https://github.com/sumneko/lua-language-server/workflows/build/badge.svg).
- Download or clone this project, and extract it in your vscode extensions directory, inside `sumneko.lua-0.20.x/server` folder.
- Copy the generated language server files from your rust binary folder, into `server` directory.

**NOTE:** This project comes with a pre-configured language server documentation files, you may not need to install or run [glua-vscode-langserver-generator](https://github.com/AliDeym/glua-vscode-langserver-generator). But in case you want to have an updated documentation, then follow the instructions step by step, otherwise, skip the first two and last steps.