### Hi, I'm Ross 👋

I make small, native apps for Mac, iPhone and iPad. More at [rossnicholson.dev](https://rossnicholson.dev).

#### Open-source Mac apps

| | App | What it does |
|---|---|---|
| <img src="https://raw.githubusercontent.com/RossNicholson/brewdock/main/docs/icon.png" width="48" alt=""> | **[BrewDock](https://github.com/RossNicholson/brewdock)** | A Homebrew GUI in your menu bar: browse, install, update and manage brew packages and casks without the Terminal. |
| <img src="https://raw.githubusercontent.com/RossNicholson/clawdbar/main/docs/icon.png" width="48" alt=""> | **[ClawdBar](https://github.com/RossNicholson/clawdbar)** | Your Claude Code usage limits (5-hour session and 7-day weekly) always in view in the menu bar. |
| <img src="https://raw.githubusercontent.com/RossNicholson/mop-up/main/docs/icon.png" width="48" alt=""> | **[Mop Up](https://github.com/RossNicholson/mop-up)** | A free Mac cleaner: clear out caches, uninstall apps along with their leftovers, tune up macOS and see where your disk space went. Powered by [Mole](https://github.com/tw93/Mole). |

All three are signed and notarized, and install with Homebrew from [my tap](https://github.com/RossNicholson/homebrew-tap):

```bash
brew trust --cask rossnicholson/tap/brewdock rossnicholson/tap/clawdbar rossnicholson/tap/mopup
brew install --cask rossnicholson/tap/brewdock rossnicholson/tap/clawdbar rossnicholson/tap/mopup
```

On Homebrew older than 7, skip the `brew trust` line. The apps share one look through [mac-house-style](https://github.com/RossNicholson/mac-house-style), a small SwiftUI package.

#### iPhone and iPad

- **[Don't Worry](https://rossnicholson.dev/worry)**: a private worry journal. Write a worry down, give it three days, then look back. [On the App Store](https://apps.apple.com/gb/app/dont-worry-anxiety-app/id6740061074).
- **[Word Slip](https://rossnicholson.dev/word-slip)**: a sneaky word party game for 2 to 8 players. Slip three secret words into the conversation without anyone noticing. Coming soon.
- **[Feedie](https://rossnicholson.dev/feedie)**: Bluesky, Mastodon and RSS in one timeline. Free, with no ads and no tracking. Coming soon.

#### World of Warcraft

- **[Rewatch Classic](https://github.com/RossNicholson/rewatch-classic)**: the Rewatch druid HoT-tracking addon, adapted for Mists of Pandaria Classic.
