# social-media-app

# Guidelines

![Alt text](assets/guide-index.jpg?raw=true "Home page of the application")

The CSS and HTML files are provided in this repo, you could use it to create the app

You should be creating this application in narwal/nx workspace.

Styles sheet has to be written with SASS.

Features you would be implementing are below, 

Note: Refer the diagram above for understanding the below features.

The contacts and search should be a re-usable component / shared component.

The application list on the left hand side should be a re-usable component
The header should be a re-usable component.

When user clicks on application like messenger, market place etc, it should load respective modules on the application container section, refer the diagram to understand what is application container section.

Navigation between apps should change the route like
http://localhost:4200/social-media -> Home
http://localhost:4200/messenger -> Messenger app module loaded
http://localhost:4200/market-place -> merket place app module loaded
and so on ... (Using angular feature Routing)

I should be able to search the contacts in contacts component.

When messenger application in loaded in application container after clicking messenger link in home page, we should reuse the contacts component on the left side sectiion.

![Alt text](assets/guide-messenger.jpg?raw=true "When messenger module is loaded")

For remaining applications, just load a place holder module, saying “market places is loaded” and so on....

The contacts and application names and its Urls should come from backend service.

for e.g. http://localhost:8080/api/apps
http://localhost:8080/api/contacts

load all post for the user in the center section of socisl media app from api http://localhost:8080/api/posts [GET]

Adding a post should persist the post to the backend with an API call.

for e.g. http://localhost:8080/api/posts [POST]

The application state should be managed with NgRx.

Split the components diligently.

Note: I know that we have not covered the unit testing and localstorage, we are planing to have a seperate session for that, you may do extend your POC with those knwoledge once we covered those topics at later state.

Note: Get back to me in teams in case of any questions
