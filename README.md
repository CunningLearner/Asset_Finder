# Telepresence Robot
### A robot controlled via voice to roam around following actions uttered via the user in the vicinity of Google Home, an AI engine. User experience is made available to a remote area using webRTC, i.e the Telepresence Bot can be controlled as well as monitored from any remote corner around the globe.

# Deploy to:
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

# What does the service do?
It's a simple echo service that takes `resolvedQuery` and `action` fields from the dialogflow.com JSON reponse and echoes them back in into `speech` and `displayTest` fields in the fulfillment JSON.
