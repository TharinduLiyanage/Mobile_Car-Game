# Mobile_Car-Game
simple mobile game for identify the car make
1. When the application starts, it presents the user with 4 buttons labelled Identify the Car
Make, Hints, Identify the Car Image and Advanced Level.


2. (a) Clicking on the Identify the Car Make button, it should display to the user one
random car image picked randomly (and NOT in the same random sequence every
time the application restarts) from the set of all the car images that your application
contains (the minimum number of images in your application should be 30).
The screen should also display a dropdown list with ALL the names of the car makes
that your application contains (e.g. BMW, Ford, etc.) and a button labelled Iden-
tify. The user should use the list to select the car make that the car image corresponds
(b) As soon as the user submits the answer, the message CORRECT! (in green colour)
or the message WRONG! (in red colour) appears on the screen with the name of the
correct car make in Yellow colour, depending on whether the answer given is correct
or incorrect respectively. 
(c) Following this, the label of the \Identify" button should change to display \Next".
The user should click the \Next" button to advance to another screen presenting him
with a new random car image and giving him the chance to play again. Every time
that this option is chosen a dierent image should be displayed.
to and clicking the \Identify" button he/she submits the guess to the app. 

3. (a) Clicking on the Hints button, it should display to the user one random car image
picked from all the car images that the application contains.
The screen should also display as many dashes as the name of the car make that the
image corresponds to, a textbox and a Submit button. The user will be using the
textbox to type a single character which is part of the name of the car make in an
attempt to guess the make character by character and submit his guesses using the
\Submit" button. Any correct guesses of characters will be replacing the correspond-
ing dashes with the actual character (ALL instances of the dashes corresponding to
that character will be substituted).
For example, if the image displayed belongs to a Mercedes car the following dashes
appear initially:
--------
If the user types the 'C' character in the textbox (either in uppercase or lowercase,
i.e. case insensitive insertion) and clicks on the \Submit" button the area displaying
the dashes will look as:
---C----
Following the above, if the user types the 'E' character and presses submit the dashes
area will look as:
-E-CE-E-
If the user types a character not existing in the name of the car make, the dashes
area remains the same and it does not change its contents.
(b) The user is only allowed up to 3 incorrect character guesses, after which the message
WRONG! (in red colour) appears on the screen with the name of the correct car make
in Yellow colour (when all 3 attempts are used). In case that the user has guessed
all the characters of the car make's name the message CORRECT! should appear in
green colour.
Following either of the cases (i.e. correct or incorrect), the label of the \Submit"
button should change to display \Next". The user should click the \Next" button
to advance to another screen presenting him with a new car image and giving him
the chance to play again. Every time that this option is chosen a dierent car image
should be displayed.

4. Clicking on the Identify the Car Image button, it should display to the user 3 dierent
unique (in terms of make, i.e. no two images should correspond to the same car manu-
facturer) random car images picked from the images that the application contain. The
images should be clickable.
The screen should also display the correct name of a car manufacturer corresponding to
one of the displayed images and a button labelled Next.
The user's aim is to click on the image corresponding to the displayed name, after which (a
single attempt is only allowed) the message CORRECT! (in green colour) or the message
WRONG! (in red colour), depending on whether the answer given is correct or incorrect
respectively.
Following this, the user should click the \Next" button to advance to another screen
presenting him with 3 new random images and giving him the chance to play again. Every
time that this option is chosen dierent images should be displayed.

5. (a) Clicking on the Advanced Level button, it should display to the user 3 dierent unique
random car images picked from all the car images in the application together with 3
textboxes and a Submit button.
The aim of the user in this level is to guess the car manufacturer names of all the 3
displayed cars using the corresponding 3 textboxes. The name of the car manufacturer
corresponding to the rst image should be typed in the rst textbox, the name of
the manufacturer corresponding to the second image should be typed in the second
textbox and the name of the manufacturer corresponding to the third image should
be typed in the third textbox.
The user will be using the \Submit" button to submit his answers. Once he clicks on
that button the answers are checked. If any of the 3 textboxes contains the correct car
make name then that textbox becomes uneditable (i.e. the user cannot change any
characters in it) and in GREEN colour. Any textboxes containing an incorrect guess
remain editable but with a RED colour (either the textbox background becomes red
or the characters face becomes red) .
If the user gets all the 3 manufacturers correct, then the message CORRECT! (in
green colour) appears, the label of the \Submit" button becomes \Next" and clicking
on the button leads the users to a new game with 3 new images being displayed.
(b) The user is allowed only 3 incorrect attempts. A single attempt is considered complete
every time that the \Submit" button is clicked.
After 3 incorrect attempts (i.e. the user has clicked the \Submit" button 3 times
and at least 1 of the 3 car make guesses is incorrect) the message WRONG! (in red
colour) appears on the screen with the names of the correct manufacturers in Yellow
colour displayed just below the incorrect answer(s). (If 1 or 2 guesses are correct
the \Yellow" name does not appear below the correct answers.) After the 3 incorrect
attempts the label of the \Submit" button becomes \Next" and clicking on the button
leads the users to a new game with 3 new images being displayed.
(c) Implement a score for the user which is displayed on the top right of the screen. The
user gets 1 point for every image he guesses correctly, i.e. if in the rst screen he
guesses all 3 car makes correctly he gets 3 points. If after 3 attempts in a screen, he
guesses correctly only 2 manufacturers out of the 3, he gets 2 points and so on.

6. Extend the application by providing a \Switch" button in the app home screen (rst screen
with the 4 buttons game levels) which can be switched on or o. Every time it is switched
on, all of the game levels (all 4 screens) will include a countdown timer, counting from 20
down to 1, every tick occurring after 1 second exactly. The countdown timer is displayed
in the main screen of each game level.
As soon as the counter reaches the value of 0, the current game screen stops, i.e. the mes-
sage CORRECT! or WRONG! is displayed to the user and the \Submit" button changes
status and becomes the \Next" button as described before. Eectively, every time the
counter reaches zero is equivalent to the user pressing once the \Submit" button for that
game level. Levels allowing more than one attempts to the user should start a new timer
for that screen until all attempts are exhausted. Thus, a value of the timer reaching 0 is
functionally EXACTLY like pressing the \Submit" button once.
