# Song Lyrics Application Using Spring Boot and JavaFX

## Overview

This project consists of a server, a client GUI, and a web app for managing songs and their lyrics. Below are the instructions for running the application effectively.

## Steps to Running the Application Effectively

1. **Run the Server**: Navigate to the `project-server` folder and start the server. Ensure the server is up and running before proceeding to other parts of the project.

2. **Dependency**: Note that for all other components to function properly (client GUI and web app), the server needs to be operational.

3. **Pre-loaded Songs**: Upon server startup, 12 songs are already pre-added for testing additional functionalities in the client GUI and web app.

4. **Run the Client GUI**: Execute the client GUI by navigating to the `project-client` folder and launching the application.

5. **GUI Functionality**: Once launched, the GUI will present options for adding, deleting, and updating song lyrics.

6. **Run the Web App**: Access the web app by opening the `index.html` file located in the `project-web-app` folder. This will display the stored lyrics from the server.

7. **Shut Down Server**: After testing all functionalities, shut down the server to conclude the project run.

## How to Run Project

The project can be executed in two ways:

1. **Using an IDE**: Utilize IDEs such as Netbeans or Intellij to run the project.

2. **Terminal Command**: Run the project from the terminal using the command `gradlew bootRun` in the project's root directory. Ensure Gradle is installed on your machine for this method.

3. **Server and Client**: The above steps apply to both the server and client located in `project-server` and `project-client` respectively.

4. **Launching Web App**: Access the web app by opening the `index.html` page in a web browser from the `project-web-app` folder.

## Project Details

1. **Client GUI Instructions**:
   - To delete a song and its lyrics, select the song and click delete.
   - To update a song, double click on it to populate the text fields, make necessary changes, and then click update.
   - To add a new song, fill in the required details and click save.