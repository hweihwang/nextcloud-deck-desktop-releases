# Deckloud: Nextcloud Deck app for iPhone, iPad, Mac, Windows, and Linux

Deckloud is an independent app for [Nextcloud Deck](https://apps.nextcloud.com/apps/deck). It opens the kanban boards you already have on your own Nextcloud server, keeps working when you are offline, and syncs straight to your server with nothing in between.

This is where you download the desktop app, report a bug, ask for a feature, or help translate. Learn more at [deckloud.com](https://deckloud.com).

## Download

| Device | Download | Needs |
| --- | --- | --- |
| iPhone and iPad | [App Store](https://apps.apple.com/app/deckloud/id6756962555?pt=128286558&ct=github-readme&mt=8) | iOS or iPadOS 16.4 |
| Mac | [Deckloud.dmg](https://github.com/hweihwang/nextcloud-deck-desktop-releases/releases/latest/download/stable-macos-arm64-Deckloud.dmg) | macOS 14, Apple Silicon |
| Windows | [Deckloud-Setup.zip](https://github.com/hweihwang/nextcloud-deck-desktop-releases/releases/latest/download/win-x64-Deckloud-Setup.zip) | Windows 11 |
| Linux x64 | [Deckloud-Setup.tar.gz](https://github.com/hweihwang/nextcloud-deck-desktop-releases/releases/latest/download/linux-x64-Deckloud-Setup.tar.gz) | Ubuntu 24.04 or similar |
| Linux arm64 | [Deckloud-Setup.tar.gz](https://github.com/hweihwang/nextcloud-deck-desktop-releases/releases/latest/download/linux-arm64-Deckloud-Setup.tar.gz) | Ubuntu 24.04 or similar |

On a Mac, you can also install with Homebrew:

```sh
brew install --cask hweihwang/nextcloud-deck/deck-desktop
```

A few things to know:

- The Mac app is signed and notarized by Apple, and it updates itself.
- On Windows, extract the zip and run the installer inside. Windows may show a SmartScreen warning because the installer is not code signed. Select **More info**, then **Run anyway**. Windows on ARM runs this build through emulation.
- On Linux, Deckloud needs GTK 3, WebKitGTK 4.1, and a keyring such as GNOME Keyring to store your login safely.
- Windows and Linux do not update themselves yet. Download the new installer from [Releases](https://github.com/hweihwang/nextcloud-deck-desktop-releases/releases) to update.

## What Deckloud does

- Shows your Deck boards, cards, comments, and attachments in a fast native app.
- Keeps your changes while you are offline and syncs them when you are back online.
- Plans dated cards on a Gantt timeline next to your kanban columns.
- Collects everything due, overdue, assigned to you, or mentioning you in one Today list.
- Searches every board at once, including labels, assignees, and card text.
- Links files from Nextcloud Files to a card.

You need a Nextcloud server with the Deck app, version 1.6 or later. If you don't have a server, Deckloud can create a free Deckloud Cloud workspace for you.

## Board templates

Start a new board from one of 20 free templates, such as a sprint board, bug triage, GTD weekly review, or content calendar. Choose **Start from template** when you create a board. Browse them at [deckloud.com/nextcloud-deck-templates](https://deckloud.com/nextcloud-deck-templates/), or see the files and suggest your own in [deckloud-templates](https://github.com/hweihwang/deckloud-templates).

## Free and Pro

Deckloud is free on every device, and your boards stay fully usable without paying. Deckloud Pro is a one-time purchase with no subscription. It removes the limits on Quick Capture, reminders, Focus sessions, and widgets, and one purchase covers iPhone, iPad, and desktop.

## Report a bug or ask for a feature

[Open an issue](https://github.com/hweihwang/nextcloud-deck-desktop-releases/issues/new). Every report is read, and small details often make the fix much faster. If you can, include:

- your Deckloud version and device, such as iPhone, iPad, Mac, Windows, or Linux, with its OS version
- your Nextcloud version and Deck version
- what you expected, what happened instead, and the steps that lead there
- a screenshot, with private board content hidden

Please never post passwords, app tokens, or private board content. If your case needs private details, open a short issue first, and we will move to a private channel.

## Help translate Deckloud

Deckloud speaks more than 90 languages, and most of them were machine translated. If you use Deckloud in your language and something reads wrong, you can fix it in a few minutes. See the [translation guide](translations/README.md).
