# cmdmp3
Lightweight command-line MP3 players for Windows written in C 

I've had to rebuild these files since their initial release.  Please see the blog post at:

https://lawlessguy.wordpress.com/2015/06/27/update-to-a-command-line-mp3-player-for-windows/

# Usage
```
gcc cmdmp3.c -lwinmm -o cmdmp3.exe
 
gcc cmdmp3win.c -lwinmm -mwindows -o cmdmp3win.exe
```
