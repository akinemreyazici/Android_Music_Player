# Android Music Player

Android Music Player is an application that allows users to play and manage their music collection on Android devices. The app retrieves music data from a provided JSON link and stores it in Firebase Firestore for future use. It utilizes an Expandable ListView to display the music list, with the ability to expand and collapse sub-items. 

## Features

- Music playback: Enjoy playing your music collection directly within the app.
- JSON data parsing: On the first launch, the app parses JSON data from a provided link and converts it into music objects.
- Firebase Firestore integration: Music data is stored and retrieved from Firebase Firestore.
- Expandable ListView: The music list is displayed using an Expandable ListView, allowing for expandable and collapsible sub-items.
- Music detail page: Tap on a music item to access a detail page where you can control playback using a MediaPlayer and SeekBar, adjust the volume, and add the music to favorites.
- Volume control: The app saves and restores the volume level using SharedPreferences, ensuring a consistent listening experience.
- Favorites list: Add your favorite songs to a separate list, view them, and remove songs from the favorites list.


## Usage

1. On the first launch of the app, the music data is fetched from the provided JSON link and stored in Firebase Firestore.
2. Subsequent launches retrieve the music data from Firestore and display the list of songs.
3. Tap on a music item to navigate to the detail page, where you can control playback, adjust the volume, and add the song to favorites.
4. Access the favorites list to view and manage your favorite songs.

## Demo

### Application Images on Running

<p align="center">
  <img width="250" alt="homepage" src="https://github.com/akinemreyazici/Android_Music_Player/assets/116732291/491c9c93-2361-425d-b91f-9961530b000f">
  <img width="250" alt="songpage" src="https://github.com/akinemreyazici/Android_Music_Player/assets/116732291/6c48e0a5-b517-4b21-939f-ffd263b8faf2">
  <img width="250" alt="favourites" src="https://github.com/akinemreyazici/Android_Music_Player/assets/116732291/74adf068-2a42-44a2-8b91-65ac78b13855">
</p>

### Project Realization 

<p align="center">
 
<img width="375" alt="project" src="https://github.com/akinemreyazici/Android_Music_Player/assets/116732291/ba4c547c-95ca-4d6f-94d0-24465e726bb8">
  </p>
