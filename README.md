# RandGuess

A simple web based number guessing game using:
* [Flask ](https://palletsprojects.com/p/flask/)
* [W3.CSS](https://www.w3schools.com/w3css/)
* Javascript

Player need to correctly guess the number between 3 and 25.
<br>
Player can adjust the number range and points for correct guess and negative points for incorrect guess changes accordingly.
<br>
![](RandGuess.gif)

<br>

Python Flask is used mainly to generate ramdom number and to verify user guess.
<br>
Remaining features like points and attempt history are computed at client side via Javascript.
<br>
So, the points and attempt history are maintained per user session.