# synched
================================
    Initialize the project
================================
    A. Server startup
        1. cd server/
        2. npm install
        3. npm start, Don't close the terminal
    B. Client startup
        1. On a new terminal type cd client/
        2. npm install
        3. npm start
================================
    Important files in server/
================================
        1. index.js => inits the server for the project
        2. route.js => defines the get method for the root entrypoint
        3. users.js => defines the methods for user accions with the app
================================
    Important files in client/
================================
        A. public/ Contains static files
             => index.html: React generated HTML boilerplate for the ReactDOM librarie.
        B. src/
             => components/ Folder with all components in the app
                            =>Chat/Chat.js: Component for all the Chat logic
                            =>InfoBar/InfoBar.js: Component for the status and name of the room
                            =>Input/Input.js: Component for the input handling within the chat
                            =>Join/Join.js: Component for name and room creation
                            =>Messages
                                =>Messages.js: Component for the integration logic of several Message.js components
                                =>Message/Message.js Component for the message creation logic per person/room
                            =>Player/Player.js: Component for the video playback logic
        C. icons/ I not explaining this dude
        D. App.js: Contains the display logic of every component and declares the ReactRouter workflow
        E. index.js: A basic ReactDOM declaration for DOM interpretation in index.html