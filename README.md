# PROJECT_TITLE

react-video-chat

# PROJECT_DESCRIPTION

In this project, a video calling application using react.js has been introduced that enables one to one (peer-to-peer) video calling.

# AVAILABLE_SCRIPTS

node.js, react.js, socket.io, socket-client.io, simple-peer, express.js.

# INSTALLATION

1. Open the project folder "react-video-chat".
2. Open terminal or cmd inside that folder.
3. In Windows run "npm install" || In Linux or Mac run "yarn install".
4. Go to client folder and repeat step 3 and get ready to enjoy this app.

# RUNNING_THE_PROJECT

Type "npm start" || "yarn start" in the terminal.

# DEPLOYMENT_IN_DOCKER

1. Install Docker Desktop.
2. Open terminal inside the project folder ("react-video-chat).
3. Run the command "docker build . -t react-video-chat-server-image".
4. Once it is completed, run that image using the command "docker run -d -p 5000:5000 react-video-chat-server-image".
5. Go to "client" folder and open terminal inside that folder.
6. Run the command "docker build . -t react-video-chat-client-image".
7. Once the image has been created, run that image using the command "docker run -d -p 3000:3000 react-video-chat-client-image".
8. Open browser in the link "localhost:3000".
9. Enjoy the app. 

# END