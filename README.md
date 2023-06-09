# Simple video-podcast generator

Welcome to my second project of the [Code institute](https://codeinstitute.net)!

I'm happy to meet my second challenge in javascript programming (+html+css). And to meet my challenge I have chosen to create a web tool that allows me to automate the generation of "lines of commands" to join an audio with several images and in this way create a video, that can be uploaded later to youtube or other video hosting platform. The command line executes the program "ffmpeg" with several parameters that specify the name of the images to insert in the video, at what moment each image is inserted (time) and the audio that composes it.


![Gallery Example](https://github.com/patchamama/PP2-Simple-Video_podcast-generator/blob/main/doc/PP2-screenshot.png)

## The goal

The objective of this program is to provide a visual tool to better manage, test and check the position of the images to be added to an audio to make a video (with the sequence of images selected in the time defined by the user). In this way, the task and configuration of the images in relation to the time position in audio with which it would be related is greatly facilitated.

## Features

In order to achieve the objective, we start with the minimum multimedia materials necessary:
- an audio,
- one or several images.

To connect the images with the audio has been defined some sections with different goal:

### Dataset section
  - Allows you to choose a predefined group of data (images+sound).

### Audio section
  - Section with the audio to be selected with a player (in the upper center). It allows you to play the audio and move with the control bar, to every direct and desired position of the audio.

### Images section
  - Candidate images to be selected (left panel). 

### Work section
  - Section that integrates the audio and the images (in the center of the page) that allows to visualize and choose each previously selected image and to change its position, delete it or insert new images.

### Result section
  - In this section, the "command line" is generated to be executed (terminal) and generate the desired final video.

### Features Left to Implement

  - Add the possibility of integrating the application with a backend and a script programmed ( php, python, nodejs) that allows to upload the multimedia files to the server and use this script on it. 
  - Add other online video generator options (mencoder).

## Testing 

  - It would be good to test a larger number of data (audios and videos) to better test the performance and correct possible errors not seen due to the small size of the data sample.
  - To avoid errors, the page has been tested with several browsers on different operating systems and devices.
  - It has been tested if the page is responsive with different screen resolutions (devtools) and devices.
  - No errors have been detected in the official html validator: [W3C validator](https://validator.w3.org/nu/?doc=https://patchamama.github.io/PP2-Simple-Video_podcast-generator/)
  - No error has been detected in the official css validator: [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fpatchamama.github.io%2FPP2-Simple-Video_podcast-generator%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=es)
  - Performance tests were done using lightouse (devtools) in chrome and the data returned is relative good (I have not reduced the size of the images too much so as not to affect the quality of the final video generated by the command line.).
  ![results](https://github.com/patchamama/PP2-Simple-Video_podcast-generator/blob/main/doc/performance.png)

  - The command line tests were performed on a MacBook Pro (Ventura) laptop terminal and on a server running Ubuntu Linux. 

![results](https://github.com/patchamama/PP2-Simple-Video_podcast-generator/blob/main/doc/preview-command-line.png)

![results](https://github.com/patchamama/PP2-Simple-Video_podcast-generator/blob/main/doc/command-line-example.png)

### Unfixed Bugs

At the moment no bugs have been detected but it is necessary to increase the possibilities of testing the tool on different devices. The tests have been performed on windows and macOSX using firefox, safari and google chrome. A Samsung Android phone with google chrome was also used.

## Deployment

The project has been completely developed based on a template from the [Code Institute](https://github.com/Code-Institute-Org/gitpod-full-template) in github and after the replication, gitpod has been used as an online IDE that allows updates to be made in github. To deploy the application, got here (this page) to the "Settings" section over right > left menu "Pages" and from here you can access directly to the link: https://patchamama.github.io/PP2-Simple-Video_podcast-generator/ 

## Credits 

- The sample images used are from: https://www.pexels.com/
- Menu Icons and sections are from: https://fontawesome.com/
- Much of the knowledge practised here is a result of the exercises and ideas learned in the [Code institute](https://codeinstitute.net) training period and adapted to my needs. 
- he fonts used are from google font (Lora & Montserrat) as can be seen in the source code: https://fonts.google.com/
- To the html and css formater was using: https://codebeautify.org/
- To make corrections with margins and force word wrap through CSS:  https://stackoverflow.com/questions/18891755/force-word-wrap-through-css
- The audios used in Spanish are from a joint work done with a friend (María Magdalena) during the pandemic for the creation of a podcast. The audios are from two short stories from the book "La vaca que lloraba" by Ajahn Brahm.
- The image used when there is not images selected is from: https://upload.wikimedia.org/wikipedia/commons/thumb/a/ac/No_image_available.svg/450px-No_image_available.svg.png

All photos are open source licensed.