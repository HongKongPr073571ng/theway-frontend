# theway-frontend
The web page front end for the way real time location view &amp; replay after the event

## UI
A map with dots represent users, implement using leaflet.js

## Polling
Using Firebase SDK as we are running out of time to implement back end

## backend
Firebase

### Auth
Firebase Anonymous authentication

## Things can be improved
- [ ] Push data to NoSQL collection "chain" (record the location history) need to test & debug  
Optimize the map view web page (Bandwidth wasted):
  - [ ] Firebase realtime database transfer old data the client already have with database().ref().on()
  - [ ] Request all data every time, but only the location data within the view port is used.
- [ ] The rule for Firebase database can be enhanced
