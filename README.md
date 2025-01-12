Link to Github:
https://github.com/islamsaadi/MobileSecurity_HW2

Process:
1- Decompiling the apk of the game using this website: http://www.javadecompilers.com/apk

2- Extract the files, look into the activity files which we need to understand which layouts and other resources needs to run the the app, check also if any permissions were needed in the MAINFEST file.

3- Build a new project in Android studio and take the activity files, resources .. etc, what I found in step 2 to run the app.

4- Understand the algorithm of the game to start the app and try to play it.

5- After first play, I see that there is a bug, after debugging the app I found that there is a problem in retrieving the data from the URL, a deep look into the URL I found the problem of the hidden added text, I fixed the URL, and the app runs perfect now.

I used my ID number to play the game and the result was:
**Survived in Washington**
