# namer_app

A comprehensive app built thanks to the: [Your First Flutter App CodeLab](https://codelabs.developers.google.com/codelabs/flutter-codelab-first#0)

# What's covered
- The basics of how Flutter works
- Creating layouts in Flutter
- Connecting user interactions (like button presses) to app behavior
- Keeping your Flutter code organized
- Making your app responsive
- Achieving a consistent look & feel of your app

# End Result
## UI
### Home Page:
![image](https://github.com/user-attachments/assets/73101bb5-fba6-4748-bce5-4eab63d3047f)
- Display a random generated word
- When clicking next, displays a new random word
- Possibility to Save a word or Unsave it (if it is already saved)
### Favorites Page
![image](https://github.com/user-attachments/assets/6dbd4bc9-2a14-4d37-b479-d84c044a417a)
- Display the total number of the favortie words.
- A scrollable list of favorite words.
## Responsiveness
![image](https://github.com/user-attachments/assets/8509e9e0-6bb8-4152-8412-a574126bb918)
- The sideBar (or _navigation rail_) alter between the expanded state and the collapsed state (see the image above) based on the width of the window, in my case the break point is 600px.
## Plateform Targeted
- This beginner app works on all platforms including desktop (the one used for the demo photos)
## Library Used
- `english_words: 4.0.0`: Used to generate a random word made of a pair of words.
- `provider: 6.1.2`: Used for state management
  - To store the current generated word.
  - To toggle between favorite and unfavorite word.
  - To hold a list of favorite words.


