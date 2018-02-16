# WheelOfFortune_Project2
Second project on 2nd Phase of Android Google Developer Nanodegree Scholarship

I was inspired by recent TV remake of the quiz game from my childhood - it is called Koło Fortuny. It occurred that it is also known abroad as Wheel of Fortune :)
The background is a real logo of the show so I just needed to use it :smiley: I tried to adjust the rest of the screen to complement it as well as I could.

For the background:
We have 2 players in the game. There is also a lot of possibilities to score money. I decided to choose 3 of them: +1500, +250, +100. There is also a possibility to go bankrupt - hence an appropriate button in my app. The last option on the wheel is to score a prize. It was also included in my app. As prizes are not in money (e.g. car, video game, …) they are not adding anything to score, but I added their additional/smaller counter for each player.

App is prepared for both smaller and larger devices. I am personally not a fan of needing to scroll down my screen to find an important button at the end of any app I use. Therefore I decided to set the reset button as always visible on the page (it is outside of ).

Scores are also not disappearing while changing device’s rotation (suggestion from the mentor). To achieve that I added some Java code:
onSaveInstanceState
and updated
onCreate.

App is also supported by ScrollView with RESET button always visible (no matter the size of the screen you are using).
And additionally I have separate .xml code for portrait and landscape view :) It can be noticed by RESET button location difference.
