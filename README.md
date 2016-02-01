# Test-Driven-Development

###History

Timeline:

* 1976 - publication of "software reliability" by Glenford Myers states a developer should never test their own code.
* 1990 - black box techniques dominate (in black box testing, the tester does not know how the code works, only what it               should be doing in the end).
* 1994 - Kent Beck writes SUnit testing framework for Smalltalk
* 1998 - Extreme Programming article about writing the test first
* 1998 - 2002 Test first becomes Test Driven
* 2003 - Kent Beck's Test Driven Development: By Example is published
* 2006 - Test Driven Development is considered a relatively mature discipline



###Test Driven Development Basics

Test Driven Development (TDD) is a style of programming with 3 primary activities:
1) Coding
2) Testing
3) Refactoring
BUT ... they are not done in that order.

The key steps are:
1) write the test
2) run the test - make sure that it fails.  It is important that the test fails.
3) write just enough code to pass the test
4) run the test - hopefully it will pass
5) refactor the code if needed
6) repeat the process
The cycle is very quick - each iteration should not take more than a couple of minutes.

This is referred to as a Red, Green, Refactor cycle.  Each cycle moves the code forward just a bit.  One advantage
of this is that you are never very far away from passing code.

TDD is often used in Agile Software Development environment.






###User Process

####General User
* Sign up/sign in
* Click on one of the tournaments (currently the Australian Open is the only one active)
* Click on draws or player name to obtain more detailed information

####Admin User
* Sign up/sign in
* Click on one of the tournaments (currently the Australian Open is the only one active)
* Click on draws or player name to obtain more detailed information
* Click on ADMIN FUNCTIONS to be directed to initial admin functions page.  From there, the admin user can Create, Update, Edit or Delete a player, country, or user.



###Language and Framework Used

* Ruby on Rails



###Links
