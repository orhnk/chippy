# Chippy

My Notes about everything!

## Dwm (Window manager)

- Very nice UI using siduck/chadwm fastest wm I have ever seen

## Picom (X compositor)

- Everyone uses it, so I do. Here is the window manager
  [fork/branch](https://github.com/dccsillag/picom/tree/implement-window-animations)

## Neovim (That Editor)

- Using siduck/NvChad: not bloated

# Terminal

## Showkey

use following command to see what is the escape code of a shortcut:

```shell
showkey -a
```

# Disk Scanner

- dua-rs: fast & solid disk scanner written in rust

# Kobo

## Cannot read billingual books?

Downlaod [Go Noto Fonts](https://github.com/satbyy/go-noto-universal) which will fix misrendered fonts. Place it under the `fonts/` at the root folder of your reader, mounted.

# OS

## NixOS

### Absolute path to a package

after installing perf tools to nixos as in my dotnix repo, I needed to find absolute path to it.
Searching a bit shows that It's in `/etc/profiles/per-user/bin/` + `perf`

# Programming languages

## Rust

### Cargo

use the following for smaller target dirs:

```toml
strip = true
```
