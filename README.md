# Surfs_up

## Project Overview


## Results

### Deliverable 1
The goal of this deliverable was to split dataset into columns (backer_id, cf_id, name, and email)



### Deliverable 2
The goal of this deliverable was to split "name" column into "first_name" and "last_name" and then drop the "name" column



### Deliverable 3
The goal of this deliverable was to first update the schema and relationship diagram for our previous crowfunding database. Then create a new table named "backers" in pgAdmin. We also had to use the "ALTER TABLE" statement to change our previous tables we had created in the module.



### Deliverable 4
There were 4 different goals in Deliverable 4 as a bonus that involved running separate queries.
- Query 1 asked us to retrieve the number of backer counts (listed in descending order) for each "cf_id" for all "live" campaigns



- Query 2 asked us to run the same data but to also use the "backers" table. This allowed us to use an "INNER JOIN" to achieve the same result as the previous query



- Query 3 asked us to create a new table using the contact table that would list the first_name, last_name, email, and remaining goal amount (in descending order). This was tricky because we had to add in a function to our code to calculate the remaining goal amount by subtracting the pledged amount columns from our goal amount columns and create a new column with the remaining amount



- Query 4 asked us to create a new table using the backers table that listed the email, first_name, last_name, cf_id, company_name, description, end_date, and left of goal amount


