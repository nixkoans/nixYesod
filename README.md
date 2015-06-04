# nixYesod

Nix environment for building yesod web components.

## How to?

1. In our user's nix environment, we first install yesod-bin -- this allows us to scaffold our yesod project.
2. Then write `shell.nix` and `default.nix`
3. Once done, running `nix-shell` will invoke `shell.nix`, that executes `default.nix` which contains all our yesod dependencies.
