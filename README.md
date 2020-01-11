# (Under Construction!)
## Spring Boot - H2 Console
* **Objective** - To interface with an in-memory H2 database via Spring's built-in h2-console-servlet.
* **Purpose** - To gain familiarity with communicating to a database.

### Part 1 - Clone the project
* Begin by _forking_ this project into a personal repository.
   * To do this, click the `Fork` button located at the top right of this page.
* Navigate to **your github profile** to find the _newly forked repository_.
* Clone the repository from **your accogit unt** into your `~/dev` directory.
* Open the newly cloned project in a code editor (IntelliJ, for example).




### Part 2 - Testing via Postman
* To view the Database via the H2 Console, navigate to `http://localhost:8080/h2`
* Launch the [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en) app and enter the URI `http://localhost:8080/employees` and hit Send.
* If your application cannot run because something is occupying a port, use this command with the respective port number specified:
	* ``kill -kill `lsof -t -i tcp:8080` ``