# 2016秋招分流考核
Define three new classes, called **Song**, **Playlist**, and **MusicCollection**. 

A Song object will contain information about a particular song, such as its title, artist, album, and playing time. 

A Playlist object will contain the name of the playlist and a collection of songs. A MusicCollection object will contain a collection of playlists, including a special master playlist called library that contains every song in the collection. 

Define these three classes and write methods to do the following:
 
1. Create a Song object and set its information.
2. Create a Playlist object, and add songs to and remove songs from a playlist. A new song should be added to the master playlist if it’s not already there. Make sure that if a song is removed from the master playlist, it is removed from all playlists in the music collection as well.
3. Create a MusicCollection object, and add playlists to and remove playlists from the collection.
4. Search and display the information about any song, any playlist, or the entire music collection.
 
Note:
You don’t need to write a application with UI for now. A console application is OK.
This task can be finish in Swift or Objective-C.