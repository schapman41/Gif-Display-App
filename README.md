# Gif Display App
Let's now write an app that displays a .gif file

Start by creating a new React application using the create-react-app tool

In the src folder of your React app, create a new folder called assets. This is where you will save your .gif file.

Save your chosen .gif file in the assets folder and make note of the file path. For example, if the file is called mygif.gif, the file path would be src/assets/mygif.gif. 

I chose this one:
(https://media.tenor.com/bD9vHNiR1rQAAAAd/boom-mind-blown.gif)

In the src folder, open the App.js file. This file contains the basic structure of your React application.

In the App.js file, create a functional component called App that returns a basic HTML structure with an img tag to display the .gif file.

In the img tag, include the src attribute, and set it to the imported mygif variable.

Add a description of where to save the .gif file in order for it to display, for example, you can add a paragraph tag with the description

In the command line interface, run the command npm start to start the development server and open the application in the browser. You should now see the .gif file displayed on the screen.
