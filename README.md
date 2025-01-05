
Pikachu Stats Viewer
Overview
The Pikachu Stats Viewer is a simple, interactive web application that fetches and displays data about Pikachu and other Pokémon from the Pokémon API. Users can view detailed Pokémon stats, types, abilities, and images, as well as manage a list of favorite Pokémon and submit comments.

The application is built using HTML, CSS, and JavaScript, and leverages asynchronous requests to fetch data from the Pokémon API. It’s designed to be a fun, engaging tool for Pokémon fans.

Features
Pokémon Stats: Displays detailed information such as HP, Attack, Defense, and Speed.
Favorite Pokémon: Users can add Pokémon to a favorites list.
Comments Section: Allows users to leave comments about the Pokémon displayed.
Responsive Design: Optimized for desktop and mobile devices.
Dynamic Data: Data is fetched asynchronously from the Pokémon API and displayed in real-time.
Screenshots

Technologies Used
HTML: To structure the content of the page.
CSS: For styling the layout and creating visually appealing effects.
JavaScript: For interacting with the Pokémon API, handling user inputs, and managing data.
Fetch API: To make asynchronous HTTP requests to the Pokémon API to retrieve Pokémon data.
Project Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/andrew72-max/masterPJ.git
Navigate to the project folder:

bash
Copy code
cd pikachu-stats-viewer
Open index.html in your preferred web browser.

You should now be able to interact with the Pokémon Stats Viewer directly in your browser.

How It Works
Fetching Pokémon Data:
Upon page load, the app fetches data from the Pokémon API (pokeapi.co) for several Pokémon using their unique IDs.
Data such as Pokémon name, types, abilities, stats, and image is retrieved and displayed dynamically on the page.
User Interaction:
Add to Favorites: Users can add Pokémon to their favorites list. This list is displayed on the same page.
Submit Comments: Users can leave comments, which are displayed below the Pokémon information. Each comment has a randomly generated user name for fun.
Dynamic Layout:
The app is styled responsively using CSS to ensure it looks good on any device.
It uses flexbox to create a flexible, neat layout for displaying Pokémon data and the favorites list.
How to Use
View Pokémon: The app fetches data about multiple Pokémon (such as Pikachu and others) and displays their stats, abilities, and images.
Add to Favorites: If you like a Pokémon, click the “Add to Favorites” button under the Pokémon to add it to your list.
Submit Comments: Write a comment in the text box and click the "Submit Comment" button to display it below the Pokémon information.
Live Demo
You can view a live demo of the project here.

License
This project is licensed under the MIT License.

MIT License
sql
Copy code
MIT License

Copyright (c) [year] Andrew72-Max

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM,
OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
Future Improvements
Persistent Storage: Currently, the list of favorites and comments is not saved between page reloads. Implementing local storage or a backend would allow users to retain their data.
More Pokémon Data: The app currently fetches data for a set of predefined Pokémon. Adding functionality to search for specific Pokémon or fetch a larger set of data could make the app more interactive.
User Authentication: Implementing a user authentication system would allow users to save their favorites and comments across sessions.
Contributions
Feel free to fork this project and contribute. You can:

Report bugs
Suggest new features
Submit pull requests for improvements
Author
Andrew72-Max
GitHub: @andrew72-max
Email: wwekesa72@gmail.com