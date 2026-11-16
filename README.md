# nur-packages

My [NUR](https://github.com/nix-community/NUR) repository.

| Package | What it is |
|---|---|
| [keybind-find](https://github.com/Benjmhart/keybind-find) | Search the keybindings for the focused window and run the one you pick |

```sh
nix-env -f '<nur>' -iA repos.benjmhart.keybind-find
```

Or with flakes, straight from upstream: `nix run github:Benjmhart/keybind-find`.

![Build and populate cache](https://github.com/Benjmhart/nur-packages/workflows/Build%20and%20populate%20cache/badge.svg)
