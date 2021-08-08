> Taio for Mac has been officially released, thanks for participating the Beta program.
> 
> You can start using [Mac App Store version](https://taio.app/mac) from now on.

# Taio for Mac (Beta)

Thank you for using [Taio](https://taio.app/) for Mac, the app is currently in its early stages, please expect bugs and do not use it for important docs for now.

Although the app is targeted for `macOS 11.5` and above, we only did internal testing on `Big Sur` (Intel & M1) and `Monterey` (Intel).

Please let us know issues you encounter, you can find feedback channel in the app.

<img src="https://user-images.githubusercontent.com/6745066/125184172-1d30dc80-e24e-11eb-9095-5b2a12c9f459.png" width="864" />

## Builds

[Recent releases](https://github.com/cyanzhong/Taio-Mac-Beta/releases).

Note that, the app won't be updated automatically, you will need to check this page for newly published builds.

Ideally, we should rely on [TestFlight](https://developer.apple.com/testflight/) for Mac, but it's not available for now.

## Known Issues

- Actions won't be synced using iCloud
  - Planned, might not be in the initial release
- HTML preview will be clipped sometimes
  - Mac Catalyst bug, fixed on Monterey
- Recent files won't show when right-clicking on the Dock icon
  - Mac Catalyst bug, we're looking for help from Apple
- Tool picker won't show in sketchpad
  - Mac Catalyst feature gap, won't fix

## Todos

- [ ] Known issues
- [ ] Move to [Mac Idiom](https://developer.apple.com/documentation/uikit/mac_catalyst/choosing_a_user_interface_idiom_for_your_mac_app), or less iPad-like
- [ ] Better multi-selection support
- [ ] More mouse and keyboard support

## Contact Us

- Website: [taio.app](https://taio.app)
- Email: [hi@taio.app](mailto:hi@taio.app)
- Twitter: [@TaioApp](https://twitter.com/TaioApp/)
