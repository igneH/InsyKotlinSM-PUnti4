# Pathway 2

### A route is defined with a(n) ___ data type.
- [ ] @Composable function
- [ ] NavHost.Route
- [x] String
- [ ] NavRoute

### With a NavHost, you must explicitly specify a starting screen.
- [x] True
- [ ] False

### It’s considered best practice to not pass a NavHostController to individual composables.
- [x] True
- [ ] False

### ___ is a composable that manages which screen is displayed based on a given route.
- [ ] NavController
- [ ] NavHostController
- [x] NavHost
- [ ] ComposableNavigator

### The composable() function called in a NavHost takes which two parameters?
- [ ] Destination content and a route
- [x] A route and composable content
- [ ] A path and a composable
- [ ] Composable content and an intent.

### You can change the currently displayed route using the ___ method.
- [ ] update()
- [ ] composable()
- [ ] transition()
- [x] navigate()

### The ___ method removes one or more screens from the backstack.
- [ ] popToStartDestination()
- [x] popBackStack()
- [ ] popComposable()
- [ ] popToBackStack()

### In a multi-screen app, navigating to a new screen puts it on the bottom of the backstack.
- [ ] True
- [x] False

### Intent ___ contain additional data passed to an Intent.
- [ ] arguments
- [x] extras
- [ ] parameters
- [ ] properties

### StateFlow is a data-holder observable flow that emits the current and new state updates.
- [x] True
- [ ] False

### Which of the following are true about the Back and Up buttons?
Choose as many answers as you see fit.

- [x] The Back button is a system button
- [ ] The Up button is provided by the system at the bottom of the screen
- [ ] The Back button is part of the AppBar
- [ ] The Up button in the AppBar automatically navigates to the previous screen.
- [ ] The Back button only appears if you use navigation.
- [x] The Up button can be shown or hidden, depending on the current screen.