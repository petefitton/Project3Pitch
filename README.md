# Project 3 Pitch

## Fork & Clone this repo.

Review the [Project 3 requirements](https://tmdarneille.gitbook.io/sei-ga-sea/11-projects/project-3#project-feedback-evaluation) and check out some [examples](https://tmdarneille.gitbook.io/sei-ga-sea/11-projects/past-projects/project3).

Provide information in the following sections:



Group Norms:
-Shane is our gitmaster
	Shane and Levin are in the same timezone. Elaine is two hours ahead, she’ll make any meeting time work but just note being understanding if things get a bit late.



-------------------------------------
-Levin
	I am not that comfortable in the back end but I would love to tackle more back end stuff for me to get more good at and also I’m not saying that I am good in the front end haha.
-------------------------------------
-shane 
	Not 100% confident in my ability to do back end work, but I’m happy to learn what i need to for us be successful.

Brainstorm:
Topics:

From Elaine: 
Flood preparation app. 
A user can create an account to log in. A user can create and save a route(https://developers.google.com/maps/documentation/directions/overview). The route will identify if a low water crossing is on the route (https://data.austintexas.gov/dataset/ATX-Low-Water-Crossings-Filtered/nin4-cdmn). The app will also have a profile page with current low water status (https://www.atxfloods.com/closures). If road is closed, tips on flood safety.



From Levin:

From Shane
:
-Auction or marketplace  app.

-Application to track hiking trails with info about trail... Might be a stretch or conceptually short of expectation.
Hiking project data api. 


Routes needed.

Stretch goals:
-cross googlemaps api to trails
-ranked difficulty
-add comments to trails
-stretch goal for recommendations(
Recommendation
	This userid
	That userid
	The trailid)



Project Overview:
Our application will be a hiking app, providing a user with an opportunity to organize their hiking options. 

Models
-User
-Index

Schemas
User
	Name
	Email
	Password
	Location
	Radius from trail
	Nickname (optional)
{Favorite_trails
		API ID}
Trails
	Id
	TrailName
	Location
	API ID

User Stories

A user can log in and create an account, they will add to their account a location and a radius from that location to return trails.
-create user,
-return user 
-update location and/or radius
-delete nickname
	
Then the user can see trails for their parameters utilizing our api.
A user can select a trail to view details. On this page they can “fave”.
Favoriting the document will create a reference in the user’s account.
	-”create”: with adding a favorite.
	-”read”:  view all favorites?
	-”update”: search location
	-”delete”: remove a favorite
A user can save trails to their account.
The user can see their favorite trails on their profile.

Wireframes
Link to wireframes on LucidCharts
https://app.lucidchart.com/invitations/accept/b1a20860-f2df-4680-ac87-85809450adae


Additional Technologies
TrailAPI, possibly GoogleMaps API, MERN auth

Work Allocation
	Gitmaster - Shane
	Scrum Master - Elaine
	Backend Engineer - Levin


Daily Sprints

Friday: 
Elaine: test API, figure out key calls and values
Shane: Set up master git, check our branches
Levin: set up user schema in mern auth

Saturday:
Everyone: review code, identify pain points/sections that need help/general scrum!

Produce: testable routes in postman for api, user, and consolidate to master?

Sunday:
Day off, any checkins/time to meet with TAs.
Produce: standard language for our different data and calls to integrate branches.

Monday:
