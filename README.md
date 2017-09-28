# DZ-music-bot

* `npm install` to install the dependencies
* Create a `.env` file for your Spotify and Twitter credentials (clientId, clientSecret & CONSUMER_KEY, CONSUMER_SECRET, ACCESS_TOKEN, ACCESS_TOKEN_SECRET)
* Create credentials if need be and add them 
  * https://developer.spotify.com/web-api/authorization-guide/
  * https://apps.twitter.com/
* Add Credentials to `.env`
* Run `npm start` 
* Check the console to see if it worked:
  * The Artist, Song Name, and URI should appear in the console if it worked.
  * If it didn't you should see an error message


* You can point it at a different playlist by changing line 57 return `Spotify.api.getPlaylistTracks('PLAYLISTID', 'USERID')` 
  * https://github.com/thelinmichael/spotify-web-api-node