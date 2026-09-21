# Student Music Player

This GitHub Pages player gives every student's device a freshly randomized song order. It shows no song titles or cover art. The only controls are **Play**, **Pause**, and **Skip**.

## Publish on GitHub Pages

1. Sign in to GitHub and create a new repository.
2. Upload everything inside this folder, including the `music` folder.
3. Open the repository's **Settings**.
4. Select **Pages** in the left menu.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)`, then click **Save**.
7. GitHub will display the student link after it finishes publishing.

## Add more songs

1. Upload each additional MP3 to the `music` folder.
2. Edit `songs.js` and add the exact filename inside `window.SONG_FILES`.
3. Put a comma after every entry except the last one.

Example:

```javascript
window.SONG_FILES = [
  "First Song.mp3",
  "Second Song.mp3"
];
```

Keep the complete published site below GitHub Pages' 1 GB limit. Only publish audio you have permission to distribute. Anyone who has the public link can access the audio files.
