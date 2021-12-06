# BookmarkManager

domainmodel.png shows the domain model 

# setting up 
Connect to psql and create the 'bookmark_manager' database

command CREATE DATABASE bookmark_manager;

Connect to the database using the pqsl command \c bookmark_manager;

Run the query we have saved in the file 01_create_bookmarks_table.sql

# run the Bookmark Manager app
run rackup
localhost:9292