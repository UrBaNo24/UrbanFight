Here's the text translated into English:

# URBAN FIGHT
Final project for the academic year 2022-2023

## Table of Contents
1. [Project Requirements](#project-requirements)
2. [Technologies Used](#technologies-used)
3. [Roadmap Game](#roadmap-game)
4. [Database](#database)
5. [Explainer Video and Presentation](#explainer-video)

📄 **Project Requirements** 📄
-----------------

- [x] 💻 **Frontend** 💻
	- [x] Basic Requirements
		- [x] Code separation into different files.
		- [x] Any dynamically created .html objects should be integrated into the DOM.
		- [x] Local storage for controlling access by different users to the web application.
		- [x] Adding some form of interactivity to the website.
		- [x] Allowing asynchronous design of the website and making requests to the server's database.

	- [x] Additional Requirements
		- [x] If the website has functions like deleting, moving, swapping, etc., objects, use 'drag and drop' implementation.
		- [x] Code modularization (import and export).
		- [x] Generate automated and random behavior for using the web application.
		- [x] Additional functionality.

- [x] 🔌 **Backend** 🔌
	- [x] Basic Requirements
		- [x] Model-View-Controller.
		- [x] Use version 8 of the Laravel framework.
		- [x] Preferably use Laravel UI with Bootstrap as the Starter Kit, but Laravel Breeze with Tailwind CSS can also be used.
		- [x] Local storage to control access by different users to the web application (visitors, registered users, and administrators).
		- [x] Proper session control and route protection through middlewares.
		- [x] Grouping routes, templates, template inheritance, dynamic components, etc.
		- [x] Pagination.
		- [x] Additional features.
		- [x] Follow PHP style standards.
		- [x] Code documentation and justification of decisions made.
		- [x] Use MariaDB or MySQL.
		- [x] Database with a minimum of 5 tables.
		- [x] A minimum of one table for users.
		- [x] Include an E/R schema in the project (README).
		- [x] The database must be created using framework tools (migrations, seeders, and factories) and not directly via PHPMyAdmin or the console.

	- [ ] Additional Requirements
		- [x] Use of Breeze (with Tailwind CSS) or Jetstream (with Tailwind CSS or Bootstrap), in addition to other aspects of the framework that complement the content taught and expand the functionality of the application.
		- [x] Proper language usage.
		- [ ] Use dynamic components based on Vue.js and Axios.js for asynchronous background communication.

- [x] 🚀 **Deployment** 🚀

    - [x] Basic Requirements
		- [x] The web application must be accessible from the internet, i.e., it cannot be deployed on local machines.

	- [x] Additional Requirements	
	    - [x] It is positively valued if the DBMS used by the web application is hosted on a different machine than the one where the web application is deployed.
		- [x] Load balancer.

- [x] 🌈 **Design** 🌈
	- [x] Create a prototype in Figma.
		- [x] Select a dominant color.
		- [x] Create a color palette with the selected dominant color. The palette can be monochromatic, analogous, or complementary.
		- [x] Select a font for the prototype and explain the font choice.
		- [x] Create a harmonious combination with another font, applying different weights in visual hierarchy.
		- [x] Select two colors for text and background, calculating the contrast between them according to the WCAG 2 standard.
		- [x] Apply several examples in your "Visual Balance and Compositional Tension" composition. Explain the choice of these elements and the meaning they contribute.
		- [x] The prototype will be designed for a resolution of 1920 x 1080, using a 12-column grid and for mobile resolution 360 x 640.

	- [x] CSS3
		- [x] Use CSS3 to style the interface; no Frameworks like Bootstrap, Materialize, UIKit, etc., are allowed.
		- [x] The interface design should be "Responsive" using Media Queries, FlexBox, and Grid layout.
		- [x] Use the SASS preprocessor to structure CSS files into a single main.css (main.scss) with @import for other scss files (colors, header, footer, body...).
		- [x] Use the BEM methodology for selector description, variables, etc.
 	
 	- [x] HTML
 		- [x] Insert one multimedia element of each type: video, sound, canvas, and SVG.
 		- [x] Libraries like Chartjs, D3.js, koolChart, Snap.svg, or any other can be used to include charts, animations, image galleries for canvas or SVG.
 
	- [x] Use vector graphics software like Inkscape to create a vector logo that can be animated with Snap.svg or anime.js to fulfill the previous point.

 
 📚 **Technologies Used** 📚
-----------------
 | **Frontend** | **Backend** | **Others** |
 |-------------|-------------|-------------|
 | JQuery      | PHP         | AWS        |
 | SASS        | MySQL       | GIT        |
 | Kaboom      | Laravel     | Photoshop  |
 | JS          |             | Others     |
 
<h2 align="center">📈📝 Roadmap Game</h2>

- [x] Version 1.0
  - [x] Create a database.
  - [x] Create a basic interface.

- [x] Version 2.0 
  - [x] Structure game development.
  - [x] Generate ViewPort.
  - [x] Design the main character.
  - [x] Design the main map.
  - [x] Load audiovisual elements.
  - [x] Create in-game elements.
  - [x] Develop animations.
  - [x] Implement running animation.
  - [x] Implement jump animation.
  - [x] Implement death animation.
  - [x] Implement attack animation.
  - [x] Implement idle character animation.
  - [x] Develop game interface.
  - [x] Implement basic movements.
  - [x] Implement gravity and ground.
  - [x] Implement health bars.
  - [x] Implement counters.

- [x] Version 3.0
  - [x] Implement hitbox.
  - [x] Detect collisions and hits.
  - [x] Animate health bar.
  - [x] Declare a winner.
  - [x] Implement jump mechanics.
  - [x] Detect when the character is on the ground.
  - [x] Implement jump reset.
  - [x] Flip animation when running.
  - [x] Correct hitbox.
  - [x] Implement a tie game.
  - [x] Disable attack at certain points in gameplay.
  - [x] Manage simultaneous key presses efficiently.

- [x] Version 4.0
  - [x] Develop a total of 5 characters.
  - [x] Create a basic character selector.
  - [x] Generate additional statistics for the characters.
  - [x] Synchronize statistics with the database.
  - [x] Synchronize the map with the database.
  - [x] Synchronize sprites with the database.
  - [x] Automatically set the number of sprites for each character.
  - [x] Implement gamepad functionality.
  - [x] Add an attack range for characters.
  - [x] Add scaling for character size.
  - [x] Add attack sounds.
  - [x] Add jump sounds.
  - [x] Add random in-game music.

- [x] Version 5.0
  - [x] Fix bug in declaring a winner.
  - [x] Fix bug in changing the player's direction mid-air.
  - [x] Fix bug in game ending with a counter.
  - [x] Stop movement when the counter ends.
  - [x] Fix bug in death animation.
  - [x] Allow resetting synchronized statistics.
  - [x] View hitboxes in admin mode.
  - [x] Fix bug while running with the gamepad.

- [x] Version 6.0
  - [x] Create avatars for the characters.
  - [x] Improve the visual character selector.
  - [x] Display statistics in the character selector.
  - [x] Implement the option to reset the selection.
  - [x] Add buttons to replay the game.
  - [x] Add a button to exit the game.

<h2 align="center">Database</h2>

![Database Screenshot](https://github.com/aUrbano24/ProyectoFinal-22-23-UrbanFight/base de datos.png)



<h2 align="center">Explainer Video</h2>

Demonstrative video explaining most of the web functions.
[Watch on YouTube](https://youtu.be/hjQDniRGRbo)

Presentation:
[Google Drive Presentation](https://drive.google.com/file/d/1WWuOjxI8q9eLND5EZu1waRgMsbWRexvz/view?usp=sharing)
