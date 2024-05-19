	Music Playlist Manager.

	Description:
The Music Playlist Manager is a software application designed to organize and manage a collection of music playlists. It provides users with functionalities to create new playlists, add songs to existing playlists, remove songs from playlists, display all playlists.It makes listening music more convenient and easier.
	
	
  	Objectives:
Efficient Playlist Management: Provide functionalities to create, update, remove, and display playlists.
Persistent Storage: Implement mechanisms to save the playlist data to a file and load it from a file, ensuring data persistence across multiple sessions.
User-Friendly Interface: Create a simple and intuitive text-based interface for users to interact with the system.
Error Handling: Handle common errors gracefully, such as attempting to update or remove a song that does not exist in a playlist.

	Data Storage:
Playlists and songs are stored using appropriate data structures to allow efficient management and retrieval.
Playlist Representation: Each playlist contains a list of songs, and playlists themselves are stored in a data structure such as a vector or map.
User Interface: A straightforward command-line interface is provided for interaction, enabling users to easily navigate through playlist management options.

Algorithms and Data Structures:
	
 	Data Structures: 
- Vector or map to store playlists, where each playlist contains a list of songs.
- Struct or class to represent song entities, containing attributes such as title, artist, album, and duration.



	Algorithms:
- Add Playlist: Creates a new playlist and adds it to the collection of playlists.
- Add Song to Playlist: Searches for the specified playlist and adds the song to its list of songs.
- Remove Song from Playlist: Locates the specified song in the playlist and removes it.
- Display Playlists: Iterates through the collection of playlists and prints each playlist's details along with its songs.

	Compilation:
1. Open a terminal or command prompt.
2. Navigate to the directory containing music_playlist_manager.cpp.
3. Compile the code using a C++ compiler, e.g., g++ -o music_playlist_manager music_playlist_manager.cpp.

	
 	Execution:

1. Run the compiled program, e.g., ./music_playlist_manager.
2. Follow the on-screen instructions to interact with the music playlist management system.
3. Ensure that playlist_data.txt exists in the same directory to load the playlist data on start. The file will also be used to save the playlist data.

	Features:
- Create Playlist: Enter the name of the new playlist to create it.
- Add Song to Playlist: Specify the playlist and provide song details (title, artist, album, duration) to add a song.
- Remove Song from Playlist: Select the playlist and enter the song details (title, artist) to remove it from the playlist.
- Display Playlists: Shows the list of all playlists along with their respective songs.
- Save Playlists to File: Saves the current state of playlists and songs to playlist_data.txt.
- Load Playlists from File: Loads the playlists and songs from playlist_data.txt if it exists, ensuring data persistence between sessions.


  	Screenshots:

  
![Снимок экрана 2024-05-17 143144](https://github.com/rosszzalina/date-structure/assets/150505816/e826bbfb-d1a5-4ef5-b62e-d61fab87f721) 



![Снимок экрана 2024-05-20 023134](https://github.com/rosszzalina/Music-Playlist-Manager/assets/150505816/637e8958-6aa8-4808-b551-8291ba7b59e3)



