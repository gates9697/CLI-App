Command line node app that takes in parameters and returns data.
Commands

node liri.js concert-this 'artist/band name here'

This will search the Bands in Town Artist Events API for an artist and render the following information about each event to the terminal:

Name of the venue

Venue location

Date of the Event (use moment to format this as "MM/DD/YYYY")



node liri.js spotify-this-song 'song name here'

This will show the following information about the song in your terminal/bash window

Artist(s)

The song's name

A preview link of the song from Spotify

The album that the song is from



node liri.js movie-this 'movie name here'

This will output the following information to your terminal/bash window:

  * Title of the movie.
  * Year the movie came out.
  * IMDB Rating of the movie.
  * Rotten Tomatoes Rating of the movie.
  * Country where the movie was produced.
  * Language of the movie.
  * Plot of the movie.
  * Actors in the movie.

node liri.js do-what-it-says

Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.



![GitHub Logo](/images/Concert.png)

![GitHub Logo](/images/Song.png)

![GitHub Logo](/images/Movie.png)

![GitHub Logo](/images/Do.png)