# MapLocation
Overview
This project demonstrates a simple animated map using the Mapbox GL JS library. It displays a map with a moving marker that simulates a bus traveling between predefined bus stops. Users can click a button to start the animation.

Features
Interactive Map: Utilizes Mapbox to render a map.
Marker Animation: A marker moves between specific bus stops on the map when a button is clicked.
Responsive Design: The map fills the entire browser window.
Prerequisites
A modern web browser (Chrome, Firefox, etc.) to run the HTML file.
A valid Mapbox access token to use the Mapbox API.
How to Use
Clone the Repository: Download or clone this repository to your local machine.
Set Up Mapbox Access Token: Replace the placeholder access token in the JavaScript code with your own Mapbox access token to avoid issues.
Open the HTML File: Open index.html (or whatever you've named it) in a web browser.
Start Animation: Click the "Gandhipuram and Sulur" button to start the marker animation.
Code Structure
HTML: Basic structure with a <div> for the map and a button overlay for user interaction.
CSS: Styles to remove margins and set the map to fill the screen.
JavaScript:
Map Initialization: The map is initialized with a center point and zoom level.
Bus Stops: An array of longitude and latitude pairs that represent the bus stops.
Marker Movement: The move() function updates the marker's position at intervals, creating an animation effect.
Customization
Bus Stops: You can add or modify the bus stops in the busStops array to change the marker's path.
Animation Speed: Adjust the setTimeout duration in the move() function to speed up or slow down the marker's movement.
License
This project is open-source and available for personal or educational use. Feel free to modify and expand upon it!

Acknowledgments
This project leverages the powerful Mapbox GL JS library to create engaging map visualizations.
