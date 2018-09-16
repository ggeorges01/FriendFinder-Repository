# FriendFinder-Repository
This app allows user to take a survey, answering 10 questions with a 1-5 scale ranging from agree to disagree. Upon submitting the survey form, the app compare the user with survey participants to identify who is the closest match. The last user who submits the form will also be added to the existing Friend Finder database.

The matching is done by computing the smallest differences between each survey responder and accumulating these differences. Responders on the database that have the smallest difference will be considered to be the closest match.

node.js Dependencies:

express
body-parser
path

Backend modules:

server.js - sets up and starts server
apiRoutes.js - specifies routes for API services
htmlRoutes.js - specifies routes for HTML services
Friend Finder Repository
