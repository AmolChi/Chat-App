# Chat-App
It is a fully functional chat application on localhost:3000, uses ReactJS, Express, MongoDB and Socket.io. Other than that uses APIs such as dicebear for random image generation

For using this application, first start the server. For the server you must have MongoDBCompass installed on your system and the port of MongoDB should 27017 and if the port of MongoDB is different please change it in the .env file present in the server folder
 
 Start the server using the command npm start or yarn start while in the server folder

After starting the server in a new terminal open the public folder and start it by Yarn start. Then on http://localhost:3000, a react app will be published showing the login page
Now if you have an existing user then use the ID Password to log in or create a new user using the register icon
Further on this Application uses dicebear API to generate avatars for a newly added user based on an input dialog box. This avatar is associated with the user and stored in the MongoDB database Users
Further on this also features emoji icons from React-Emoji library. The live telecast of message is done through Socket.io if both the users are online else the message is saved in the messages database in MongoDB and whenever the user logs in the messages are shown in his chat


New Developments could be:
  1. Newest chat pop up on the top with how many new messages showing
  2. Sharing of video/audio/text files in the chat
  3. Features such as audio/video call functionality
  4. Deploying the app on a server
