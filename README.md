# Face Recognition Web Development (Front end) 
This repository contains the front end code for this project, which implements webpages for sign in, register, and a home page for users to submit urls for face recognition. A version deployed on Heroku can be tried out [here](https://face-recognition-vd.herokuapp.com/)

To  use the face recognition web, register or sign in, then simply paste a image url, [like this](https://goop-img.com/wp-content/uploads/2020/06/Mask-Group-2.png), to see the image displayed with the face in it marked by a square frame.

The app was built with HTML5 for text content, CSS3 for visuals, Javascript and React for interactive user interface. Libraries, such as particles.js for creating the floating particles on the page as decoration, were used to make it look fancy. The face recognition function was implemented with the Clarifai APT. (They actually provide various AI models you can explore and exploit!)

#### Tips to adapt it for your own use
1. Clone this repo
2. Run `npm install`
3. Run `npm start`
4. You must add your own API key in the `src/App.js` file to connect to Clarifai. You can grab Clarifai API key [here](https://www.clarifai.com/)
5. This code works together with the [back end](https://github.com/FuAdventure/face-recognition-api/edit/main/README.md). If you deploy the back end on a remote platform, remember to change the locations of the fetches in `App.js`, `signin.js`, `register.js` to your back end host.
