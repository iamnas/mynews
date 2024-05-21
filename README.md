# MyNews

MyNews is a news application that fetches the latest news from [newsapi.org](https://newsapi.org/). It provides users with up-to-date news articles from various sources and categories, ensuring they stay informed about current events.

## Features

- **Latest News**: Get the most recent news articles from around the world.
- **Categories**: Browse news by different categories such as technology, sports, business, entertainment, and more.
- **Search**: Search for specific news articles or topics.
- **Responsive Design**: Accessible on both mobile and desktop devices.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed the latest version of [Node.js](https://nodejs.org/).
- You have an API key from [newsapi.org](https://newsapi.org/). You can get a free API key by signing up on their website.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/iamnas/mynews.git
    cd mynews
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and add your NewsAPI key:

    ```bash
    REACT_APP_NEWS_API=your_newsapi_key_here
    ```

4. Start the development server:

    ```bash
    npm start
    ```

## Usage

Once the development server is running, open your browser and navigate to `http://localhost:3000` to start using the application.

### Fetching News

The application fetches news from the NewsAPI using the provided API key. It makes GET requests to the API and displays the articles on the homepage. You can browse articles by categories or use the search functionality to find specific news.

### API Endpoints

The application interacts with the following endpoints of the NewsAPI:

- **Top Headlines**: `https://newsapi.org/v2/top-headlines`
- **Everything**: `https://newsapi.org/v2/everything`
- **Sources**: `https://newsapi.org/v2/sources`

## Contributing

To contribute to MyNews, follow these steps:

1. Fork the repository.
2. Create a new branch:

    ```bash
    git checkout -b feature-branch
    ```

3. Make your changes and commit them:

    ```bash
    git commit -m 'Add some feature'
    ```

4. Push to the branch:

    ```bash
    git push origin feature-branch
    ```

5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.


---