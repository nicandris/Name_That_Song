# Name That Song
Simple bash script for a game of Name That Song. It plays initially 3seconds of the song and you have to guess it. The 3 seconds are selected randomly from the script. 

### Menu Functions

Menu
1. Play Again (play same snippet)
2. Play More (play a longer part of the song)
3. Play Other Part (play same length but from another part of the song)
4. Show Song Info (displays the answer (Artist - Title))
5. Next (next song)
6. Create New Playlist
7. Exit

### Dependencies
* mplayer
* mp3info

### Usage

```sh
$ ./Name_That_Song
```

Specify a playlist
```sh
$ ./Name_That_Song -p playlist.m3u 
$ ./Name_That_Song -p playlist.txt
```
Create New Playlist
```sh
$ ./Name_That_Song -c <folder>
```

