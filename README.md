# StoryShare
Crud app for wysiwyg editor with google autho2 
followed along with tutorial from Traversy Media
https://www.youtube.com/watch?v=SBvmnHTQIPY&t=5619s

if running elsewhere will require config.env file with the following:
  PORT
  MONGO_URI - connection string to db
  GOOGLE_CLIENT_ID - auth https://console.cloud.google.com/ Google+ API OAuth 2.0 
  GOOGLE_CLIENT_SECRET - auth https://console.cloud.google.com/ Google+ API OAuth 2.0 

TODO: issue with storing the session with connect-mongo currently crashes app when used so users are logged out when server restarts
