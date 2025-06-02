# WineSpritz
A cocktail of some useful Wine patches, aagl-version. 🍹

## Features

- **Game-specific fixes**  
  - *A Certain Anime Game*: Fixes launch issues when network is enabled and resolves game hanging on exit.

- **Upstream merge requests** 
  - [MR 7540](https://gitlab.winehq.org/wine/wine/-/merge_requests/7540): Fixes issues with long paths links/files (fix to GI's community/feedback tab crashing).

## Builds

Weekly builds are available via [WineBuilder GitHub Actions](https://github.com/NelloKudo/WineBuilder/actions), built using the Proton SDK environment.
Also in [WineBuilder Releases](https://github.com/NelloKudo/WineBuilder/releases).

## AAGL Builds

Spritz-Wine is also available in **AAGL** launchers as `Spritz-Wine-AAGL-TkG`, a minimal build with only the essential patches needed for game fixes (see the [aagl branch](https://github.com/NelloKudo/WineSpritz/tree/aagl)).

For easier maintenance and compatibility, those are built at [my fork of Kron4ek's Wine-Builds](https://github.com/NelloKudo/Wine-Builds), always via GitHub Actions: you can download it from releases or from workflows.