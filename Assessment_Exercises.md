# PHP, PDO and Databases

## Setting up
This practical is about using PHP to work with a MySQL database. We will work with the films tables we created in the practical last week. 

## Listing all items from the database
In a text editor open list.php.

Modify the connection settings so that you use the values for your MySQL database, username and passwork. These should be:
* database: student number e.g. u1234567
* username: student number e.g. u1234567
* password: date of birth e.g. 01jan97

Add a foreach loop in the body of the document that will display the title of each of the films.

## Creating a 'browseable' list
Using the lecture examples as a guide build a simple 'browseable' web application
  * Modify your list.php page so that each film is displayed as a hyperlink that links to a page named *details.php* (you will need to create a *details.php* page).
  * If you can get this to work, try and pass the specific film's id in the query string.
  * In *details.php* connect to your database and run a query that will display the full details for the selected film. 

## Create a search facility for your *films* table
* Create a new HTML page and add the following form:
```html
<form action="results.php" method="get">
<label for="search">Enter a search term:</label>
<input type="text" name="search" id="search">
<input type="submit" name="submitBtn" value="Search">
</form>
```

* Create a PHP page *results.php*. 
* Add PHP code so that when the user enters a search term and clicks 'Search' results.php displays the search term they have entered.  
* Look at the lecture examples for advice on how you can use this search term to query a database and display films with titles that match the search term.

 

