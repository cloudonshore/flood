flood
=====

soundcloud network explorer

tasks:
1. learn to set up components in backbone.js
2. use the api explorer to figure out the data that can be returned from different endpoints, use that to decide filtering criteria.
  -filter by duration
  -sort by fav count
3.  Also user should be able to change settings on how long the chain of followers is, and how many favs to include from each user.
4.  Buttons for stream recreation would also be interesting. Clicking on an artist and creating a flood based on them,or removing their favs from the feed.
5.  All information could be stored in the url. The artist name followed by a string of characters like a6d7s8^7, the url is decyphered into all the settings. (try to find a framework for this you can utilize).
6.  It seems the application will have two main sections. One search/filtering section, and then the playlist section below. The search/filtering section should include a graph visualizer using D3.js. 
  - should the page re-render everytime a change is made? They can change the settings. The graph will spin and regenerate if it is open, and a 'flood' button can be clicked to change the flood steam. The button click also updates the url.
  - There it would be nice to be able to sort the data though without 'reflooding'. I think visually you would need to seperate functions that can be done without reload, and those requiring reload. 
7.  Log in is optional. But if you do it should have a way to remember your previous floods. 
8.  I guess the next step is to decide components and component layout. 
