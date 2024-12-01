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

## Converting E-Book Formats

### PDF to EPUB

Converting pdfs may become complex, especially with non-plain-text pdf files. If your pdf's structure is simple, using calibre convertion tools or some site like cloud convert would work fine. But if the structure is full of images and such, these options may not convert them correctly (e.g images may appear black). For those situations I found that [this site](https://www.cleverpdf.com/downToEpub) works, from [a commment from reddit](https://www.reddit.com/r/zlibrary/comments/15baklx/comment/kcwsb2m/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button).

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
