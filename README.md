# WineSpritz
A cocktail of some useful Wine patches, aagl-version. 🍹

## Features

- **Game-specific fixes**  
  - *A Certain Anime Game*: Fixes launch issues when network is enabled and resolves game hanging on exit.

- **Upstream merge requests** 
  - [MR 8493](https://gitlab.winehq.org/wine/wine/-/merge_requests/8493): Fixes issues with loading cutscenes in some games (eg. HSR/HI3).

- **AAGL workarounds**
  - Includes some patches/workarounds for builds to work correctly in AAGL and related launchers, if you're planning to build your own Wine you can probably remove those.

## AAGL Builds

Spritz-Wine is also available in **AAGL** launchers as `Spritz-Wine-AAGL-TkG`, a minimal build with only the essential patches needed for game fixes (see the [aagl branch](https://github.com/NelloKudo/WineSpritz/tree/aagl)).

For easier maintenance and compatibility, those are built at [my fork of Kron4ek's Wine-Builds](https://github.com/NelloKudo/Wine-Builds), always via GitHub Actions: you can download it from releases or from workflows.

## Spritz-Proton

A Spritz-Proton-CachyOS version is also available at [NelloKudo/Proton-CachyOS](https://github.com/NelloKudo/proton-cachyos) with just game patches and some backports applied (see the [proton branch](https://github.com/NelloKudo/WineSpritz/tree/proton)). 
