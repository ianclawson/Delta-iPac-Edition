## -- DISCLAIMER

Almost all of the features in this fork have now **finally** been implemented in the official Delta (pretty much everything except for Rewind).

Please use that instead of this fork.

# Delta (iPac Edition)

<p align="center">
  <em>(a Fan-build of Delta, an all-in-one classic video game emulator for non-jailbroken iOS devices)</em>
  </br>
  <em>https://github.com/rileytestut/delta</em>
</p>

## -- About

This is a page I threw together quickly as a means to both inform about and to host this iPac-Edition of Delta!

**Please don't consider this as a contiuation/fork of Delta, but rather a "technical review" of some features that I hope eventually make their way into Delta mainline.**

As of the time of writing this (November 19th, 2021), this edition includes everything that the official Delta release currently has, along with some features I decided to implement myself because I was too excited about them to wait 🙃

Every feature I added to this edition is accompanied by open PRs to merge the features upstream into Delta mainline.

Though in my testing the build is stable, I am not planning on continuing development of this iPac Edition ❤️

## -- Download

Check the Releases tab for the IPA:
https://github.com/ianclawson/Delta-iPac-Edition/releases/tag/1.0.0

You'll need to sideload using AltStore: https://altstore.io or sideload using whichever method is your preference.

The source code isn't hosted here, so if you wish to build from source, you'll need to pull the PRs listed below into a locally cloned version of Delta. I can't go over how to to do that here. Best of luck!

## -- Supported Systems:
- Nintendo Entertainment System (NES)
- Super Nintendo Entertainment System (SNES)
- Nintendo 64 (N64)
- Game Boy / Game Boy Color (GBC)
- Game Boy Advance (GBA)
- Nintendo DS (DS)
- Sega Genesis / Mega Drive (GEN) **(still in beta by Delta mainline)**

## -- Additional Features (along with their PRs):

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
- Delta: https://github.com/rileytestut/Delta/pull/131
### Additional MFi Inputs (L3, R3, Options, Home, and some PS/Xbox-specific inputs)
- Delta: https://github.com/rileytestut/Delta/pull/135
- DeltaCore: https://github.com/rileytestut/DeltaCore/pull/33
### External Controller deadzones for analog inputs (allows analog sticks to work properly for d-pads)
- DeltaCore: https://github.com/rileytestut/DeltaCore/pull/35
### External Controller connection now prevents game screen from rotating
- Delta: https://github.com/rileytestut/Delta/pull/155
### SNES Audio no longer crackles
- SNES: https://github.com/rileytestut/SNESDeltaCore/pull/3
### Bonus: Quick Saves now Sync
- Delta: No PR for this one for reasons, but in [this file](https://github.com/rileytestut/Delta/blob/main/Delta/Database/Model/Human/SaveState.swift#L131) I simply removed `&& self.type != .quick`

## -- FAQs
- Where to download?
    - https://github.com/ianclawson/Delta-iPac-Edition/releases/tag/1.0.0
- How to sideload?
    - https://altstore.io
- Will this replace my currently installed version of Delta?
    - No -- The bundle ID is different, so this will be treated as a _separate_ app by iOS and AltStore.
- Will it automatically pull in my games/saves from Delta?
    - No -- because it's treated as a separate app from Delta, you'll need to reimport any games/saves you want in this iPac edition yourself.
- There are some weird graphical bugs in the Delta menus, what's going on?
    - This IPA was built against the iOS 15 SDK -- and iOS 15 introduced some under-the-hood changes to how Navigation Bars and Menu Bars work -- so there are some graphical hiccups in the menus. I currently don't have the time to look into fixing it, so please consider this expected behavior for this iPac Edition 😉
- Why release a build of your PRs?
    - To share my passion for iOS Retro Game Emulation dev with the world, and to keep Delta fresh while we patiently wait for the next official Delta release. 
- Why "iPac"?
    - It's my initials, and also a tongue-in-cheek naming intersection of two of my interests: Apple Dev and Video Games. It made sense to me at least 🙃

## -- Disclaimers
- I am not affiated with or sponsored by Riley Testut, Delta, or AltStore LLC. I'm just an ordinary guy with a passion for Retro Game Emulation on iOS Devices.
    - I hold a regular full-time job and have a family to take care of, so my hobby-dev work is limited; please do not expect updates to this edition.
    - I am not planning on keeping this Edition up-to-date as Delta mainline moves forward.
        - That's why I opened the PRs in the first place; so that Delta mainline one day merges them in, and this iPac Edition becomes obsolete and removed.
- This IPA is issued free from charge or promise of continued development.
    - Please do not contact me for bug reports or feature requests, unless the bugs pertain specifically to the features I've added myself to Delta. Everything else should be reported to Delta mainline.
    - I make no promises or claims for reliability, asbsense of bugs, protection of your games/saves, or performance of your device.
    - Should I choose, additional features that I open PRs for on Delta mainline may make their way into a new version of this iPac Edition. No promises.
- All code included in this release is publicly available and publicly licensed as stated by Delta mainline: https://github.com/rileytestut/delta#licensing
- The code for this edition is not hosted here, but is available via the linked PRs above.

<p align="center">
  Thanks for reading ❤️
</p>
