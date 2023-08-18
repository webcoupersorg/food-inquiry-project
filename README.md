# food-inquiry-project

#### PROJECT FOR FRONTEND AND FULL-STACK DEVELOPERS: BUILD A FOOD INQUIRY WEB APPLICATION

A client, Miss Ore, wants a food project done for her business portfolio. She doesn’t mind a rough implementation - She just needs her users to look up any recipe on your web application. As a nutritionist, she wants the calorie count for the corresponding recipe.

Also, she proposed a cost calculator for each looked-up recipe; she's okay if it is some random amount. Although, she is keen on having this cost (in naira) converted to USD, that reflects on the live conversion rate at any given time. Ore insisted this conversion be displayed as a popup with a click of a button. Fred is our UI/UX guy - he proposed you have a button alongside the cost (in naira) with a description "Click to see USD price" for this popup.

Additionally, she wants a dedicated page where her users can look up restaurants near them, using the current location.

**FRIENDLY NOTE**: Fred just started his UI/UX journey. He's not as good as he would like, but we think he's alright. We like Fred.

**Side note**: *Ore is a big fan of Animation, especially Lotties! She also likes Card styling, Grid styling, and the color Purple.*


##### FULL-STACK DEVELOPERS

In addition to the above, You should have this project running on a backend framework of your choice (Django, express.js, Laravel, CakePHP, Nextjs, WordPress, etc), as long as it is Python, javascript, php inspired. Also, for data collection reasons, store every search query in a database with at least two tables: one for recipes and the other for restaurants.

You should implement an authentication system that allows User registration, User login, logout, and User deactivation.

You should have these endpoints:
   */users - to view all registered users*
   
   */users/<str: mary> - to view a particular user*
   
   */profile- to view authenticated user's profile*
   
   */recipes - to view all searched users*
   
   */restaurants - to view all searched restaurants*






**GENERAL NOTE** 

-	Push the code to your personal cloud-based Git repository (Gitlab, Github, etc)
-	Deploy your web application on a FREE cloud platform (Vercel, Heroku, etc)  and include the full address in your repository READme
-	Send your repository link for the project to careers@webcoupers.com (Cc: emmanuelo@webcoupers.com).
-	And hey, try to go nuts to impress Ore.


We expect you to use API(s)/services that are free to use.



DEADLINE FOR FRONTEND DEVELOPERS: 16th of August, 2023. 11:59 PM ⏰
DEADLINE FOR FULL-STACK DEVELOPERS: 18th of August, 2023. 11:59 PM ⏰



FAQ
----
- _Can Miss Ore have a dashboard where she can upload recipe?_ She wouldn't mind.
- _Are the recipes limited to Nigerian meals?_ If you want that, okay. However, you can easily utilize at least one RECIPE APIs. (only use the free version(s), please)
search query will be coming from the frontend (you are implementing this as well), so whenever a user makes a search query, collect the input and save to the Recipe table. In order to make everything simple, create two views (one for recipe, one for restaurant), and store corresponding searches.
- _So to be clear, I'm to create an endpoint to create the recipe and restaurant the do a search functionality. Or enable a search for this endpoint connected to external APIs?_ search query will be coming from the frontend - input field - (you are implementing this as well), so whenever a user makes a search query using this field, collect the input and save to the Recipe table. In order to make everything simple, create two views (one for recipe, the other for restaurant), and store corresponding searches. App flow: user registers -> user logs in -> landing page -> recipe page/restaurant page. Store search input in any of these pages.\
When a user searches for a recipe on the recipe page (collect that search input and store it in the Recipe table), then continue with the flow of hitting an external API to return the searched recipe. Same as Restaurant.


You can occassionally check this repository for responses to other recruits' questions.
