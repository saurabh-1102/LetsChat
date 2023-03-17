

# LetsChat
  This application is built using Socket.io and ReactJs.
  
  ![s2](WebsiteDemo.png)

# Features
  <li>Mutliple users can join and chat in a room.</li> 
  <li>Real-time communication between a client and a server using Socket.io.</li>
  <li>You can send emoticons , features like scroll to bottom button and auto scroll on receiving a message are provided     using ReactJs.</li> 
   
# Installation

### Running Locally

Make sure you have Node.js and npm install.

  1. Clone or Download the repository 
    <pre>git clone https://github.com/saurabh-1102/LetsChat.git
  2. Install Dependencies and run server
      <pre>$cd server       
     $npm install
     $npm start</pre>
  3. Install Dependencies and Start the Application 
      <pre>$cd client       
     $npm install
     $npm start</pre>
     
  Application runs on localhost:3000.
      
## How It Works

   Having an active connection opened between the client and the server so client can send and receive data. This allows real-time communication using TCP sockets. This is made possible by Socket.io.

   The client starts by connecting to the server through a socket(maybe also assigned to a specific namespace). Once connections is successful, client and server can emit and listen to events. 
   
   If multiple users try to join in the same room with same username,the user who joins first would be in and others would not be able to send or receive message in that room.
   
   
   
    
  
  


