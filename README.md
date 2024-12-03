# Music Streaming Application

## Description
This project is a comprehensive **music streaming application** that emulates Spotify’s core features and functionalities. It provides a seamless user experience with features like user authentication, file/image uploads, audio playback, and a system for favoriting and repeating songs. The application is optimized for performance and search engine visibility.

The project was built using **Next.js**, **React**, **Tailwind CSS**, **Supabase**, and **PostgreSQL**, with a focus on scalability and user interaction.

## Features
- **Dynamic User Interface**: Responsive and user-friendly design for all devices.
- **File and Image Upload**: Supports all image formats for playlist covers and **MP3** files for audio playback.
- **Music Playback**: Includes features like play, pause, repeat, and a system for favoriting songs.
- **Liked Songs System**: Users can favorite songs, with preferences synced to the database.
- **User Authentication**: Secure login and sign-up functionality.
- **Error Handling**: Robust server-side error handling to ensure seamless user experience.
- **SEO Optimization**: Built with Next.js to improve search engine visibility.

## Deployment
The project is deployed on Vercel and can be accessed here: [Live Link](https://spotify-clone-surya-sunkari.vercel.app/)

## Technologies Used
- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Supabase, PostgreSQL
- **Audio Playback**: HTML5 Audio API
- **Hosting**: Vercel

## Media Support
- **Playlist Cover Images**: Supports all image formats.
- **Audio Files**: Supports **MP3** format for song playback.

## Challenges and Solutions
- **Challenge**: Ensuring seamless playback and synchronization across user sessions.
  - **Solution**: Integrated Supabase to manage and sync playback states, liked songs, and user data efficiently.
- **Challenge**: Implementing a dynamic and responsive UI for various screen sizes.
  - **Solution**: Used Tailwind CSS to create a fully responsive layout optimized for both desktop and mobile users.

## Future Improvements
- Add playlist creation and sharing functionality.
- Implement shuffle and queue management features.
- Support for additional audio formats like AAC and FLAC.
