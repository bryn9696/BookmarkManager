# BookmarkManager

domainmodel.png shows the domain model 

# Set up bookmark_manager: 
Connect to psql and create the 'bookmark_manager' database

command CREATE DATABASE bookmark_manager;

Connect to the database using the pqsl command \c bookmark_manager;

Run the query we have saved in the file 01_create_bookmarks_table.sql

# Set up bookmark_manager_test: 
Connect to psql and create the 'bookmark_manager_test' database

command CREATE DATABASE bookmark_manager_test;

Connect to the database using the pqsl command \c bookmark_manager_test;

Run the query we have saved in the file 01_create_bookmarks_table.sql

# run the Bookmark Manager app
run rackup
localhost:9292