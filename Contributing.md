# Welcome to GreenStand:
We are here to make the world a cooler, richer greener place. Think Agile Mindset. 

## Git basics
 * If you don't how to fork a repo and make a pull request you need to learn some Git Hub basics.
 * Find the repo you want to work on and look in the issues. Or check the 'boards' tab for an issue you would like. 
 
## Communications
* When in doubt ask
* Use Github issues or Slack

### Slack link 
[https://join.slack.com/t/greenstand/shared_invite/enQtMjcyMzgyMjk4NzU3LWZmNjM3YzY5N2Q0MzQ5YTM4OGZkMWJhM2U4MTkyYjI2NjhkN2YxNTRiMDIwNWQ5ZTVlNDczYzBjZmMxYzM2ZjU] 
* Threads versus replies
* Open Channels rather than Private Channels 

System flow diagram, etc. 
 
# Roadmap for TreeTracker Project

This project coordinates tree planting employment for people living in extreme poverty.

## Immediate Development Targets (Core Functionality)

### Android
+ Integrate with API

~~+ Fix GPS Location Tracking~~

+ Upload images to cloud object storage and integrate URLS with API (**Underway**)

~~+ UI Fixes and Updates~~

+ Repackage with new key
+ Implement RPC for stream upload/downloading trees

~~+ Remove remind to sync ~~

### Web
+ Design and Implement an Awesome web map background (**Underway**)
+ Switch to JSONP endpoints
+ Design location markers, etc (**Underway**)
+ Tweak for embedding in other platforms (**Underway**)
+ Stylize dialog

### API
+ Clean or Rewrite the Api (**Underway**)
+ Access control on the API
+ Create tree endpoints filtered by location or user
+ JSONP endpoints for Map

### Cloud
+ Scalable Infrastructure / Load Balancing
+ Backups
+ SSL (https)

### Dev Ops
+ Deployments
+ Automated unit testing

## Targets for February 2018 (Deployable System)

### Admin Panel
+ List and filter plants by time and planter
+ Remove tree records from list

### Embed maps in external websites
+ Filter by project / organizations
+ Filter by region
+ Filter by date

### Donor Panel 
+ Map
+ Click on trees and see something
+ A charts page


## Long Term Feature Targets  (Full System)

### Admin Panel
#### Project management
+ Create planter accounts
+ Assign planters to projects / organizations
+ Project configuration / organization whitelabel
+ Payout management for planters / collectors
#### Planting planning
+ Notify planters to check on particular trees
+ Species mixture and layout
+ Collection of forest products
+ Coordination of collection
+ Coordination of pickup

#### Tree Updates
+ Data quality / linking tree updates to correct tree using GPS

### Android
+ Money earned counter for the planter
+ Whitelabel deployments

### Link to mobile money

### Link donations to individual trees or groups of trees

### Advanced GIS features and Data Analysis

### Species recognition
