NETB380
======

Variant 4: Test generator

Using C++/Qt and Postgres database write a test generator program that allows 
the user automatically to generate tests out of the database of questions and 
possible answers. The program supports two main activities: course database 
creation and test generation.

The course database creation has the following features:

-the user can enter a question with five possible answers. Only one of 
the answers is selected as correct and all the others are wrong;
-the user can choose a level of difficulty that corresponds to the question;
-the user selects the course to which this question is relevant.

The test generation has the following features:

-the user selects the number of questions that will be contained in the test;
-the user selects how many questions of each level of difficulty will be included;
-the program selects randomly the required questions, and scrambles the answers randomly;
-the program generates a list of pairs question – correct answer for the instructor;
-the generated test is in HTML file format in paper size A4, ready for printing.
