# Jamming - Music Playlist Creator 🎵

Jamming is a web application that allows you to create and manage your own music playlists using your personal Spotify account. It leverages the Spotify Web API to search for tracks, add them to your playlist, and even publish the playlist to your Spotify account. This project is published using Surge through NPM.

## Screenshots
![jamming-playlist](https://github.com/ralphdaryn/jamming/assets/74474293/8f2c584f-437f-435d-8db5-0e44e82aba39)
![jamming-login](https://github.com/ralphdaryn/jamming/assets/74474293/4cb94975-c443-42fe-95cd-3f6ef6806941)

http://slippery-drain.surge.sh


## Features 🚀

- 🔍 Search and add tracks from the Spotify catalog to your playlist.
- 📁 Create a custom playlist and give it a name.
- 🚫 Remove tracks from your playlist.
- 🔒 Authenticate using your Spotify account.
- 📤 Publish your playlist to your Spotify account.

## Instructions 📝

1. Clone this repository to your local machine:

   - git clone https://github.com/your-username/jamming.git
   - cd jamming

2. Install the required dependencies:

   -npm install

3. Run the application
   -npm start
   
4. Open your browser and navigate to http://localhost:3000/

5. Log in with your Spotify account to start using Jamming.

## Tech Stack 💻
   -React
   -JavaScript (ES6)
   -HTML5
   -CSS3
   -Surge (for deployment)
   -Spotify Web API

   
## API Reference 📚
Spotify Web API 

## Lessons Learned / Next Steps 📝✨
This project was a great learning experience, and here are some lessons learned and potential future improvements:

Authentication: Implementing OAuth2 for authentication with Spotify was a key challenge. It required understanding the OAuth2 flow and handling tokens securely.

State Management: Managing the application's state, especially the playlist, can be complex. Leveraging state management libraries like Redux could simplify this.

UI/UX: Improving the user interface and experience is an ongoing process. Consider user feedback and design improvements for better usability.

Next Steps 🚀
Implement user profiles and user-specific playlists.
Add the ability to follow other users and share playlists.
Expand the search functionality with filters and recommendations.
Optimize performance and handle large playlists efficiently.
  
