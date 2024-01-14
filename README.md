# API with data about the number of people in the space
## Intro
This is the eleventh project of my 30-day coding challenge. The project includes following tech stuff: HTML, CSS, JavaScript, API, LottieFiles.

## Idea
The goal was to make a page that displays an information about how many people are in space at the moment and what are the names of these people. I also used a popular library with animations called Lottie to add some movement to the web and make it visually appealing. Unfortunately after deploying the API is not being fetched, but the information from the database is shown while you code on your local port.

## Breaking down the code
To use the Lottie animation I simply attached the tag to the HTML file. I found it on <a href="https://lottiefiles.com/animations/space-tour-myQ6ir159r">Lottie page </a>. The JS code, retrieves the JSON response from the server and updates the HTML content inside an element with the ID 'astros'. The updated content includes an H1 element displaying the number of people in space and a set of paragraphs listing each person's name and their associated spacecraft. If there is an error during the data fetch, it logs an error message and updates the HTML content to inform the user about the issue, suggesting they try again later.

## Demo
Click <a href="https://fantastic-hamster-a2725c.netlify.app/"> here </a>.