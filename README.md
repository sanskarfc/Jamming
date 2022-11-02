# Jamming

Jamming is a React app for creating new playlists with Spotify.

## Objective

> In this project, I built a React web application called Jammming. I used the knowledge of React components, state, and requests with the Spotify API to build a website that allows users to search the Spotify library, create a custom playlist, then save it to their Spotify account.

![image](https://user-images.githubusercontent.com/10026538/65839342-303a1d00-e304-11e9-84ec-43e7d8b2365a.png)

## Features

* Spotify Login — the first time a user searches for a song, album, or artist, Spotify will ask them to log in or set up a new account.
* Search by Song, Album, or Artist — a user can type the name of a song, artist, or album into the search bar and click the SEARCH button.
* Populate Results List — Jammming displays the list of returned tracks from the user’s query.
* Add Song to a Custom Playlist — users can add a track to their playlist by selecting a + sign on the right side of the track’s display container.
* Remove Song from Custom Playlist — users can remove a track from their playlist by selecting a - sign on the right side of the track’s display container.
* Change Playlist Title — users can change the title of their custom playlist.
* Save Playlist to Account — users can save their custom playlist by clicking a button called SAVE TO SPOTIFY.

## Potential improvements

* Pressing enter triggers a search (done)
* After user redirect on login, restoring the search term from before the redirect (done)
* Include preview samples for each track
* Only display songs not currently present in the playlist in the search results
* Add a loading screen while playlist is saving
* Update the access token logic to expire at exactly the right time
* Ensure playlist information doesn’t get cleared if a user has to refresh their access token
