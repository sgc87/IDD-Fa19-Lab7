# Video Doorbell, Lab 7

*A lab report by Samuel Choi*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

[Link to demo video](https://youtu.be/jnzSSknBo44)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

Firstly, there's there the inclusion of the extra button for taking the picture. Also, the variables in the pictureServer file are dynamic, whereas in the server file, they're static. Also, pictureServer.js has the NodeWebcam variable, which is used to take, store, and upload the piture from the webcam. 

**b. Include a video of your working video doorbell**

[Video of working doorbell](https://youtu.be/d132xfT4NHg)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

I've attempted to implement Canva, GM, and OpenCV, but what I already had seemed to work pretty well. I modified the Arduino code in a hybrid of past labs. I took the pressure sensor and used that as the camera trigger so that it takes a picture of the burgler or trespasser. 

**b. Upload a video of your working modified project**

[Demo video of burgler photo capture system](https://youtu.be/F2tOV9apk38)
