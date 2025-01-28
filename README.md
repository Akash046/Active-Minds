# Active Minds

**Active Minds** is an interactive chat-room-based web application designed to create a safe and engaging space for users to communicate. The application includes features such as voice chat and text messaging, with an advanced filtering system that ensures a positive environment by muting microphones and hiding messages containing vulgar or abusive language.

## Features

- **Real-time Chat:** Users can engage in text-based communication with real-time updates.
- **Voice Chat:** Enables voice communication between users in the chat room.
- **Content Filtering:** Includes an automated system to mute audio and hide inappropriate messages that contain abusive or vulgar language.
- **User Interface:** Simple and easy-to-use interface designed to facilitate communication without unnecessary distractions.

## Technologies Used

- **Frontend:**
  - ReactJS
  - Tailwind CSS
  - WebSocket for real-time communication

- **Backend:**
  - Node.js
  - Express.js

- **Database:**
  - MongoDB (for storing user data and messages)

- **Additional Tools:**
  - Socket.io (for real-time messaging and voice communication)
  
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Akash046/Active-Minds.git
   ```

2. Navigate to the project folder:
   ```bash
   cd active-minds
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the application:
   ```bash
   npm start
   ```

5. The app should now be running on **localhost:3000**.

## How It Works

- **User Authentication:** The app supports guest login for users to easily join and participate in chat rooms.
- **Voice & Text Communication:** Users can toggle between text and voice communication, enabling flexible interaction modes.
- **Content Moderation:** The system uses a filtering algorithm that detects and mutes inappropriate language in real-time, ensuring a positive user experience.

## Contributing

Feel free to contribute by opening issues or submitting pull requests. We welcome improvements and suggestions for new features!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
