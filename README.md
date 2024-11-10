# Monito Pets 🐶
This is a quick project made while discovering SCSS and SASS. To be more precise, it's a 16/9-sized build of a desktop website based on [this Figma template](https://www.figma.com/design/OHLPgA07wTWGV9pnJxjnzy/%5BFREE-TEMPLATE%5D-eCommerce-Website---Monito-Pets-for-Best-(Community)-(Community)?node-id=49-188).<br>

The objective of the build is to understand the basics of SCSS file structures, partials, variables, mixins and links between these features.<br>
Please note that the mobile version has not been implemented.

## Viewing 👀 
To view this website, you simply have to:
- Download the repo files
- Extract the ZIP file wherever you want
- Open the index.html file in your browser

## Editing ✏️
To editing the source code, especially the SCSS files, you need to do two things first:
- Download and install [Node.js](https://nodejs.org/)
- Install SASS for Node.js by running ```npm install -g sass``` in an elevated Command Prompt
<br>

After these steps, you can open the website folder in a IDE and edit the files.<br>
If you modify the SCSS files, you need to recompile the CSS file with SASS.<br>
To do so, open a terminal at the root of the website folder and run ```sass scss/main.scss:style.css --watch --style=compressed```.

- ```--watch``` means that the command will keep running and recompile the CSS file after any change in any SCSS file, you can press CTRL + C to stop the command. You can remove this argument to run the command once.<br><br>
- ```--style=compressed``` means that SASS will compile the CSS in a minified and lightweight style, with no line breaks and no whitespaces. You can remove this argument to compile the CSS in a readable style.
