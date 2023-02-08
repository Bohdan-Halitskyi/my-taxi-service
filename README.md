# my-taxi-service
Simple taxi service web app. Built with J2EE
## Intro
Manage your cars and drivers, get and provide info about cars manufacturers and more upcoming features. Built with J2EE, will be deployed on Heroku soon.
## Features
- View your cars as a driver
- View all registered drivers names and licenses
- Add, remove and update drivers info
- Cars management and drivers assignments
- Additional car info such as manufacturer and country of origin
## Structure
Servlets linked to 3-layer DAO services for each scoped object, covered by a filter to protect data from unauthorised access
## Startup instructions
Use init_db script to initialise project required db at your server, configure connection util constants to match your links and server user credentials and deploy it on your servlet container
## Feedback
You can contact me with adding a comment to report an issue, add some suggestions, etc.