# WineSpritz
A cocktail of some useful Wine patches. 🍹

## Features

- **Game-specific fixes**  
  - *A Certain Anime Game*: Fixes launch issues when network is enabled and resolves game hanging on exit.

- **Quality of Life improvements**  
  - Includes a selection of patches from [wine-pure-git](https://aur.archlinux.org/packages/wine-pure-git) for enhanced compatibility and smoother usage.

- **Upstream merge requests**  
  - [MR 7064](https://gitlab.winehq.org/wine/wine/-/merge_requests/7064): Fixes issues with many WoW64 games.  
  - [MR 7780](https://gitlab.winehq.org/wine/wine/-/merge_requests/7780): Addresses broken `RedrawWindow()` behavior.

- **Rebased on [wine-tkg](https://github.com/Kron4ek/wine-tkg)**  
  For broader compatibility and ease of use. Still largely works with upstream Wine.

## NTSync Branch

The `ntsync` branch includes all the above, plus support for [wine-tkg-ntsync](https://github.com/Kron4ek/wine-tkg/tree/ntsync).

## Builds

Weekly builds are available via [WineBuilder GitHub Actions](https://github.com/NelloKudo/WineBuilder/actions), built using the Proton SDK environment.
