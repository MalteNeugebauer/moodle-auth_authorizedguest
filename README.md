# Authorized Guest Plugin for Moodle
This authentication plugin allows users to be automatically logged in, if a specific paramter is set in the Moodle URL.
A typical use case is a demo system. If you want to demonstrate some features that would usually require creating an account like attempting a quiz, this plugin allows user  to be automatically logged in with previously created guest accounts. The demonstrator just needs to provide the URL to the quiz and add the trigger paramter to the URL (default: '...&authorizedguest').

## Demo
[This Moodle system](https://moodleresearch.hs-bochum.de) demonstrates the usage of the plugin. The provided links to quizzes on the start page are equipped with the 'authorizedguest' parameter. This serves logging in with guest credentials, allowing users to attempt the quizzes, although not logged in.

## Video
The following video illustrates how the plugin works.
![Video demonstrating the effect of the plugin](demo_video.gif)

## Contribution
If you want to contribute to this work, please use GitHub's pull requests or issues. You are also welcome to simply write me a mail: malte.neugebauer@hs-bochum.de.

## License
This work is published under the MIT license.