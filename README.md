tunnelMe-HowTo
==============

Create a public url for a static site from localhost


How to
======
 1. Install nodeJS http://nodejs.org/
 2. Install https://localtunnel.me/
      
 npm install -g localtunnel
 2. Dowload repo and inside 'view' folder put your static site. Be aware that in view folder
    must be present a 'index.html' file
 3. Start node app
      
node app.js
 4. Check http://localhost:8080/      
 5. In a new tab of terminal run:
      lt --port 8080
      
    How you will have a public url !!
