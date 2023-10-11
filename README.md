## [Project 8: 7 Swifty Words](https://www.hackingwithswift.com/read/8/overview)
Written by [Paul Hudson](https://www.hackingwithswift.com/about)  ![twitter16](https://github.com/juliangyurov/PH-Project6a/assets/13259596/445c8ea0-65c4-4dba-8e1f-3f2750f0ef51)
  [@twostraws](https://twitter.com/twostraws)

**Description:** Build a word-guessing game and master strings once and for all.

- Setting up

- Building a `UIKit` user interface programmatically

- Loading a level and adding button targets

- It's play time: `firstIndex(of:)` and `joined()`

- Property observers: `didSet`

- Wrap up

## [Review what you learned](https://www.hackingwithswift.com/review/hws/project-8-7-swifty-words)

**Challenge**

1. Use the techniques you learned in project 2 to draw a thin gray line around the buttons view, to make it stand out from the rest of the UI.

2. If the user enters an incorrect guess, show an alert telling them they are wrong. You’ll need to extend the `submitTapped()` method so that if `firstIndex(of:)` failed to find the guess you show the alert.

3. Try making the game also deduct points if the player makes an incorrect guess. Think about how you can move to the next level – we can’t use a simple division remainder on the player’s score any more, because they might have lost some points.
