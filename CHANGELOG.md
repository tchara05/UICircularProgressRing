# Version 1.1.7

Fix bug where progress bar was pixelated inside of tableView from [issue #4](https://github.com/luispadron/UICircularProgressRing/issues/4)

Thanks to [@DeepAnchor](https://github.com/DeepAnchor) for the fix!

- Default background color for view and layer is now of `UIColor.clear`

# Version 1.1.6

Lower required iOS version to iOS 8.0

- Lower podspec for compatability with iOS 8.0
- Lower project deployment target to 8.0

# Version 1.1.5

Fix inaccesible ring value thanks to [@DaveKim](https://github.com/davekim)

- Update delegate method parameters for more Swift like method names/parameters
- Update Xcode project to recommended settings

### API Changes:

Delegate method renamed to: `func finishedUpdatingProgress(forRing ring: UICircularProgressRingView)` (this is the last time, I swear)

# Version 1.1.4

Add isAnimating to UICircularProgressRingView

- Added new property to determine whether ring is animating currently
- Fix some typos
- Made completion handler default to nil
- Refactor delegate method call to look more Swifty

## Breaking API Changes:

Delegate method renamed to: `func finishedUpdatingProgress(forRing: UICircularProgressRingView)`

# Version 1.0.0

### Hugh Mungus changes

- Refactor code into two separate files (UICircularProgressRingView, and UICircularProgressRingLayer)
- Fix animation, now works smoothly both increasing and decreasing
- More stability in terms of not causing a crash due to RunLoop
- More documentation
- ITS READY
