# Trivia-Battle-Game
- WORK INTEGRATED PROJECT

<p>The application will be developed for the iOS mobile platform (SwiftUI) and it will consist of a game in which users will have to answer a series of questions in order to reduce the life bar and defeat their enemy. Users will have the possibility to sign up and sign in and all the collected information of the user will be collected with the features of authentication and Firestore Database of Firebase.</p>
  
<p>Firebase will be used for allowing the user to create their account with an email and password; the app will check if the information is valid, in case of error or lack of information the app will show an alert informing that it is required to fill all the boxes and give the correct information. Additionally, the feature of Firestore Database will be used, this feature will allow us to store the user information and history of games. Using the collected information of the collections the app will present a profile option where users will be able to see their game record, energy, materials, equipment levels, and the user's basic information.</p>
  
<p>Once the profile is created, the user will be able to choose their champion from a list of various heroes (the user will be able to change their champion every time they start a new game). Once the champion has been chosen, the user can go to the level screen which contains a list of enemies to choose from. Once they select the level, the application will navigate the user to the game screen in which for each correct answer the life bar of the enemy will reduce, as well as for each incorrect answer the life bar of the champion will be reduced. Once the enemy is defeated, the user will earn random materials which the user can later use to upgrade their equipements. If the user lose, then the app will navigate the user back to the champion selection screen without gaining any materials. Regardless of the game result, one energy will be deducted for each game.</p>

<p>There are advertisements in the level selection screen and when the user enter a game. The user can check their performance statics such as the percnetage of correct answers from the profile screen. The profile screen also shows their currently selected champion and the highest level the user had completed. The user can also logout and change their information through the profile screen</p>

- TECHNOLOGIES
  - Project Management (Jira)
  - GitHub (version control)
  - SwiftUI
  - Firebase (Firestore/Authentication)
  - SceneKit (File for Model 3D)
  - Google AdMob (Advertisements)
  - CocoaPods (standard format for managing external libraries)
  - User Notifications
  - NavigationView (Navigation Screen)
  - Google Fonts (Custom Font)
  - WKWebView (Display gif)
  - Blender (Models 3D)
 
https://github.com/arnulfo457/Trivia-Battle-Game/assets/125388195/06781eda-07d7-4f19-98d5-5c5e2b0eaf85

Once the user downloads and opens the application, they could see a splash screen which will be displayed every time the user opens the application.

https://github.com/arnulfo457/Trivia-Battle-Game/assets/125388195/9a83ecf4-b1ca-4c50-ba2c-fd5d7e7379e0

Then, the user will be able to find the login or sign up window if the user does not have an account in our application.

https://github.com/arnulfo457/Trivia-Battle-Game/assets/125388195/a1880620-ecf0-48d9-8d9f-86955117824f

When the user opens the application for the first time, it asks the user if they will allow the app to send notifications since our application sends a daily notification at 20:00 in which it invites the player to play again.

https://github.com/arnulfo457/Trivia-Battle-Game/assets/125388195/128b5b43-7971-4e02-89af-d58d636f662f

Once the user is logged in, they will see the champion screen in which they can select a champion among the 4 possible ones, in addition the player will be able to rotate the champion 3D and see the details of each one of the champions.
Additionally, the user can navigate to the crafting screen which allow the user to level up each of their equipment only if they have the minimum amount of materials.

https://github.com/arnulfo457/Trivia-Battle-Game/assets/125388195/846c4097-16e6-492e-8d25-b0f0f05828b1

Subsequently the player can navigate to the level screen in which to see each of the enemies go to the details of the enemies as well as the amount of energy that the user presents.
As can be seen in the video, our application presents two types of advertisements, which are Banner and Interstitial, the Banner is shown on the levels screen and in game: on the other hand, the Interstitial is shown every time the player clicks the "Play" button. now”

https://github.com/arnulfo457/Trivia-Battle-Game/assets/125388195/355713df-0140-425b-a5b7-7d97f5f498b1

Once the player sees the warning he will be able to fight the enemy.
In this video you can see that every time the player answers the question incorrectly the enemy will attack and consequently the player will lose
