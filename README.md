# SpotifySolarSystem
A simple **express application** that looks at your Spotify statistics using the **Spotify API** and generates a solar system based around them.
![App](mySystem.gif)
One running, simple log in with your Spotify account, and it will generate a simple but satisfying solar system based around your music taste.
## Setup
**The setup for this app is a little more complicated as it's designed to be accessed remotely from a server, instead of being downloaded and run locally, but if you do want to try this out for yourself, this is how you would go about it.**

First you will have to login to the [Spotify Developer Portal Dashboard](https://developer.spotify.com/dashboard/) and create a new application. 
Once setup, you will need to grab the ```Client ID``` and ```Client Secret```, and put them into the ```App.js``` file, under the appropriate variables.

Then, back on the Spotify Developer Portal you will need to make sure that your spotify account is whitelisted for your application, and add ```http://localhost:8888/callback``` onto the list of redirect URLs.

Once all everything to do with the Spotify API is setup, you should be able to go into 

```./web-api-auth-examples-master/authorization_code```

and run the command 

```node App.js```

To start the application.
