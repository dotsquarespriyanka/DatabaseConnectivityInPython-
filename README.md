# MySQL Data Fetching Using Python

This project demonstrates how to connect to a MySQL database using Python, fetch data from a table, and create a DataFrame for further analysis using the `mysql.connector` library and the `pandas` library.

## Requirements

- Python 3.x
- `mysql.connector` library
- `pandas` library

## Installation

1. Clone or download this repository to your local machine.

2. Install the required libraries using `pip`:

## Usage

1. Update the database connection details in the code:
   - `host`: The hostname of your MySQL server.
   - `user`: The MySQL user.
   - `passwd`: The password for the MySQL user.
   - `database`: The name of the database.

2. Run the Python script to fetch data from the MySQL table and create a DataFrame:

3. The script will establish a connection, execute the SQL query, fetch data, and create a DataFrame.

## Code Explanation

1. Import necessary libraries .

2. Create a connection object to the MySQL database.

3. Define an SQL query to fetch data from a specific table.

4. Execute the query using a cursor.

5. Fetch all the rows from the query result.

6. Extract column names from the cursor's description.

7. Create a DataFrame using the fetched data and column names.

8. Close the cursor and the database connection.
