# SQL INTRO
Fork & Clone this repository

After file is cloned, cd into the project directory then run this command in terminal:

	sqlite3 firstdb.db < testdb.mdf

Carefully look at the prewritten code and make sense of it before moving on. Compare it to what was retuned in terminal. Research anything that does not make sense. 

It may be helpful to turn on the syntax coloring for this. In sublime, go to the view menu > Syntax > open all current extensions as... > SQL

Then, continue with the steps below to write your own sql queries! 

When this exercise is completed, git add, commit and push your changes. Exercise is due at the end of class.

## TO DO:
#### Use this site as a resource: http://zetcode.com/db/sqlite/datamanipulation/

	 0) ADD POST TABLE
				-- Fields: ID, title, author, content 

	 0) DATA INSERTION
				-- Add at least 9 more records
				-- 4 to the users & 5 to the posts

	 1) QUERY SPECIFIC DATA
				-- Select all records
				-- Select the records that have a first name that is ‘caesar’
				-- Select all the titles from posts
				-- Select all the titles AND authors from posts
				-- Select only the first two records from users


	 2) CHANGE A VALUE
			-- change Caesar's last name to be Castaneda and the email to ccastaneda@latinschool.org

	 3) DELETE A RECORD
			-- delete the first record from the posts table


## BONUS: 
	 ADD A COLUMN
		-- After the table has already been created, see if you can update that table with a new column. 
			--Add a birthdate column to the user table. 
