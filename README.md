# Webdev Starter Project Master

This project will start a new Web Development project using NodeJs and NPM scripts. This project will help you automate the creation of your project which will include HTML, CSS (Sass) and Javascript.

## Requirements
You will need NodeJS to run the npm scripts in this project. NPM will install with the NodeJS installation. [NodeJS](http://nodejs.org) website

## Install
You will need to clone the repository to your local machine where you what your project to run, or you can download the zip folder.

Change your directory to the cloned repository.

If you clone the repository you need to delete the Node_Modules folder and the .git folder or with the zip folder you can copy in everything except Node_Modules and .git folders into your project folder.
  
`npm install`

This will install the dependencies associated with this project.

Once you have installed the dependencies you can change the HTML, CSS (SASS) and Javascript to make it your own.

## How to use
You will have a Build folder that will contain your *production* files for HTML, CSS, Javascript and images. You will only be changing the HTML files and Javascript files in this location. There will be a Source folder that contains all the SASS files where you will create all of your preprocessed CSS files.

Then you will enter from the command line to run script that monitors all SASS files for changes.

`npm start` 
     
*VSCODE USERS*
 You can use the built in terminal to run and monitor the changes when they are made. Also you can use Live Server to run your project in the browsers to see what your project looks like as you build it. If you make changes to you HTMl files, SCSS files or JS files the browser will automatically reload.

This can be used with Atom or Sublime Text , but you will need to use their Live Server setup.