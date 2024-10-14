# VIdeo-Chat-using-WebRTC
This is an web application which can be used for video call purposes it uses WebRTC to communicate between users and a custom server to connect both users.

The server uses ICE candidates (Free STUN servers from google ) which are used to know the path for communication between the users the application also uses Socket.io which has a main functionality of connecting the users by exchanging the ICE candidates and required codec data 