# embed-observer
Or Embedio if you dig it. It's a browser's extension to detect an embed of a media through its social network unique page.

## Intro
Suppose you visit a YouTube's video like ['Cute Baby Pandas'](https://www.youtube.com/watch?v=Z4A8pIi-NpU) and you want to save the embed on a server.

This extension detects the embed of that video. It shows you a button icon in the search bar when the page found it, then sends the url to the server once the user clicks on the button.

This assumes that you handle the requests on your server, which might use oembed or something similar to treat the embed code.

### List of current detectable embeds
* YouTube
* Vimeo
* Slideshare
* SpeakerDeck
* CodePen
* Kickstarter

## Usage
Just replace the `serverUrl` variable that is at the top of the code on the `background.js` file. Then, you will start getting the code once you click on the icon at top when appears in each detected page.