Recipe Application

This project is a Recipe Application built with HTML, CSS (Tailwind CSS), and JavaScript. It fetches data from a recipe API and dynamically displays recipe information, allowing users to explore various recipes with ease.

Features

Dynamic Recipe Rendering: Fetches and displays recipes dynamically from the Vegan Recipes Database API.

Responsive Design: Styled using Tailwind CSS for a clean and modern user interface.

Recipe Details: View detailed information about each recipe, including ingredients, preparation steps, and images.

LocalStorage Caching: Caches recipe data in LocalStorage to reduce API calls and improve performance.

Demo



Technologies Used

Frontend:

HTML5

CSS (Tailwind CSS)

JavaScript

API:

Vegan Recipes Database API

Project Structure

|-- index.html          # Main page to display recipe cards
|-- recipe.html         # Detailed recipe view page
|-- index.js            # JavaScript for dynamic recipe rendering on the main page
|-- recipe.js           # JavaScript for fetching and displaying recipe details
|-- styles.css          # Tailwind CSS integration
|-- assets/             # Folder for images and other assets

Installation

Clone the repository:

git clone https://github.com/your-username/recipe-application.git

Navigate to the project directory:

cd recipe-application

Open the index.html file in your browser to view the application.

Usage

Open the application in your browser.

Browse through the recipes displayed on the main page.

Click on "View Recipe" to see detailed information about a specific recipe.

API Integration

This project uses the Vegan Recipes Database API to fetch recipe data. To use this API:

Sign up on RapidAPI and subscribe to the Vegan Recipes Database API.

Replace the placeholder API key in index.js and recipe.js with your own API key:

const options = {
    method: 'GET',
    headers: {
        'X-RapidAPI-Key': 'your-api-key',
        'X-RapidAPI-Host': 'the-vegan-recipes-db.p.rapidapi.com'
    }
};

Screenshots

Main Page



Recipe Details Page



Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue to discuss improvements or bug fixes.

License

This project is licensed under the MIT License.

Author: Your Name

Vishal Kondi

