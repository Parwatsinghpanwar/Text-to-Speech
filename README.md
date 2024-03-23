# Text-to-Speech
Build a Text to Speech Converter using HTML, CSS &amp; Javascript
A text-to-speech converter is an application that is used to convert the text content entered by the user into speech with a click of a button. A text-to-speech converter should have a text area at the top so that, the user can enter a long text to be converted into speech followed by a button that converts the entered text into speech and plays the sound on click to it. In this article, we will build a fully responsive text-to-speech converter using HTML, CSS, and JavaScript.

Approach:
Create a folder with the project name and create the required HTML, CSS, and JavaScript files as shown in the project structure.
Now, use the HTML tags like textarea, button, div, head, body etc. to define the structure of the website.
Add the styles to the HTML tags used to define the structure by selecting them with the help of given IDs and Classes.
Utilise the speechSynthesis API of the global window object and the SpeechSynthesisUtterance to create a utteraance of the entered text.
Next, use the speak() method of the speechSynthesis API to speak or play the created utterance as a speech.
Handle the errors efficiently if user have not provided any text to converter
