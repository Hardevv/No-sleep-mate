# Changelog

Every release, newest first. `unreleased` in the date means the entry is still
being written; `scripts/cli.sh version build` refuses to tag it until it has a date.

## [1.1.1] - 2026-10-28
### Added
- docs: add release instructions

### Fixed
- fix: realease link


## [1.1.0] - 2026-10-28
16 commits since v1.0.0 (446fb87..d2c44bd), newest first

### Added
- feat: scren saver improvemnts
- feat: buy me a coffe and placeholder for add preset
- feat: add version to help menu
- feat: add feedback form
- feat: hide cursor on screen saver
- feat: reduce requests when on scren saver
- test: add tests for new UX solution
- test: fix tests after new UX changes
- feat: new menu UX styles
- feat: new menu UX
- feat: screen saver pt2
- feat: screen saver
- refactor: change the way screen lock works
- docs: appcast for 1.0.0

### Fixed
- fix: follow the system on alerts, login item, pointer and assistive input
- fix: inconsisten UI for new UX menu item across devices


## [1.0.0] - 2026-10-20
### Added
- The menu bar shows what the app is doing: off, on with the time left, or `∞` for never
- Keeps the Mac awake by holding IOKit power assertions, and lets it sleep at the deadline
- Presets, so a length that is used every day is one click away
- `Only on Power Adapter`, which drops everything while on battery
- `Pause while media plays`, so a video is not interrupted by the countdown running out
- A first-run tour, with `Do not show again` and `Show the tour again` in the Help menu
- Launch at Login, through `SMAppService`
- A sound shortly before the time is up, with the lead time set in the menu
- Seven languages -- English, German, Spanish, French, Japanese, Polish and Simplified
  Chinese -- following the system language, or picked in the menu
- Updates through Sparkle: EdDSA-signed, checked for silently at launch
- Apple Silicon and Intel, from either one slice or a universal build

<!-- 111 commits, newest first (no v* tag to start from)
- refactor: make tests faster, finish onboarding, make app bundle and icon smaller
- feat: onboarding steps: 3,4 and fixes
- fix: the last page's note lines up with the glyph lines above it
- feat: finishing the tour opens the app's menu
- feat: the tour's last page says where the tour went
- feat: onboarding step 3, the two warning lists
- fix: the test menu leads with the run on the test machine
- fix: the menu picks with its own colours, not reverse video
- feat: pick commands from a menu in cli.sh
- feat: cli.sh, one entry point for the scripts
- feat: onboarding step 2 + icon
- feat: onboarding base + step1
- feat: localization, media playing detection
- test: add missing tests
- feat: video prevent sleep, faster unplug read on event
- test: coverage & naming conventions
- test: the sleep request, and the wiring the user's build runs on
- test: help has to keep up with the bar, and one row to quit with
- test: presets, from the field to the stored list
- test: the sound warning, from the menu down to the speaker
- test: power adapter and launch settings
- test: calculations, I/O, better test logs
- test: keep awake logic
- test: presets logic, add pre-hook for time consuming tests with optimistic commiting
- test: enabled
- test: smoke on adapter
- test: smoke lunch at login
- test: sound smoke test
- test/app quitting
- feat: better remote tests
- test: somke add and delete presets
- test: smoke enable / disable
- feat: configure remote tests, rebuild test logic
- test: split fast and slow tests approach
- test: add smoe tests for presets
- chore: remove mocked icon generation
- docs: readme
- feat: add help description and change the icon
- docs: polish the README
- chore: udpate the build script comments
- refactor: read the settings once per menu update
- chore: tooltips for the three states
- docs: README, how it works and how to build it
- chore: tidy up the add-preset window
- wip: trying a live counter instead of the countdown
- chore: a place for the help text
- fix: the EXIT trap read the temp dir before it was set
- feat: build one app that runs on both architectures
- chore: share the build logic between the scripts
- feat: migrate stored settings to whole minutes
- ... and 61 older commits
-->
