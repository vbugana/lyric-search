# LyricsSearch App

Find songs, artists and lyrics using the [lyrics.ovh](https://lyrics.ovh) API

## Project Specifications

- Display UI with song/artist input
- Fetch songs/artists and put in DOM
- Add pagination
- Add get lyrics functionality and display in DOM

## Description

This App creates a web application for searching song lyrics using the API provided by "https://api.lyrics.ovh".

The code defines several variables to refer to various HTML elements such as the search form, search input field, search result area, and the "more" section for pagination buttons. It then defines a function called `searchSongs` that sends a GET request to the lyrics API and retrieves the search results for the provided search term. The function `showData` is called to display the search results on the page. This function uses the retrieved data to create an unordered list of songs with artist and song titles along with a "Get Lyrics" button for each song.

The code also defines an event listener on the search form that calls `searchSongs` function when the user submits a search term. Another event listener is defined on the search result area that waits for the "Get Lyrics" button to be clicked. When the button is clicked, it extracts the artist name and song title from the button's data attributes and passes them to a function called getLyrics. This function then retrieves the lyrics for the selected song and displays them on the page.

Additionally, the code defines a function called `getMoreSongs` that is used for pagination when the user clicks on "Prev" or "Next" buttons. This function sends a GET request to the lyrics API with the provided URL to retrieve the next or previous set of songs. It then calls the `showData` function to display the new set of songs on the page.

Overall, the code creates a functional web application for searching song lyrics using the API provided by "https://api.lyrics.ovh".

## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Technologies Used

![HTML 5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS 3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)


## 😂 Here is a random joke that'll make you laugh!

![Jokes Card](https://readme-jokes.vercel.app/api)

https://mdb.pushkaryadav.in/generate
