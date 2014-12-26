# YouTube-Player-iOS-Helper

## Installation

Import files from YTPlayerView to your project.

After installing in your project and opening the workspace, to use the library:

  1. Drag a UIView the desired size of your player onto your Storyboard.
  2. Change the UIView's class in the Identity Inspector tab to YTPlayerView
  3. Import "YTPlayerView.h" in your ViewController.
  4. Add the following property to your ViewController's header file:
```objc
    @property(nonatomic, strong) IBOutlet YTPlayerView *playerView;
```
  5. Load the video into the player in your controller's code with the following code:
```objc
    [self.playerView loadWithVideoId:@"M7lc1UVf-VE"];
```
  6. Run your code!

See the sample project for more advanced uses, including passing additional player parameters and
working with callbacks via YTPlayerViewDelegate.

## Author

Ikai Lan, ikai@google.com
Yoshifumi Yamaguchi, yoshifumi@google.com

## License

YouTube-Player-iOS-Helper is available under the Apache 2.0 license. See the LICENSE file for more info.
