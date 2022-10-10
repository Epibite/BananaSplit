## Scripts to generate coding style reports

The script display a colored output on the terminal (inspired by [Abricot-Norminette](https://github.com/Just1truc/Abricot-Norminette)).

### Linux

Requirement :

- [Docker](https://docs.docker.com/engine/install/) installed
- [Curl](https://curl.se/download.html) installed

Use `coding-style.sh`

By default the script doesn't update the docker. Be sure to check for update
every time before the end of a project with the argument `-u`.

This script is delivered "as is" without any warranty.

A part of the source code comes from [Epitech](https://github.com/Epitech).

In memoriam of [Abricot-Norminette](https://github.com/Just1truc/Abricot-Norminette).

If using Nix, you can run `nix run github:epitech/coding-style-checker` to run a script printing you the list of infractions.

### Windows

Requirements :

- [Docker](https://docs.docker.com/engine/install/) installed
- [Powershell](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows) installed

Use `coding-style.ps1`

### MacOS

Requirements :

- [Nix](https://github.com/DeterminateSystems/nix-installer) installed

Use `nix run github:epitech/coding-style-checker` to run a script printing you the list of infractions.
(Supports both Intel and Apple Silicon)
