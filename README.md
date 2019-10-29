# Video Doorbell, Lab 7

*A lab report by Ben Kadosh*


## Part A. HelloYou from the Raspberry Pi

[HelloYou Sketch - Youtube Link](https://www.youtube.com/watch?v=FlI-6Wrdn8Y&feature=youtu.be)


## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

Below are links to two text files: the diff output for the two files, and a file with my own highlevel overview of the major changes. 

[Diff Output]()
[Highlevel Changes]()

In summary, the major changes relate to elements being added to pictureServer, which include creating variables to start up the webcam, adding functionality to take a picture with the webcam, and displaying the image to the web browser.

**b. Include a video of your working video doorbell**
[Working Doorbell - Youtube Link]()

## Part C. Make it your own

For my own implementation, I added a knocking background noise when the "doorbell" is rung, and added text output to display a "who's there" call and response to acknowledge it's me :)
[Ben's own Doorbell In Action - Youtube Link]()
