Load the [Sakila Database](https://dev.mysql.com/doc/sakila/en/sakila-installation.html) into MySQL Workbench.

### Query the Sakila Database

* 1a. Display the first and last names of all actors from the table `actor`. 

* 1b. Display the first and last name of each actor in a single column in upper case letters. Name the column `Actor Name`. 

* 2a. Find the ID number, first name, and last name of an actor, of whom you know only the first name, "Joe." 

* 2b. Find all actors whose last name contain the letters `GEN`:

* 2c. Find all actors whose last names contain the letters `LI`. This time, order the rows by last name and first name, in that order:

* 2d. Using `IN`, display the `country_id` and `country` columns of the following countries: Afghanistan, Bangladesh, and China:

* 3a. Add a `middle_name` column to the table `actor`. Position it between `first_name` and `last_name`. Hint: you will need to specify the data type.

* 3b. Some of these actors have tremendously long last names. Change the data type of the `middle_name` column to `blobs`.

* 3c. Now delete the `middle_name` column.

* 4a. List the last names of actors, as well as how many actors have that last name.

* 4b. List last names of actors and the number of actors who have that last name, but only for names that are shared by at least two actors

* 4c. The actor `HARPO WILLIAMS` was accidentally entered in the `actor` table as `GROUCHO WILLIAMS`, the name of Harpo's second cousin's husband's yoga teacher. Write a query to fix the record.

* 4d. In a single query, if the first name of the actor is currently `HARPO`, change it to `GROUCHO`. Otherwise, change the first name to `MUCHO GROUCHO`, as that is exactly what the actor will be with the grievous error. (Hint: update the record using a unique identifier.)

* 5a. Use a query to re-create the schema of the `address` table. 

  * Hint: [https://dev.mysql.com/doc/refman/5.7/en/show-create-table.html](https://dev.mysql.com/doc/refman/5.7/en/show-create-table.html)

* 6a. Use `JOIN` to display the first and last names, as well as the address, of each staff member. Use the tables `staff` and `address`:

* 6b. Use `JOIN` to display the total amount rung up by each staff member in August of 2005. Use tables `staff` and `payment`. 

* 6c. List each film and the number of actors who are listed for that film. Use tables `film_actor` and `film`. Use inner join.

* 6d. How many copies of the film `Hunchback Impossible` exist in the inventory system?

* 6e. Using the tables `payment` and `customer` and the `JOIN` command, list the total paid by each customer. List the customers alphabetically by last name:

* 7a. Use subqueries to display the titles of movies starting with the letters `K` and `Q` whose language is English.

* 7b. Use subqueries to display all actors who appear in the film `Alone Trip`.

* 7c. Using joins retrieve the names and email adresses of all Canadian customers.

* 7d. Identify all movies categorized as family films.

* 7e. Display the most frequently rented movies in descending order.

* 7f. Write a query to display how much business, in dollars, each store brought in.

* 7g. Write a query to display for each store its store ID, city, and country.

* 7h. List the top five genres in gross revenue in descending order.

* 8a. View the top five genres by gross revenue.

* 8b. Display the view created in 8a.

* 8c. Write a query to delete it the view `top_five_genres`.

### Appendix: List of Tables in the Sakila DB
```
'actor'
'actor_info'
'address'
'category'
'city'
'country'
'customer'
'customer_list'
'film'
'film_actor'
'film_category'
'film_list'
'film_text'
'inventory'
'language'
'nicer_but_slower_film_list'
'payment'
'rental'
'sales_by_film_category'
'sales_by_store'
'staff'
'staff_list'
'store'
