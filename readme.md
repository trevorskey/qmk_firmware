# Quantum Mechanical Keyboard Firmware

[![Current Version](https://img.shields.io/github/tag/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/tags)
[![Build Status](https://travis-ci.org/qmk/qmk_firmware.svg?branch=master)](https://travis-ci.org/qmk/qmk_firmware)
[![Discord](https://img.shields.io/discord/440868230475677696.svg)](https://discord.gg/Uq7gcHh)
[![Docs Status](https://img.shields.io/badge/docs-ready-orange.svg)](https://docs.qmk.fm)
[![GitHub contributors](https://img.shields.io/github/contributors/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/pulse/monthly)
[![GitHub forks](https://img.shields.io/github/forks/qmk/qmk_firmware.svg?style=social&label=Fork)](https://github.com/qmk/qmk_firmware/)

This is a keyboard firmware based on the [tmk\_keyboard firmware](https://github.com/tmk/tmk_keyboard) with some useful features for Atmel AVR and ARM controllers, and more specifically, the [OLKB product line](https://olkb.com), the [ErgoDox EZ](https://ergodox-ez.com) keyboard, and the [Clueboard product line](https://clueboard.co).

## Fork Notes

This is a fork of the official repository _and_ the MassDrop repository for the express purpose of fixing issues with the MassDrop Shift keyboard.

At present, support for the MassDrop Shift keyboard is only present in the MassDrop repository, and that is based on a very old version of QMK. The default branch of this fork is currently based on this one working repository.

### Disclaimers

* I am but one man, and I have a day job. I also have much to learn about this codebase. So work here will be slow. That said, I also use this keyboard for my day job. So annoyances are more likely to be dealt with swiftly.
* The Drop Shift keyboard is my only programmable keyboard, so I won't be making updates/fixes with other keyboards in mind yet.
* I have thus far never used the online configurator tool, so all of my initial updates will not have this in mind. Eventually I do plan to make sure my changes work with the configurator tools.

### Priorities

These are the items I currently have on my list to fix or update.

* The LED indicators are not separate from the whole keyboard LED effects, causing them to disappear. [FIXED]
  * Setting the indicator color should be possible in the keymap config.
* Scroll Lock doesn't seem to work, not even for the indicator LED.
* Fix the USB so the keyboard is compatible with my KVM switch.
* Add a visual countdown when pressing the DFU mode button.


## Documentation

* [See the official documentation on docs.qmk.fm](https://docs.qmk.fm)

The docs are powered by [Docsify](https://docsify.js.org/) and hosted on [GitHub](/docs/). You can request changes by making a fork and [pull request](https://github.com/qmk/qmk_firmware/pulls), or by clicking the "Edit Document" link at the bottom of any page.

## Supported Keyboards

* [Planck](/keyboards/planck/)
* [Preonic](/keyboards/preonic/)
* [ErgoDox EZ](/keyboards/ergodox_ez/)
* [Clueboard](/keyboards/clueboard/)
* [Cluepad](/keyboards/clueboard/17/)
* [Atreus](/keyboards/atreus/)

The project also includes community support for [lots of other keyboards](/keyboards/).

## Maintainers

QMK is developed and maintained by Jack Humbert of OLKB with contributions from the community, and of course, [Hasu](https://github.com/tmk). The OLKB product firmwares are maintained by [Jack Humbert](https://github.com/jackhumbert), the Ergodox EZ by [ZSA Technology Labs](https://github.com/zsa), the Clueboard by [Zach White](https://github.com/skullydazed), and the Atreus by [Phil Hagelberg](https://github.com/technomancy).

## Official Website

[qmk.fm](https://qmk.fm) is the official website of QMK, where you can find links to this page, the documentation, and the keyboards supported by QMK.
