# Chuckles with Chuck 🤠  

A simple single-page application (SPA) built with React that fetches and displays hilarious Chuck Norris jokes using the Chuck Norris Jokes API.

## About 

A single-page application (SPA) built with **Next.js**, **Material-UI**, and **Redux**, which displays Chuck Norris jokes fetched from the [Chuck Norris API](https://api.chucknorris.io/). The application allows users to view random jokes, search for jokes, and filter jokes by category.  

## Features  

- **Random Joke Display**: Shows a random Chuck Norris joke when the page loads.  
- **Interactive Search**: Users can search for a joke containing specific text strings.  
- **Category Selection**: Jokes can be filtered by category, and the category of the displayed joke is indicated.  
- **Error Notifications**: Displays a message when no jokes match the search criteria.

## Tech Stack  

- **Framework**: Next.js  
- **UI Library**: Material-UI  
- **API**: [Chuck Norris API](https://api.chucknorris.io/)  
- **Package Manager**: Yarn

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/micihime/chuck-joke-spa.git
2. Navigate to the project directory:
   ```bash
   cd chuck-joke-spa
3. Install dependencies using Yarn:
   ```bash
   yarn install
4. Start the development server:
   ```bash
   yarn dev
5. Open the app in your browser:
   ```bash
   http://localhost:3000

## Folder Structure

   ```plaintext
   app/  
   ├── components/     # Reusable React components  
   └── utils/          # Helper functions and constants  
   ```

## Usage

- View a Random Joke: Visit the homepage to see a random Chuck Norris joke.
- Search for a Joke: Use the search bar to find a joke containing a specific string.
- Filter by Category: Select a category from the dropdown to view a random joke from that category.
