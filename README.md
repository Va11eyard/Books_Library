## Deploy
# https://books-library-5v9s.onrender.com

A web application that provides Weather information, a Translator, the The New York Times Best Sellers lists and Dictionary for Word. The application was created using Node.js, Express and integrates with external APIs to get data.

## Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.

## Installation

1. Clone the repository:

   ```bash
   git clone `https://github.com/Va11eyard/Books_Library.git`

2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Start the server using `nodemon server.js`.

## Usage
- The server runs on port 3000.


### Structure
```
├── Books_Library/
│   ├── node_modules/
│   ├── client/
│   │   ├── TranslateClient.js
│   ├── models/  [For mongoose schemas]
│   │   ├── NumberModel.js
│   │   ├── Translation.js
│   │   ├── User.js
│   │   ├── WeatherData.js
│   ├── routes/  [Server-side routes for request handling]
│   │   ├── routes.js
│   ├── views/  [Contains client-side files (ejs)]
│   │   ├── admin.ejs
│   │   ├── dictionary.ejs
│   │   ├── history.ejs
│   │   ├── login.js
│   │   ├── number.ejs
│   │   ├── register.ejs
│   │   ├── translate.js
│   │   ├── weather.ejs
│   ├── README.md
│   ├── package-lock.json
│   ├── package.json
│   ├── server.js
```


## Features
- **Weather Information:**
  - Real-time weather data including temperature, description, icon.
  - Enter any city name to retrieve relevant weather data.
- **Translator:**
  - Allows you to translate a word to another language.
- **The New York Times bestsellers:**
  - Provides information about book reviews and The New York Times Best Sellers lists.
- **Dictionary:**
  - Enter any word and choose language, after get a meaning of word.

##
**Note that Weather information and Translator is just additional APIs which has nothing to do with requierments, while Books and Dictionary is APIs about my theme.** 

## Admin information:
- username: Dinmukhammed
- password: Dinmukhammed2207

## Admin page:
**In order to get access to the admin page click the button with house icon** 

## Dependencies
- **Express:** Used for server setup and routing.
- **Body-parser:** Middleware for parsing incoming request bodies.
- **Axios:** Handles HTTP requests.
- **Path:** Helps manage file paths.
- **Nodemon:** Monitors for changes and automatically restarts the server.

## APIs Used
- **OpenWeatherMap API** - for weather data.
- **Google Cloud Translate API** - to translate text into certain languages.
- **Books API** - the Books API provides information about book reviews and The New York Times Best Sellers lists.
- **Yandex dictionary** - to get meaning of words in another languages


### Author
Dinmukhammed Mynzhasar, SE - 2207
