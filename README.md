## What is this?

This is a home for 12 custom-made Spotify playlists based on artists' astrological signs that I'd curated. The photography and captions were done by Maurice Sarah in Melbourne, Australia.

## Why is this?

I found this to be a good excuse to tinker with the [spotify-web-api-node](https://www.npmjs.com/package/spotify-web-api-node), a wrapper for the Spotify Web API, and well as [react-spotify-web-playback](https://www.npmjs.com/package/react-spotify-web-playback), a React component built with Spotify's Web Playback SDK. I also wanted to a way to showcase this archival music project.


## How to use:

1. Create a new Spotify API integration [here](https://developer.spotify.com/dashboard/)

2. Once you've created an App with Spotify, select "Edit Settings" and add "http://localhost:3000" as the Redirect URI 

3. Once completed, clone this repository

4. In both directories, simply run `npm i` to install all necessary dependencies

5. In *server.js* replace the `clientID` and `clientSecret` with [your own](https://developer.spotify.com/dashboard/) 

5. Navigate to **spotify-server** and run `$ npm run devStart`

6. Navigate to **spotify-frontend** and run `$ npm run start`

## Is this app currently deployed?

Yes! The frontend is served with Firebase and the backend with Heroku [here](https://zodiacmusicplayer.web.app)