# PHP Developer Test

## Background 
Demonstrate your skills using a varied range of technologies our company commonly uses. We’ll be assessing task completeness, as well as code quality. 

## Estimated Time 
3 hours 

## Skills Tested 
Primary 
- PHP (Laravel)
- jQuery
- HTML
- GIT: Commit your work to a local Git repository within your working folder as you finish logical parts of the task. Include the .git folder. Our company follows a commit early/commit often mantra.

## Tasks 
### API 
Using the provided CSV data, create an API route using Laravel that allows the data to be searched. The data should be converted to a database table. Provide Laravel migrations and seeders within the project. 

The API should search on: 
- Name: Should also match on partial names
- Bedrooms: Exact match
- Bathrooms: Exact match 
- Storeys: Exact match 
- Garages: Exact match 
- Price: Range (between $X and $Y) 

All search parameters should be optional, we should be able to search for 2 bedroom houses, or 4 bedroom and 2 bathroom houses, etc. 

The API should return JSON, with pure numeric data (not HTML content). 

### Frontend (Search Form) 
Create a simple search form that will send AJAX requests to an API and display the received results on the frontend. The search results should be dynamically rendered as an HTML table using jQuery for content updates.

Include a loading indicator, such as a spinning icon or a similar element, on the page to indicate that the search is in progress.

If no search results are found, display a message indicating the absence of results.
