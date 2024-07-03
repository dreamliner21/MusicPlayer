# Music Player with JavaScript

## Functionality
- **Random Song:** Plays a random song from the playlist.
- **Previous Song:** Plays the previous song in the playlist.
- **Next Song:** Plays the next song in the playlist.
- **Repeat Song:** Repeats the current song.

## Layout Design
![Music Player Layout](https://raw.githubusercontent.com/dreamliner21/MusicPlayer/master/images/bubrah.png)

## How to Use
1. Clone the repository:
    ```sh
    git clone https://github.com/dreamliner21/MusicPlayer.git
    ```
2. Navigate to the project directory:
    ```sh
    cd MusicPlayer
    ```
3. Open `index.html` in your web browser to start the music player.

## Example Code
Here is an example of how to initialize and use the music player:

```javascript
// Initialize the music player
const musicPlayer = new MusicPlayer();

// Play a random song
musicPlayer.playRandom();

// Play the previous song
musicPlayer.playPrevious();

// Play the next song
musicPlayer.playNext();

// Repeat the current song
musicPlayer.repeatCurrent();
