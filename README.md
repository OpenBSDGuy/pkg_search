# pkg_search ⚡

Blazing fast intuitive search for OpenBSD packages.

<p align="center">
  <img width="400" height="335" src="https://github.com/OpenBSDGuy/pkg_search/raw/master/assets/screenshot.png">
</p>

## Dependencies

`pkg_search` is dependent on two packages `pkglocate` and `fzf`. Install them by running,

```bash
$ doas pkg_add pkglocatedb fzf
```

## Installation

```bash
$ curl -sL https://raw.githubusercontent.com/OpenBSDGuy/pkg_search/master/pkg_search > "$HOME/.local/bin/pkg_search" && chmod a+x "$HOME/.local/bin/pkg_search"
```

## Uninstallation

```bash
$ rm "$HOME/.local/bin/pkg_search" && doas pkg_delete pkglocatedb fzf
```

## More info

For more info refer to `--help` or this YouTube video: https://www.youtube.com/watch?v=KwLshLgGWS0
