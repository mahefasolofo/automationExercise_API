# automationExercise_API

API test project in https://automationexercise.com/api_list via Postman

## Getting started
- clone the project into your local repository
- go to Postman
- on the left of the My Workspace side bar click on Import.
- Choose the file "AutomationExercise API.postman_collection.json" 
- Import


To run test manualy open GIT Bash : 
install newman:
> npm install newman

Export the Collection projet and the environment project : Local.

Run the command :
>  newman run AutomationExercise\ API.postman_collection.json -e Local.postman_environment.json
