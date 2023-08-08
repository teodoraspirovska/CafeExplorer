# Step 1
When users access the root URL ("/"), they are directed to the home() function.
It renders the "index.html" template, which serves as the homepage.
![homepage](https://github.com/teodoraspirovska/CafeExplorer/assets/133661233/99f494fe-40b2-4107-92f4-2f026ae74200)
# Step 2
Users can access the "/add" URL to submit new cafe information.
This route handles both GET and POST requests.
If the form is submitted (POST request) and validates successfully, cafe data is added to a CSV file, and the user is redirected to the /cafes route.
If the request is GET (initial visit to the page), the form is rendered using the "add.html" template.
![add](https://github.com/teodoraspirovska/CafeExplorer/assets/133661233/bd116829-25d8-45ec-9e74-9509531c5274)
# Step 3
Form is submitted.
![submit](https://github.com/teodoraspirovska/CafeExplorer/assets/133661233/8e169910-4350-4d4c-b163-5533ea19fbdb)
# Step 4
When users access the "/cafes" URL, they are shown a list of cafes stored in a CSV file.
This route reads data from the CSV file and renders it using the "cafes.html" template.
![cafes](https://github.com/teodoraspirovska/CafeExplorer/assets/133661233/3225d0c2-70c2-43e0-abb9-1c1e7402226a)

# CafeExplorer
This project is a Flask web application for users to submit and view cafe details, including name, location, opening and closing times, along with ratings for coffee quality, WiFi strength, and power socket availability.
# What I have learned
I embarked on a web development journey using Flask, a Python micro web framework, to create a platform for users to submit and explore cafe details. I integrated Flask-WTF for handling forms, employed Flask-Bootstrap for styling, and managed data storage and retrieval through CSV files. This experience deepened my proficiency in Flask, honed my form validation and rendering skills, and familiarized me with data manipulation using CSV files in a web context, ultimately enhancing my Python programming skills and introducing me to web development technologies like Jinja templating and Bootstrap styling.
