There are two examples of API and DB testing with the usage of Jmeter.
We have prepared database on the localhost with standard port 5432.
The database name is mydb.
There are two standard tables in the db: 
1) cities and location:
2) cities with the weather parameters on the particular date.
We also have prepared API on the localhost with standard port 5000, which connected to our DB.

There are 5 tests for DB:
1) Check the insert functionality of DB;
2) Check the possibility of interacting with DB tables and getting data from it;
3) Check the insertion correctness;
4) Check the data deletion functionality;
5) Check the data deletion correctness.

There are 5 tests for API similar to previous one:
1) Check the POST request functionality;
2) Check the possibility of interacting with DB tables and getting data from it;
3) Check the POST request correctness;
4) Check the DELETE request functionality;
5) Check the delete request correctness.

You can choose as many possible users as you want to check the possibility of the system to work in stress conditions.
For this purpose use threads properties settings.