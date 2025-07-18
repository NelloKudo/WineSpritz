# WineSpritz
A cocktail of some useful Wine patches. 🍹

## Features

- **Game-specific fixes**
  - *Genshin Impact (Global/CN)/Zenless Zone Zero*: Includes workaround to launch the game offline, fixes possible high CPU usages in-game and launch issues.
  - *Genshin Impact*: Fixes game hanging on exit. 

- **QoL improvements**  
  - Includes some patches from [wine-pure-git](https://aur.archlinux.org/packages/wine-pure-git) for compatibility/usage.

- **Upstream merge requests**  
  - [MR 7064](https://gitlab.winehq.org/wine/wine/-/merge_requests/7064): Fixes issues with many games when using WoW64 Wine.
  - [MR 8493](https://gitlab.winehq.org/wine/wine/-/merge_requests/8493): Fixes issues with loading cutscenes in some games.

- **NTSync support**
  - Fixes for NTsync not compiling on certain GCC/NTsync header versions.

- **Rebased on [wine-tkg](https://github.com/Kron4ek/wine-tkg)**  
  For easier compatibility with TkG patches, still mostly working with upstream Wine too of course.

## AAGL Builds

Spritz-Wine is also available in **AAGL** launchers as `Spritz-Wine-TkG`, as a minimal build with only the essential patches needed for game fixes (see the [aagl branch](https://github.com/NelloKudo/WineSpritz/tree/aagl)).

For easier maintenance and compatibility, those are built at [my fork of Kron4ek's Wine-Builds](https://github.com/NelloKudo/Wine-Builds), always via GitHub Actions: you can download it from releases or from workflows.

## Spritz-Proton

A Spritz-Proton-CachyOS version is also available at [NelloKudo/Proton-CachyOS](https://github.com/NelloKudo/proton-cachyos) with just game patches and some backports applied (see the [proton branch](https://github.com/NelloKudo/WineSpritz/tree/proton)). 
