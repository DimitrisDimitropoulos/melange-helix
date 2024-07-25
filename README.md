# Melange Helix

This theme for the [helix](https://helix-editor.com/) editor is a port, with
some minor tweaks, of a great [nvim](https://neovim.io/) colorscheme called
[melange-nvim](https://github.com/savq/melange-nvim). The tweaks are an attempt
to better fit the theme into the helix tui.

## Usage

In order to use this theme you must install it manually into your helix configuration directory under the themes subdirectory. For your \*nix os you can do something like the following:

```sh
mkdir -p $XDG_CONFIG_HOME/helix/themes
git clone https://github.com/DimitrisDimitropoulos/melange-helix.git $XDG_CONFIG_HOME/helix/themes/
```

Make sure to restart helix and try to use it by:

```
:theme melange
```

## Showcase

![Rust code from helix core](./showcase_melange_helix.png)

## LICENSE

This project is distributed under the MIT license.
