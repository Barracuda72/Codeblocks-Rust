# Codeblocks-Rust
Rust integration for Code::Blocks

This repository contains files required to work with Rust/Cargo projects and files in the Code::Blocks IDE.

# Installation
1. Download this repo as a ZIP archive
2. Extract it into Code::Blocks installation directory (C:\Program Files\Codeblocks or whatever on Windows, /usr/share/codeblocks on *nix)
3. In the templates/wizard/config.script file inside Code::Blocks installation directory find the function RegisterWizards and add the following:
```
RegisterWizard(wizProject,     _T("rust"),         _T("Rust Cargo project"),    _T("Console"));
RegisterWizard(wizFiles,       _T("rust_file"),    _T("Rust source"),           _T("Rust language"));
```
4. Enjoy!

# Disclaimer
I'm not affiliated in any way with Code::Blocks nor Rust. You are doing everything on you own risk. Pull requests are welcome.
