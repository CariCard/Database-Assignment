# Database-Assignment

Add database support to your word occurrences application.

Use the tutorials from "Learning Materials" to learn how to use MySQL Workbench
Add a schema called “word occurrences”. Add a table called “word”. Then, as you parse the document, add new words that are not already in the database like this,
insert into wordOccurrences.word (word) values ('the');

insert into wordOccurrences..word (word) values ('test');

insert into wordOccurrences..word (word) values ('this');

insert into wordOccurrences..word (word) values ('a');

select * from wordOccurrences..word

Add JDBC support to your Java project (http://tutorials.jenkov.com/jdbc/index.html Links to an external site.)
In your word occurrence application, instead of storing the frequencies in the array, store/read them from the database
This is a very simple database. The idea is to get it working.
