# Battle_Ship_Game
Overview
The Battle Ship Game is a classic battleship game implemented in Java. The project is structured into client, server, and shared modules, allowing for a networked multiplayer experience.

Key Features
Client-Server Architecture: The game is designed to run in a client-server setup where multiple clients can connect to a server to play the game.
Graphical Interface: The client module provides a graphical interface for users to interact with the game. This includes panels for authentication, login, registration, main menu, game details, live games, and more.
Event-Driven Design: The shared module defines various events that facilitate communication between the client and server. Each event has a corresponding response to ensure smooth gameplay.
Authentication: The server module contains an authentication controller (currently commented out) that handles login and registration requests.
How to Run
Start the server by running the Main class in the server module.
Start the client by running the Main class in the client module.
Future Enhancements
Complete the authentication process by uncommenting and finalizing the authentication controller in the server module.
Add more game features and improve the graphical interface for a better user experience.
