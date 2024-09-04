# News Aggregator Web Application

This project is a simple news aggregator web application that fetches and displays news articles from various sources using the [NewsAPI](https://newsapi.org/). Users can search for news on specific topics and navigate through different categories.

## Features

- **Responsive Design**: The application is designed to be responsive, providing a good user experience on both desktop and mobile devices.
- **Search Functionality**: Users can search for news articles by entering a query in the search bar.
- **Category Navigation**: Predefined categories allow users to quickly browse news related to specific topics like "India", "Technology", "Sports", etc.
- **Dynamic Content**: News articles are fetched dynamically from the NewsAPI and displayed as cards on the page.

## Project Structure

The project consists of the following files:

- `index.html`: The main HTML file that defines the structure of the web page.
- `style.css`: The CSS file that contains the styles for the web page, including responsiveness and layout.
- `script.js`: The JavaScript file that handles the fetching of news articles from the API and dynamically updates the web page with the fetched content.

## Setup and Usage

### Prerequisites

- A web browser to view the application.
- An API key from [NewsAPI](https://newsapi.org/) to fetch news articles. Replace the placeholder API key in `script.js` with your own.

### Getting Started

1. **Clone the repository**:

2. **Open the application**:
    - Open the `index.html` file in your preferred web browser.

3. **Using the Application**:
    - The default news category is "India". You can navigate to other categories or use the search bar to find news articles related to specific topics.

### Customization

- **API Key**: Replace the placeholder API key in `script.js` with your own from [NewsAPI](https://newsapi.org/).

  ```javascript
  const API_KEY = "your-api-key-here";
