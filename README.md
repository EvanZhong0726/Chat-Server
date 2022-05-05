--------
#### Functionalities:
- User can leave the chat room
- Owner can disband the chat room
- Owner can transfer ownership

#### User-centered design:
- Username is unique across all rooms
- Roomname is unique
- Owner cannot kick himself out
- Owner cannot leave the room, disabled button 
- A scrollable chat log panel

Need to install node.js for the program to run

      $ curl --silent --location https://rpm.nodesource.com/setup_12.x | sudo bash -
      $ sudo yum install -y nodejs
      
      
      
      
      
And then clone the repository, go inside the repository and run:
     
       node chat-server.js
       
Then go to localhost:3456 in your browser, you should be able to see the chat-server
