# Music-Player-using-HTML-CSS-JS

A feature-rich and visually appealing music player built with HTML, CSS, and JavaScript. The player supports multiple songs, volume control, seeking, repeat, shuffle, and more!

## Features

- Play and pause functionality
- Next and previous track controls
- Shuffle and repeat options
- Volume control slider
- Seek slider for navigation within a track
- Dynamic gradient background
- Rotating album art
- Interactive UI with animated wave loader

## Technologies Used

- **HTML**: Structure of the application
- **CSS**: Styling and animations
- **JavaScript**: Logic and interactivity

## Project Structure

```plaintext
music-player/
├── index.html         # Main HTML file
├── style.css          # Styling for the application
├── script.js          # JavaScript functionality
├── images/            # Album art and favicon images
│   ├── stay.png
│   ├── fallingdown.jpg
│   ├── faded.png
│   └── ratherbe.jpg
├── music/             # Music files
│   ├── stay.mp3
│   ├── fallingdown.mp3
│   ├── Faded.mp3
│   └── Rather Be.mp3
└── README.md          # Project documentation
```

## How to Use

1. Clone or download the repository to your local machine.

2. Place your music files in the `music/` directory and update the `music_list` array in `script.js` to include the new tracks:

   ```javascript
   const music_list = [
       {
           img : 'images/your-image.jpg',
           name : 'Your Song Name',
           artist : 'Your Artist Name',
           music : 'music/your-song.mp3'
       },
       // Add more tracks here
   ];
   ```

3. Open `index.html` in a web browser to run the application.

## Installation

No installation is required. Simply open the `index.html` file in any modern browser.

## Future Enhancements

- Support for playlists
- Mobile-friendly responsive design
- Integration with music streaming services

## License

This project is open source and available under the [MIT License](LICENSE).

---

Enjoy your music! 🎶

![image](https://github.com/user-attachments/assets/44df8a98-b0f0-4d68-a304-4584993365e5)
