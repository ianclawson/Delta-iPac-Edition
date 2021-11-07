# Delta (iPac Edition)

<p align="center">
  <em>(a Fan-build of Delta, an all-in-one classic video game emulator for non-jailbroken iOS devices. Check the Releases tab for the IPA)</em>
</p>

## About

This is a page a threw together quickly as a means to both inform about and to host this iPac-Edition of Delta.

As of the time of writing this (November 5th, 2021), this edition includes everything that the official Delta release currently has`*` along with some features I decided to implement myself because I was too excited about them to wait 🙃

`*`_(minus syncing -- see disclaimers section below for info)_

Every feature I added to this edition is accompanied by open PRs to merge the features upstream into Delta mainline.

Why do this? To share my passion for iOS Reetro Game Emulation dev with the world, and to keep Delta fresh while we patiently wait for the next official Delta release. 

Though in my testing the build is stable, _**please do not open issues or tickets.**_ I am not planning on continuing development of this iPac Edition ❤️ _(again, see disclaimers section below for info)_

## Supported Systems:
- Nintendo Entertainment System (NES)
- Super Nintendo Entertainment System (SNES)
- Nintendo 64 (N64)
- Game Boy / Game Boy Color (GBC)
- Game Boy Advance (GBA)
- Nintendo DS (DS)
- Sega Genesis / Mega Drive (GEN) **(still in beta by Delta mainline)**

## Additional Features (along with their PRs):

### Optimized AirPlay Support
- Delta: https://github.com/rileytestut/Delta/pull/119
- DeltaCore: https://github.com/rileytestut/DeltaCore/pull/31
### Local Mulitplayer (NES, SNES, N64, GEN)
- Delta: https://github.com/rileytestut/Delta/pull/128
- DeltaCore: https://github.com/rileytestut/DeltaCore/pull/32
- NES: https://github.com/rileytestut/NESDeltaCore/pull/2
- SNES: https://github.com/rileytestut/SNESDeltaCore/pull/2
- N64: https://github.com/rileytestut/N64DeltaCore/pull/5
- GEN: https://github.com/rileytestut/GPGXDeltaCore/pull/1
### Nintendo-Switch-Online-like Rewind
- https://github.com/rileytestut/Delta/pull/131
### Addition MFi Inputs (L3, R3, Options, Home, and some PS/Xbox-specific inputs)
- Delta: https://github.com/rileytestut/Delta/pull/135
- DeltaCore: https://github.com/rileytestut/DeltaCore/pull/33
### External Controller deadzones for analog inputs (allows analog sticks to work properly for d-pads)
- https://github.com/rileytestut/DeltaCore/pull/35
### External Controller connection now prevents game screen from rotating
- https://github.com/rileytestut/Delta/pull/155

## Disclaimers
- I am not affiated with or by Riley Testut, Delta, or AltStore LLC. I'm just an ordinary man with a passion for Retro Game Emulation on iOS Devices.
    - I hold a regular full-time job and have a family to take care of, so my hobby-dev work is limited; please do not expect updates to this edition.
    - I am not planning on keeping this Edition up-to-date as Delta mainline moves forward.
        - That's why I opened the PRs in the first place; so that Delta mainline one day merges them in, and this iPac Edition becomes obsolete and removed.
- These IPA is issued free from charge or promise of continued development.
    - Please do not open tickets/issues for bugs or requested features.
    - I make no promises or claims for reliability, asbsense of bugs, protection of your games/saves, or performance of your device.
    - I am not planning on fixing bugs or responding to issues.
- Syncing is currently **NOT** supported. I encountered technical difficulties while attempting to get this edition's syncing to coexist with mainline Delta's syncing on the same device. It's possible I'll address this in the future, but I'm not making any promises.
- This IPA was built against the iOS 15 SDK -- and iOS 15 introduced some under-the-hood changes to how Navigation Bars and Menu Bars work -- so there are some graphical hiccups in the menus. Consider this expected behavior for this iPac Edition.
- All code included in this release is publicly available and publicly licensed as stated by Delta mainline: https://github.com/rileytestut/delta#licensing
- The code for this edition is not hosted here, but is available via the linked PRs above.


<p align="center">
  Thanks for reading ❤️
</p>
