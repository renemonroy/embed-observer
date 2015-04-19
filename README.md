# embed-observer
Or Embedio if you dig it. It's a browser's extension to catch the embed of a media through its social network unique page.

## Intro
Suppose you visit a YouTube's video like ['Cute Baby Pandas'](https://www.youtube.com/watch?v=Z4A8pIi-NpU) and you want to get the embed and send it to your server directly.

This extension detects the embed of that video, shows you a button icon in the search bar, obtains the embed code once you click on the button and sends it to your server specified.

### List of detectable embeds
* YouTube
* Vimeo
* Slideshare
* SpeakerDeck
* CodePen
* Kickstarter

## Usage
Just replace the `serverUrl` variable that is at the top of the code on the `background.js` file. Then, you will start getting the code once you click on the icon at top when appears in each detected page.

This assumes that you handle the requests on your server.