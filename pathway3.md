# Pathway 3

## Quiz
### The ___ composable is used to respond to the Back button, with or without a NavHost.
- [ ] BackButton
- [x] BackHandler
- [ ] BackNavigator
- [ ] BackStack

### Which of the following are true about designing for larger screens?
- [x] Button positioning is more important on larger screen sizes.
- [ ] Usually no changes are needed to the UI layout to make the app work well for larger screen sizes.
- [x] Adding another layout to the same screen removes the need to navigate between screens.
- [x] Large screen layouts should avoid placing commonly used buttons in the center of the screen.

### A ___ is a specific measurement of width or height where an app's layout should change.
- [ ] window class
- [ ] layout point
- [ ] size bucket
- [x] breakpoint

### The compact width window size class generally refers to smaller devices, such as phones in portrait mode.
- [x] True
- [ ] False

### The ___ API makes the implementation of adaptive layouts simpler.
- [ ] SizeClass
- [ ] WindowSizeState
- [ ] SizeBucket
- [x] WindowSizeClass

### A navigation rail is often appropriate for ___ width layouts.
- [ ] compact
- [ ] standard
- [x] medium
- [ ] expanded

### When building apps with adaptive layouts, you should use a single preview for each screen.
- [ ] True
- [x] False

### The list-detail layout requires Back navigation on compact screens, but not on screens where both the list and detail screens are shown at once.
- [x] True
- [ ] False

### Assume you have a contacts app that displays a list of contacts and has details to show for each contact. What are appropriate ways to adapt the UI to different screen sizes?
- [x] Use the list-detail layout to show one pane or two panes side-by-side depending on the available width of the screen.
- [ ] The list items should take up the full width of the screen, regardless of how narrow or wide the screen is.
- [ ] The Up button should always be shown within the app and clicking the button should exit the app.
- [ ] When rotating the device, the selected item in the list (and the corresponding details of that item shown) should be reset to the first item in the list.
- [ ] It’s required to use the Jetpack Navigation Component to make the UI responsive to different screen sizes.

### Tests can be configured to run only test functions with custom annotations by configuring the ___.
- [ ] module
- [ ] package
- [ ] instrumentation class
- [x] instrumentation arguments