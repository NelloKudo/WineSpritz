# WineSpritz
A cocktail of some useful Wine patches. 🍹

## 🍸 - Features: 

- Game-specific fixes:
    - Genshin Impact: fixes game not launching with network enabled and game hanging on closure.
- Various QoL fixes:
    - Great patches from [wine-pure-git](https://aur.archlinux.org/packages/wine-pure-git) for better compatibility and usage.
- Wine merge requests:
    - [7064](https://gitlab.winehq.org/wine/wine/-/merge_requests/7064), fixing many games not working on WoW64.
    - [7780](https://gitlab.winehq.org/wine/wine/-/merge_requests/7780), fixing some broken `RedrawWindow()` calls.
- Rebased against [wine-tkg](https://github.com/Kron4ek/wine-tkg) for easier compatibility (mostly works with Wine upstream, too).

## 🥂 - NTSync version
The `ntsync` branch includes everything above, plus a patch for [wine-tkg-ntsync](https://github.com/Kron4ek/wine-tkg/tree/ntsync).

## 🍷 - Builds

You can find weekly builds at my [WineBuilder's workflows](https://github.com/NelloKudo/WineBuilder/actions), built in Proton's SDK.