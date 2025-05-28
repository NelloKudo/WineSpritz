# WineSpritz
A cocktail of some useful Wine patches. 🍹

## Features

- **Game-specific fixes**  
  - *A Certain Anime Game*: Fixes launch issues when network is enabled and resolves game hanging on exit.

- **QoL improvements**  
  - Includes some patches from [wine-pure-git](https://aur.archlinux.org/packages/wine-pure-git) for compatibility/usage.

- **Upstream merge requests**  
  - [MR 7064](https://gitlab.winehq.org/wine/wine/-/merge_requests/7064): Fixes issues with many WoW64 games.

- **NTSync support**
  - Fixes for NTSync based on [wine-tkg-ntsync](https://github.com/Kron4ek/wine-tkg/tree/ntsync).

- **Rebased on [wine-tkg](https://github.com/Kron4ek/wine-tkg)**  
  For broader compatibility and ease of use. Still largely works with upstream Wine.

## Builds

Weekly builds are available via [WineBuilder GitHub Actions](https://github.com/NelloKudo/WineBuilder/actions), built using the Proton SDK environment.
