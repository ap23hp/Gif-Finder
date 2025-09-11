# Gif-Finder

GIF Search App

#A simple web application that fetches and displays GIFs using the Giphy API. Users can search for specific GIFs or click a button to fetch a random GIF.

#Features

Display random GIFs by default (cats).

Search for specific GIFs using the input box.

Handle scenarios when no GIFs are found with a placeholder image.

Asynchronous fetching without refreshing the page.

Error handling for network issues.

#Technologies Used

HTML

CSS

JavaScript (Fetch API)

Giphy API


##Notes:

The app uses asynchronous fetch calls to retrieve GIFs without reloading the page.

When the search query doesn’t return a result, a default “Loading” placeholder is displayed.

Errors during fetching are handled with .catch() in the JS code.
