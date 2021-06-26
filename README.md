# Taio for Mac (Beta)

Thank you for using [Taio](https://taio.app/) for Mac, the app is currently in its early stages, please expect bugs and do not use it for important docs for now.

Although the app is targeted for `macOS 11.5` and above, we only did internal testing on `Big Sur` (Intel & M1) and `Monterey` (Intel).

Please let us know issues you encounter, you can find feedback channel in the app.

## Known Issues

- Shortcuts on Monterey doesn't work
- HTML preview will be clipped sometimes
  - macOS bug, fixed on Monterey
- Recent files won't show
  - macCatalyst bug, we're looking for help from Apple
- Unsupported text actions
  - Show Dictionary Definition (macCatalyst feature gap)
  - Web Search (use `Open URL` to work around)
- Unsupported [JavaScript](https://docs.xteko.com/#/en/) APIs
  - [Obj-C blocks](https://docs.xteko.com/#/en/runtime/blocks?id=objective-c-blocks)
  - [Calling C functions](https://docs.xteko.com/#/en/runtime/c)
  - [Secure shell](https://docs.xteko.com/#/en/ssh/intro)

## Todos

- [ ] Known issues
- [ ] Move to [Mac Idiom](https://developer.apple.com/documentation/uikit/mac_catalyst/choosing_a_user_interface_idiom_for_your_mac_app)
- [ ] Better multi-selection support
- [ ] More mouse and keyboard support

## Contact Us

- Website: [taio.app](https://taio.app)
- Email: [hi@taio.app](mailto:hi@taio.app)
- Twitter: [@TaioApp](https://twitter.com/TaioApp/)
