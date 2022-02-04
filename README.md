# Posts-Comments-Microservices

Start each node project separately
npm start

visit the site
http://localhost:3000/

Post and Comment service will write to event-bus

Event=bus will send the events to Post/Comment/Query/Moderation

Moderation will check every comment for a word

Query will fetch the data to display
