Description: 

Java Application for for ChatRoom having following functionalities:

- Video Calling
- Messaging
- P2P File Sharing
- Desktop sharing (Bug in case of Multiple users in Chatroom behind NAT)
- WhiteBoard
- Individual User Recording on KMS server

Pre-requisites:

- Mvn
- Jdk 7
- kms server 6.6.0
- Ubuntu 14.04 not 16
- Nodejs >= 4.x
- KMS on https 
- Frontend code 

TODO:

- Clone the Repo into machine,
- go to root user via 'sudo su',
- go to '/kurento-room-demo/' directory after cloning,
- clean previous compiled code via 'mvn clean'
- compile and run the code via: 'mvn compile exec:java &'
- all done with setup
- can check the compiled on target folder

Setting and Other locations: 

- setting resides in '/kurento-room-demo/src/main/resources/application.properties'
- Kms settings resides in '/kurento-room-demo/src/main/resources/kurento-room-demo.conf.json'
- Angular code,css, images and other static files resides in '/kurento-room-demo/src/main/resources/static/'


Current Status:

- Configured and Running on KazaRoomServer