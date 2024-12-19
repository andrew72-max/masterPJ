# Pikachu Stats Viewer

## Overview
This project is a simple web application that allows users to view Pokémon information, specifically Pikachu and other Pokémon, by fetching data from the [PokéAPI](https://pokeapi.co/). Users can see various details like types, abilities, stats, and images of Pokémon. Additionally, the app has a comment section where users can leave comments and interact with the Pokémon data.

## Features
- **Display Pokémon Information:** Fetches data for multiple Pokémon (including Pikachu) and displays their types, abilities, stats, and images.
- **Comment Section:** Users can submit comments that are displayed on the page.
- **Favorite Button:** Users can add Pokémon to their favorites (though it currently only shows an alert).

## Technologies Used
- **HTML**: Structure of the webpage.
- **CSS**: Styling of the page to make it visually appealing.
- **JavaScript**: Handles functionality like fetching Pokémon data, displaying it, submitting comments, and toggling favorites.

## How It Works
- When the page loads, the script fetches Pokémon data (including Pikachu) from the [PokéAPI](https://pokeapi.co/).
- The data for each Pokémon, including its name, types, abilities, stats, and an image, is displayed on the page.
- Users can add comments, which will be displayed below the input field after submission.
- The "Add to Favorites" button allows users to favorite a Pokémon (currently just shows an alert).

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, etc.)
- An internet connection to fetch Pokémon data from the PokéAPI.

### Instructions
1. Clone or download this repository.
2. Open the `index.html` file in a web browser.
3. The page will automatically load Pokémon data, including Pikachu, and display it.
4. Interact with the comment section by adding comments.
5. Click "Add to Favorites" on any Pokémon to add them to your favorites (currently just shows an alert).

## Customization
- You can modify the list of Pokémon IDs in the `pokemonIds` array to display different Pokémon.
- You can adjust the CSS to change the look and feel of the page.

## Contributing
Feel free to fork this repository and create pull requests to improve the project. If you encounter any issues or have suggestions, please open an issue.

## License
This project is open source and available under the [MIT License](LICENSE).
