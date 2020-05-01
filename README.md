# budget_tracker
![Picture of budget tracker app](Screenshot(40).png)
## Description
This budget tracker application allows user to add expenses and deposits to their budget with or without an internet connection. When entering transactions offline, it should populate the total when brought back online. The app stores database when offline in INDEXEDDB, updates database when brought back online. User can install this application on their local device to use when offline or online.
##### Offline Functionality:
* Enter deposits offline
* Enter expenses offline
##### When brought back online:
* Offline entries should be added to tracker.
## Business Context
Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.
## Technologies
It's a node application built with express, morgan, mongoose and compression packages. It's deployed on Heroku with mLab database.
