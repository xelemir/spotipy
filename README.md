# Spotipy Playlist Mixer
Auto-generates a Spotify playlist based on various factors using Python.

# Features:
- A playlist is automatically added to the user's Spotify library.
- A mix of songs is added to the playlist, consisting of:
  -  User's recent top songs
  -  Liked songs
  -  Personal "Repeat Rewind" playlist's songs
  -  "RapCaviar" playlist's songs
  -  "Today's Top Hits" playlist's songs
  -  "Mega Hit Mix"'s songs
- The playlist will refresh everyday at 20:00 (8pm) or whenever the user changes the playlist's description to "clear".
- The user's listening activity will be shared in the playlist's description. This will refresh every minute.

# Credits
Enabled by the Python library "Spotipy" using the official Spotify Web API.<br>
https://spotipy.readthedocs.io/<br>
https://developer.spotify.com/
