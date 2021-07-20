# Launch

Interactive streaming service where pressing a launch button results in a immediate response on the live stream. Viewers can post launch suggestions and discuss the viability of these plans on the website. The launch button triggers a specific websocket message which is sent to the WebSocket server, and then broadcasted to all devices(including the pi). The raspberry pi then executes a command to run the code which performs the 'launch'.

Launch web app is a available at https://dry-badlands-58743.herokuapp.com.

### Launch Web application
Web application build using express, EJS, mongoose, and mongoDB. Produced as a final project for an online web development course. Code can be found in this repository.

### [Launch Rasberry Pi repository](https://github.com/markvangenderen/launch-pi "Launch Rasberry Pi reopository")
Client side WebSocket running on raspberry pi which executes launch immediately once launch signal is transmitted

### [Launch WebSocket Server repository](https://github.com/markvangenderen/launch-ws-server "Launch WebSocket Server")
WebSocket server which broadcasts launch signal to all clients when a launch key is received


