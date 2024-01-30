
Basic oauth2 example

Configure github oauth2 

	Go to:					https://github.com/settings/developers
	Add New OAuth App
	Add Home page as:		http://localhost:8080
	Add callbackURL as:		http://localhost:8080/login/oauth2/code/github
			
Run it with spring boot

	http://localhost:8080
	Authorize service with github
	 