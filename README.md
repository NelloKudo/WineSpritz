# WineSpritz
A cocktail of some useful Wine patches. 🍹

## Features

- **Game-specific fixes**  
  - *A Certain Anime Game*: Fixes launch issues when network is enabled, resolves game hanging on exit and fixes community tab not launching.

- **QoL improvements**  
  - Includes some patches from [wine-pure-git](https://aur.archlinux.org/packages/wine-pure-git) for compatibility/usage.

- **Upstream merge requests**  
  - [MR 7064](https://gitlab.winehq.org/wine/wine/-/merge_requests/7064): Fixes issues with many WoW64 games.
  - [MR 7540](https://gitlab.winehq.org/wine/wine/-/merge_requests/7540): Fixes issues with long paths links/files.

- **NTSync support**
  - Fixes for NTSync based on [wine-tkg-ntsync](https://github.com/Kron4ek/wine-tkg/tree/ntsync).

- **Rebased on [wine-tkg](https://github.com/Kron4ek/wine-tkg)**  
  For broader compatibility and ease of use. Still largely works with upstream Wine.

## Builds

Weekly builds are available via [WineBuilder GitHub Actions](https://github.com/NelloKudo/WineBuilder/actions), built using the Proton SDK environment.

## AAGL Builds

Spritz-Wine is also available in **AAGL** launchers as `Spritz-Wine-AAGL-TkG`, a minimal build with only the essential patches needed for game fixes (see the [aagl branch](https://github.com/NelloKudo/WineSpritz/tree/aagl)).

For easier maintenance and compatibility, those are built at [my fork of Kron4ek's Wine-Builds](https://github.com/NelloKudo/Wine-Builds), always via GitHub Actions: you can download it from releases or from workflows.