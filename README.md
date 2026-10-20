# No Sleep Mate

No Sleep Mate keeps your Mac awake while you need it, then lets it sleep when you are done.
It lives in the menu bar, uses the power management features macOS already has, and stays out of the way. Nothing is simulated, and no permission is needed. No data collecting.

## Download and install

1. Open the [Releases page](https://github.com/Hardevv/No-sleep-mate/releases) and download the latest version.
2. Move No Sleep Mate to your Applications folder.
3. Open it. There is no Dock icon, so look for the app in the menu bar.

macOS 13 Ventura or later is required, on Apple Silicon or Intel.

This version is not notarized yet. If macOS blocks the first launch, open
System Settings > Privacy & Security and choose Open Anyway. This is needed only once.
Later versions will be signed with a Developer ID.

## What it does

- Keeps the Mac awake with power assertions, not by faking activity. A No AFK mode, which can simulate activity, is planned for a later version.
- Counts down the time you choose, then lets the Mac sleep.
- Has no Dock icon and no background window.
- Works offline and collects nothing.
- Works in continuity mode: set it once and it keeps running, unlike apps such as Amphetamine, where you start a session every time.

## The menu bar

Click the menu bar icon to turn the app on or off, choose how long to stay awake, and manage
presets.

| Menu bar                                                                          | Meaning                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------- |
| <img src="docs/menu-bar-off.png" width="24" height="18" alt="Pause icon">            | Off, the Mac can sleep as usual                       |
| <img src="docs/menu-bar-timed.png" width="46" height="18" alt="zzz and the time left"> | On, with the time left before the Mac may sleep       |
| <img src="docs/menu-bar-never.png" width="35" height="18" alt="zzz and infinity">     | On, with no time limit                                |
| <img src="docs/menu-bar-time-up.png" width="24" height="18" alt="zzz alone">          | On, but the time is up and the hold is released       |
| <img src="docs/menu-bar-battery.png" width="24" height="18" alt="Crossed bolt">       | On, but on battery while Only on Power Adapter is set |

The last minute is shown in seconds. The timer restarts whenever you use the Mac and begins
counting down after 10 seconds without activity, so it does not flicker while you type.

## Time limits

A preset is a number of minutes by default. You can also use units and mix them: `15`, `1h`,
`90m`, or `1h30m`. Limits are whole minutes, from 1 minute to 24 hours.

**Never** is a mode, not a duration. The Mac stays awake until you change the mode.

## Options

- **Only on Power Adapter** holds the Mac awake only while it is plugged in. Unplugging lets
  it sleep.
- **Pause while media plays** is on by default. Audio or video pauses the countdown, and the
  countdown resumes when playback ends, so a film is never cut short.
- **Sound warning** is off by default. Pick how early to be warned and which system sound to
  play, and it will play once before the time runs out.
- **Launch at Login** starts the app with your Mac. Keep the app in Applications.

## The tour and help

A short tour explains the menu bar and the main options. Tick `Do not show again` in its
footer to skip it next time. To see it again, choose `Help` > `Show the tour again` from the
menu.

![The No Sleep Mate tour](docs/onboarding.gif)

## Language

The interface follows your Mac's language. You can choose another language from the `Language`
row in the menu, and the change applies the next time you open the menu. English, Polish,
German, Spanish, French, Japanese, and Simplified Chinese are included.

<img src="docs/langs.png" alt="The Language menu in No Sleep Mate" width="160">

## Privacy

No network, no telemetry, no data collection. The app asks for no permissions at all.

## Version and release notes

The current version is 1.0.0. This repository is the public update channel for No Sleep Mate.
Release notes live in [CHANGELOG.md](docs/CHANGELOG.md).

## Feedback

Found a problem or have an idea? Open an issue in this repository or fill in the [Feedback form](https://verdant-child-0e1.notion.site/3fea45897ee880c288dbcfef2ccf8b9b?pvs=105 "Feedback form").

## License

No Sleep Mate is free to download and use, but it is not open source. Redistribution,
modification, and republishing are not allowed. See [LICENSE.md](LICENSE.md) for the full
terms.
