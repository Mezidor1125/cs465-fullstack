### CS465 Full STack Development - MEAN

## Architecture

# Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

During the the full stack project development, there were a few different types of front end code that were used in different parts of the application.  The customer facing site was developed originally in Express HTML and then converted over to a .hbs view to help with rendering speeds by not having to fully load every component of the site at each refresh.  HTML is static and client facing, which means it can;t interact with backend databases to dynamically update information.  Javascript is a frontend and backend coding language that is used to add dynamic elements to the webpage.  This was used to pull trip information from the MongoDB database so that the page can change dynamically based on user interaction.  A single-page application is a website that doesn't fully refresh the page based on user interactions like an HTML page would.  This is particularlly useful in giving the website a local/native application feel when interacting with the applicaiton itself. 

# Why did the backend use a NoSQL MongoDB database?

The backend used a NoSQL MongoDB database because of its ease of modifying schema based on scaling and functionality changes, as well as the ability to rapidly scale horizontally because of its non-relational nature of the database.

## Functionality

# How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JSON is a standardized way to format object data that can be easily read by Javascript to form it into a literal Javascript object.  This makes it easy for Javascript to take the data and form it into a object in the Javascript language.  This ties frontend and backend development together by creating a way for data/ Javascript objects to be stored on the backend and used in different situations based on what the frontend is requesting the data for. This also means that the data just has to be stored once but can be pulled and used in a variety of ways.

# Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.



## Testing

# Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security.



# Explain your understanding of methods, endpoints, and security in a full stack application.

## Reflection

# How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
