Star Wars Planets Directory

This web application showcases information about planets from the Star Wars universe , along with details about their notable residents. The application uses the Star Wars API (SWAPI) to fetch and display planet information.

Task Requirements ->>
 
Planets Directory:
Fetches and displays information about planets from SWAPI (https://swapi.dev/api/planets/?format=json).
Presents each planet's data in a distinct card, including name, climate, population, and terrain.


Residents Display:
Within each planet's card, provides a list of residents fetched using their respective URLs found in the planet's data.
Displays relevant details such as the resident's name, height, mass, and gender.


Pagination Mechanism:
Implements pagination functionality to navigate through the list of planets.
Leverages the "next" URL provided in the API's response for fetching additional pages.
Ensures user-friendly and intuitive pagination controls.


Styling and Responsiveness:

- Utilizes CSS to style the application with a focus on a clean, engaging layout   and responsive design.
- Delivers a consistent and appealing user experience across various devices and screen sizes.
- Showcases CSS skills with animations, transitions, and modern layout techniques - such as Flexbox or Grid.

Framework/Library Choice:
Developed using React, demonstrating proficiency in API integration, frontend development, and creating a responsive UI.

** Axios is used for making API requests. **

Project Structure

components:

1) PlanetCard.js: React component for displaying individual planet information, including residents.

2) Pagination.js: React component for implementing pagination controls.

3) App.js: Main React component orchestrating the fetching and rendering of planets, along with pagination.

4) App.css :  Stylesheet for styling the application.


Getting Started
Clone the repository:
git clone https://github.com/your-username/star-wars-planets.git


-> Install dependencies:
   
   [cd star-wars-planets]
   [npm install]

 -> Run the application: 
   
   [npm start]
             
Open the application in your browser:
 
 ->  http://localhost:3000

Contributions

Contributions are welcome! Feel free to fork the repository, create a branch, make your enhancements, and submit a pull request.


Acknowledgments
Star Wars API (SWAPI): https://swapi.dev/
May the Force be with you! 🚀🌌





