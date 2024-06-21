Windows Desktop Application for Slidely AI. In this task, we will be replicating the functionality of Google Forms in a Windows Desktop App. We will be making both the desktop app as well as the backend. It is well equipped with a user interface for viewing and creating the form submissions and is connected to a backend server made with TypeScript and Express.js.

This repository only contains the Backend part.

This project is developed as a Windows Desktop Application using Visual Basic in Visual Studio. The application allows users to create new form submissions and view previously submitted forms. Additionally, the application features a stopwatch functionality on the form submission page.

This repository contains the backend server implementation for managing form submissions, built with Express.js and TypeScript. The server utilizes a JSON file (db.json) as a database to store form submissions locally.

Make sure that the backend server is running and accessible at http://localhost:3000.


Features:

-Ping Endpoint: /ping - A GET request endpoint that always returns true.

-Submit Endpoint: /submit - A POST request endpoint to save form submissions.

-Read Endpoint: /read - A GET request endpoint with a query parameter to retrieve form submissions by index.

-Delete Endpoint: /delete - A POST request endpoint to delete submitted forms by ID.

-Edit Endpoint: /edit - A POST request endpoint to edit submitted forms by ID.

-Search Endpoint: /search - A GET request endpoint with query parameter to search forms by email ID.


Getting Started
To get a local copy up and running, follow these steps:

Prerequisites
Node.js and npm installed on your machine.
