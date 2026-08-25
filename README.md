# Android MP3 Player using Service

## Aim

Create an Android MP3 Player application by using a **Service** and `MediaPlayer`.

## Description

This practical demonstrates how Android Services can be used to perform tasks in the background. An MP3 player application is created where a Service manages the playback of an audio file using the `MediaPlayer` class.

The application contains a user interface for controlling the MP3 player, while the Service is responsible for handling the music playback.

## What is a Service?

A **Service** is an Android component that can perform long-running operations in the background without providing a user interface.

For example, a Service can be used for:

- Playing music
- Downloading files
- Performing background operations
- Processing data

## Types of Service

### 1. Foreground Service

A Foreground Service performs a task that the user is actively aware of. It usually displays a notification.

Example:
- Music player
- Navigation
- Fitness tracking

### 2. Background Service

A Background Service performs operations without directly interacting with the user.

Example:
- Background data processing

### 3. Bound Service

A Bound Service allows other application components to bind to it and interact with the Service.

## Features

- MP3 music playback
- Music playback using a Service
- MediaPlayer implementation
- Audio file stored in the `raw` folder
- Custom drawable icon
- MainActivity user interface
- Background music playback

## Components Used

- MainActivity
- Service
- MediaPlayer
- ImageView
- TextView
- Button
- ConstraintLayout
- Drawable resources
- Raw resources

## MediaPlayer

`MediaPlayer` is an Android class used to play audio and video files.

In this application, `MediaPlayer` is used to:

- Create the audio player
- Start the MP3 file
- Pause the music
- Stop the music
- Release the player when it is no longer required

## Raw Folder

The `raw` folder is created inside the `res` directory.

The MP3 audio file is placed inside the `res/raw` folder so that it can be accessed from the application using its resource ID.

## Drawable Icon

A drawable icon is added to the Android project and used in the MP3 player interface.

## Working

1. The application starts with `MainActivity`.
2. The MP3 player interface is displayed.
3. The user can interact with the music controls.
4. `MainActivity` communicates with the Service.
5. The Service creates a `MediaPlayer` object.
6. The MP3 file stored in the `raw` folder is loaded.
7. `MediaPlayer` starts playing the song.
8. The Service manages the music playback.
9. When the Service is no longer required, the `MediaPlayer` is stopped and released.

## Project Structure

The main components of the project are:

- `MainActivity.kt`
- `MusicService.kt`
- `activity_main.xml`
- `AndroidManifest.xml`
- `res/raw/song.mp3`
- Drawable icon resources

## Android Concepts Studied

- Service
- Types of Service
- MediaPlayer
- Drawable resources
- Adding a Drawable Icon
- Creating a `raw` folder
- Adding an MP3 file to the `raw` folder
- Background music playback

## Conclusion

This practical demonstrates how to create a simple **MP3 Player application using an Android Service and MediaPlayer**. The Service manages the audio playback while the MP3 file is stored in the `raw` resource folder.
