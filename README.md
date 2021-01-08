# Eye Contact

![Video Chat](images/image-from-rawpixel-id-2335469-jpeg.jpg)

This is a placeholder for project **Eye Contact**, a tool meant to give us back this essential nonverbal form of communication while using video chat applications. Many of us feel disconnected when the people we are activaly engaged with remotely don't look at us while we talk, and this project hopes to bring eye contact back using machine learning.

### Brief Description

Imagine a scenario where you (hereon referred to as the user) are actively video conferencing with friends (hereon referred to as viewers). The user's videofeed is fed to an algorithm to determine their gaze. This data is then used in combination with the known position of the viewers' video feeds to determine which viewer the user is looking at. This data is then sent to the viewers. Similarly the user receives a list of viewers, who are actively looking at this user's video, and their gaze is manipulated using an algorithm to make it look as if they were looking right at the user. When this is done between all parties of the video conference, eye contact can be established between parties who are looking at each other on the screen.

### Technology

Pretty much all the pieces for this are available is some form. As I am most familiar with web technologies, my aim is to implement this using them. WebRTC is ready to be used to establish video and data connections between the parties. TensorFlow models are ready to be used in the broser to detect faces and gaze direction. The only missing piece seems to be the algorithm that can augment a video feed, smoothly shifting the user's gaze from any point on the screen to looking right at the camera.

### Product

I'm really not interested in creating yet another video conferencing platform, so I intend to provide modules that can be readily added to existing web-based platforms. This could be easily done in the form of browser extensions for the desktop. Hopefully platform providers would pick up the idea and implement it in the products hereafter making this project obsolete.
