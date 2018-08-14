# theBackstage

-	Project Name
The Backstage (provisional)
-	Description
The Backstage is a small fórum site that Works with the Songkick API to find musical events nearby filtered by your preferences, You can check them, join and interact with other users that wish to attend too.
-	User Stories
o	Error handler 
o	Homepage : Login and signup 
o	Signup: créate a new username and password 
o	Login: Login using alrady existing username and password 
o	Profile: edit and check my profile info, also fill the remaining fields needed (such as music preferences, location …) 
o	Main page: see list of events  pre-filtered (using profile info) by location, genre, artist and date
o	Event page: Full information of the event; Option to join and add it to your calendar and/or to comment on the event’s Wall to interact with other users 
o	Calendar : check all the events that I joined 
-	Backlog
o	Upload profile picture
o	See other profiles 
o	See map of the event 
o	Search bar on the events page allowing me to filter them by special parameters 
o	Dynamic calendar 
o	Get preferences by Facebook login 

-	ROUTES
o	get/ 
o	get/login
o	post/login (Body: username, password) 
o	get/signup
o	post/signup (Body: username, password)
o	get/profile
o	post/profile (Body: Name, surname, age, description, list of favourite genres, location)
o	get/main 
o	get/event/:id
o	post/event/:id/join (Body: nothing) 

-	MODELS
User: 
o	Username: String 
o	Password: Strting
o	Name: String
o	Surname: String
o	Age: Number
o	Description: String
o	Genres: Array list of strings
o	Location: String
o	Joined Events : Array list of id’s
Events: 
o	Name: String
o	Description : String 
o	Date: date
o	Location: String 
o	Genre : Array list of strings 
o	Users attending : array list of id’s

-	Links
o	Trello: https://trello.com/b/vDpAnHdN/the-backstage
o	Git: https://github.com/sasrous/theBackstage
o	Slides.com
