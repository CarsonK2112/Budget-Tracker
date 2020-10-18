# Budget Tracker App

With this application I have attempted to create functionality to the pre-existing budget tracker allowing it to function offline. 

A manifest.json, db.js, and service-worker.js files were added to the app to provide functionality in offline mode. The service worker performs the bulk of the offline serviceability. The db.js (database) creates a virtual database which can store the offline data.

Be sure to run npm start to begin the application and check localhost:3000

Unfortunately I have run into deployment problems that I no longer have time to fix. Utilizing the command heroku logs --tail will reveal the issues, and unfortunately I cannot make heads or tails of it. 