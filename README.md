WebSQLShell
===========

A one-page Web SQL shell.

A friend of mine recently asked to teach her some SQL. She wants to practice at work during her lunch-break. But paranoid security rules of the place don't let her install ANYTHING on her machine or run any unapproved executable or access any site except wikipedia and few others, though she can receive text files by e-mail. So I tried to find a [Web SQL](http://en.wikipedia.org/wiki/Web_SQL_Database) shell for Chrome browser she has and found nothing (maybe I just cant find the right words to ask google nicely). Then I just coded this thing. I know that WebSQL is a dead technology. But maybe sometimes it'll help somebody.

##Q&A##

##What does it look like?##
![Screenshot1](WebSQLshell_screenshot1.png)

###What can it do?###
It just creates a local database with hard-coded name 'testdb1' and allows you to execute SQL statements. You can execute multiple statements at once (SQL dump of some db for example). Individual statements should be separeted with ";\n" (semicolon followed by end of line).

###Do I need to install it?/How to use it?###
No. You don't need to install anything except some browser with WebSQL support. Just open provided WebSQLshell.html. That's all. 

###When should I use it?###
You should consider using something like this only out of interest or when you don't have any other choice (like me). There are much better SQLite shells out there. Many of them are free.

###What browsers does it support?###
Tested it in only Chrome v35. I think it will work in Opera and Safari but didn't check.
It defenitely won't work in Firefox because it lacks WebSQL support. 



