# -CS250Cannonball
Project Cannonball

Cannonball is a webpage-based application designed to help users search for and view information about local bodies of water in San Diego County, intended to provide live information via the EPA.

Current Project State

At the time of handoff, the project includes:
•	a landing page (index.html)
•	a results page (search-results.html)
•	image/logo assets in the Cannonball Assets folder
•	a working search flow between the two pages

The current version is a static HTML/CSS/JavaScript implementation.

Current Functionality

The current build allows the user to:
•	enter either a zip code or a location name on the landing page
•	navigate to the results page using that search term
•	search across the hardcoded water body dataset
•	view matching results with:
•	location
•	zip code
•	swimmability
•	drinkability
•	activities
•	source link

The search currently matches against:
•	location
•	waterbody name
•	activities
•	zip code

Data Implementation

At this stage, the water body data is hardcoded directly inside search-results.html.

This was done to ensure a stable midpoint submission and a working prototype without introducing additional file-loading or backend complexity.

Intended next steps:

The next planned improvement would be to move this hardcoded data into a dedicated JavaScript object or data file, which would make the project easier to maintain and expand.

After that, the long-term goal would be to replace or supplement static data with live API calls for up-to-date water quality information.

Long-Term Goals / Planned Features

The intended long-term direction for Cannonball includes:
•	integration with live EPA waterway data through API calls
•	replacing hardcoded data with a dedicated JS data structure 
•	an interactive map for searching and exploring waterways geographically
•	a user login system
•	a commenting/posting system so users can share updates, experiences, or warnings

Notes for the Next Team
•	The current search flow is stable and should be used as the functional baseline.
•	index.html currently handles initial input and basic zip-code validation.
•	search-results.html contains the searchable dataset and displays the results.
•	The code currently favors readability and stability over modularity.
•	Refactoring the data into a separate JS file would be a strong next step before implementing live data integration.

File Overview
•	index.html
Landing page and search entry point
•	search-results.html
Search logic, result rendering, and current hardcoded dataset
•	Cannonball Assets/
Logos, icons, and visual assets used by the pages

⸻

