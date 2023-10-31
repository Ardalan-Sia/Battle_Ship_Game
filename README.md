# Battle Ship Game

## Overview
The Battle Ship Game is a classic battleship game implemented in Java. The project is structured into client, server, and shared modules, allowing for a networked multiplayer experience.

## Key Features
1. **Client-Server Architecture**: The game is designed to run in a client-server setup where multiple clients can connect to a server to play the game.
2. **Graphical Interface**: The client module provides a graphical interface for users to interact with the game. This includes panels for authentication, login, registration, main menu, game details, live games, and more.
3. **Event-Driven Design**: The shared module defines various events that facilitate communication between the client and server. Each event has a corresponding response to ensure smooth gameplay.
4. **Authentication**: The server module contains an authentication controller (currently commented out) that handles login and registration requests.

## How to Run
1. Start the server by running the [Main class in the server module](https://github.com/Ardalan-Sia/Battle_Ship_Game/blob/main/ap2021-network-master/server/src/main/java/ap/mini_project/server/Main.java).
2. Start the client by running the [Main class in the client module](https://github.com/Ardalan-Sia/Battle_Ship_Game/blob/main/ap2021-network-master/client/src/main/java/ap/mini_project/client/Main.java).

## Future Enhancements
- Complete the authentication process by uncommenting and finalizing the authentication controller in the server module.
- Add more game features and improve the graphical interface for a better user experience.
