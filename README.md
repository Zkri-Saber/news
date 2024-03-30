= README: Simple Express Web Server

== Introduction

This project is a basic example of an Express.js application. It demonstrates how to create a simple web server that responds to HTTP GET requests with HTML content. This is suitable for developers learning the basics of web development with Node.js and Express.

== Prerequisites

Before you begin, ensure you have installed:

* Node.js (https://nodejs.org/)
* Express.js

== Installation

To set up the project locally, follow these steps:

. Clone the repository to your local machine.
. Navigate to the project directory.
. Install the dependencies by running `npm install`.

== Running the Application

To start the server, run the following command in your terminal:

[source,bash]
----
npm start
----

Or, if you prefer to use node directly:

[source,bash]
----
node app.js
----

By default, the server listens on port 5000. You can access the application by visiting http://localhost:5000 in your web browser.

== Additional Notes

The application is configured to listen on port 5000. If you wish to use a different port, you can modify the `app.listen(5000, ...)` line in the `app.js` file to your preferred port number.

This application is designed for educational purposes and to serve as a template for more complex projects. Feel free to modify and expand upon it as needed.
