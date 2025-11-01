Project: zuul-bad
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

This project is a simple framework for an adventure game. In this version,
it has a few rooms and the ability for a player to walk between these rooms.
That's all.

To start this application, create an instance of class "Game" and call its
"play" method.

This version of the game contains some very bad class design. It should NOT
be used as a basis for extending the project without fixing these design
problems. It serves as an example to discuss good and bad design (chapter 8
of the book).

Chapter 8 of the book contains a detailed description of the problems in this
project, and how to fix them.

The project 'zuul-better' contains a version of this project with better
designed class structure. It includes the fixes discussed in the book.

ANSWERS TO QUESTIONS:

9. It returns a set of keys that are in the HashMap.

13. We change the currentRoom and also the available exits.

17.Yes, because I would have to implement the command's behavior inthe processCommand method in Game class.

18. I do not understand the question.
