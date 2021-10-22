![image](https://user-images.githubusercontent.com/92478365/138358383-120b04b1-77ce-4380-9a05-3bf2c15bf4eb.png)

### Todoist is the simple yet powerful to-do list app that will help organize life and work.

# Automated Solution

- Tech Stack:
	- NPM
	- TestCafe
	- Eslint
	- TestCafe Reporter 


- Programing language:
	- JavaScript
	
	
- Pre-requisites:
	- An IDE installed  (Recommended: Visual studio code) 
	- Clone the repository : https://github.com/Alexahls/TodoistAutomatedSolution
	- NPM installed
	
	
- Install in the project terminal:
	- TestCafe : `npm install testcafe`
	- Reporter: `npm install testcafe-reporter-html`
	- Casual: `npm install casual`


- Solution Structure:

	pageObjectModel
	├── data
	│   ├── Constrains.js
	│   └── Roles.js
	├── pages
	│   ├── InboxPage.js
	│   ├── LoginPage.js
	│   ├── SideBarPage.js
	│   └── TodayPage.js
	└── tests
	    ├── LoginTest.js
	    ├── ProjectCreationTest.js
	    └── TaskCreationTest.js	    
	    	    
	    
    - pageObjectModel:
        -data : the common data used by several test and methods is saved in these files.
        -pages :  page elements are declared and used to perform actions 
        -test :  assertions are created to validate the actions performed in the pages
    - Reporter : here the logs are saved (open it in any browser)


- Create .env file:
	(In order to run the scripts the .env file must be created, there the login information will be located)
	- In the main folder add one new file using the following name: `.env`
	- Add the following information in the file :
		- STANDARD_USER_EMAIL = myemail@email.com
		- STANDARD_USER_PASSWORD = password
	- Save the file
	

- Execute scripts by copy & paste the followin code into the terminal:
	- Smoke test: `npm run smoketest`
        - Login in two browsers headless:`npm run testlogin2browsersheadlessmode`
        - Full regression (all the thest cases in this solution):`npm run fullregression`

        
  

