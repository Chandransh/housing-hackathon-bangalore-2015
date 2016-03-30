# Housing.com Hackathon (Bangalore-2015)

Created basic pages for finding the lands/properties nearby during the 24 hours hackathon organised by Housing.com in April 2015. The idea was to provide a location based search where the results will be displayed inside a map similar to google maps, similar to what current UI of Housing.com is. The search criteria and options were intelligently selected where neighbours' ratings and ethinicity of the location were also taken into conideration. The code and functionality are incomplete. However, doing a bit hacking with the code will do the basic job (our team of 4 did the same during the presentation).

Here is the final application we submitted for better understanding what we intended to create:

##Team: WhiteWalkers
###Members
1.	Broto Bhattacharjee 
2.	Chandransh Srivastava
3.	Pradeep
4.	Viral Shah

###Problem 
Help a person discover interesting localities (Statement 2/3).

###Solution	
A web app with feature rich UI that allows users to get preferential details about the land he is interested in. The idea is to provide as relevant results as possible related to user’s cultural taste, ethnicity, and locality preferences and of course the budget. The app relies on the extensive research data about the land and its surrounding by the data collectors. Once a user comes to the home page of the app (no login is required for users), the app detects the location of the user and suggests about nearby lands under ‘Lands Near You’ heading. The sidebar asks the list of basic inputs such as city, locality, area and budget from the user to funnel out the results. There is also an ‘Advanced Search’ button which if clicked, further asks more inputs from the user for population density and population type. More options listed under future scope. After entering all or few preferences, a user has to click on the ‘Look Up’ button. The results are then plotted on the map. Google maps API is used for the same. The user now can click on any balloon icon (location icon) to get all the details about the land. The details will help users to get information about the following:

1.	High quality images of the land and locality. If possible, aerial view is also suggested.
2.	A short video of the land and its surroundings
3.	Population density
4.	Population ethnicity percentage
5.	Estimated value of the land after certain time periods
6.	Sanitary conditions
7.	Proximity to amenities
8.	Status of locality

###Technology Stack
The following technologies are used to design the app:

1.	HTML5- To design the layout of the web app
2.	CSS3- To stylise the web app’s layout
3.	jQuery- To put click functionalities and behaviour on various HTML elements
4.	Java- To write the program logic and fetch data from database
5.	Java Servlet- To compute business logic
6.	MySQL- To maintain the database

###Design and Architecture

![Design](https://raw.githubusercontent.com/Chandransh/housing-hackathon-bangalore-2015/master/WebContent/images/architecture.png)

Process is as shown below:

![Process](https://raw.githubusercontent.com/Chandransh/housing-hackathon-bangalore-2015/master/WebContent/images/process.png)

###Issues and Unfinished Works

1.	Code failing to fetch the location data from map due to servlet issue
2.	Incomplete UI due to lack of time
3.	Detection of user’s location is not implemented

###Future Scope
Given more time and resources at our disposal, the app can be extended to include the following:

1.	Take inputs from the existing customers and show the ratings on the web page. The better approach that we suggest is to survey the neighbours and get the ratings from them.
2.	Data mining from different social networking sites.
3.	Filter and sort options in the main page for ‘Lands near You’.
4.	Enhancing the accuracy of the map results.
5.	Including more input options in ‘Advance Search’ modal window such as sanitary conditions, water logging issues and proximity to vegetable vendors.
6.	Admin UI (Data Collectors).
7.	Admin can customize ‘Advance Search’ features region wise.
8.	User dashboard and login options to save the search preferences (which can be used as auto completed fields when user is searching about any new land). Also, a logged in user will be capable of saving certain lands to his wish list.
9.	More input options under ‘Advance Search’ such as ‘Land Value Estimation’ and ‘Sanitary Conditions’.

###Steps to Use the App
The app is simple and easy to use.

1.	Run the Apache server.
2.	Go to http://localhost:8080 from any browser. This will open the app’s homepage.
3.	Sidebar contains the search criteria. The user needs to select his preferred options such as location of land, area of land, and price of land.
4.	Click on Search button - Data from the database is fetched and displayed on Google map identified with balloon icons.
5.	Click on any of these listed icons – Details of the land like area of land, price of land, owner’s name and contact details are displayed on a pop-up.
6.	User can modify the fields in the sidebar to get new results.
7.	Click the “Advanced Search” button.
8.	Select Population Density and Majority of Religion (More options listed in the future scope) and hit “Look Up More” to search.
9.	The details provided in the Advanced Search criteria are now included while doing a search on the database and are displayed with the results on a map. A user can click and view the land details in a pop up (modal window). He can also navigate through other listings from the same modal window.
10.	 If in case the search results in “0 matches”, the broker’s name and contact details are provided.

###Thank You!

