Download Link: https://assignmentchef.com/product/solved-cs2028-lab-6-stacks-and-queues
<br>
The objective of this Lab is to examine stacks and queues built using C++.  This will take the famous “Towers of Hanoi” game and modify the rules to be a challenge between 2 players.

<strong>Task 1: </strong>Create a stack class that will be used as the basis for the remainder of the lab. Complete this before moving on to task 2.

<ol>

 <li>Create a new C++ project. You can name this whatever you like.</li>

 <li>Design a stack class using an array. This class should be a template.

  <ol>

   <li>The constructor should include a parameter to indicate the size of the array.</li>

   <li>The array holding the data should be an array of pointers.</li>

   <li>The push function should accept a pointer and add that pointer to the top of the stack. It doesn’t need to create any memory.</li>

   <li>The pop function should return a pointer. It doesn’t need to delete any memory.</li>

   <li>The top function should return a pointer to the item on the top of the stack without removing it.</li>

   <li>The length function will return an int indicating the number of items in the stack.</li>

   <li>The empty function should empty the stack of all contents. It needs to call delete to avoid memory leaks.  It doesn’t need to return any value.</li>

   <li>The stack should declare a friend function that can access the underlying array for the purposes of printing it to the screen.</li>

   <li>Create the implementation code for the above functions as required. <strong>Do not</strong> use cout in the class.  Any errors such as overflow or underflow should throw a custom class error.</li>

  </ol></li>

</ol>

<strong>Task 2:  </strong>Create a single person version of the “Towers of Hanoi” game.

<ol>

 <li>Read the introduction to the game at <a href="https://en.wikipedia.org/wiki/Tower_of_Hanoi">https://en.wikipedia.org/wiki/Tower_of_Hanoi</a>.</li>

 <li>Create a main program that uses stacks to allows the user to interactively play the game.

  <ol>

   <li>It needs to determine the number of disks to use in the game.</li>

   <li>It needs to provide a way for the user to indicate the tower to move from and to.</li>

   <li>It needs to prevent illegal moves as defined in the Wikipedia rules.</li>

   <li>It needs to provide the user with a way to see their progress on the screen.</li>

  </ol></li>

 <li>Test your program to ensure it is working correctly. This should test both expected success conditions and expected error conditions.</li>

 <li>Include in the lab report a screen shot(s) of the output of your tests.</li>

</ol>

<strong>Task 3:  </strong>Make a game of it.

<ol>

 <li>Create a new project.</li>

 <li>Copy any code from the previous project you may need into this project.</li>

 <li>In this version, there are 2 towers on each side and 1 tower in the middle. Each player needs to move their disks over to the other side (which tower on the other side is not relevant so long as they are on a single tower).  You will need to find a way to signify which disk belongs to which player.  Each players disk of similar size is considered equal and may be placed on the other.  Each player may move any top disk to any tower on their turn so long as the move is legal.</li>

 <li>Test this game in your group.</li>

 <li>Include in the lab report a screen shot(s) of the output of a test. Include a discussion of the different strategies you tried (cooperative, defensive, ignoring the other player completely, etc…).</li>

</ol>

<strong>Task 4:  </strong>Create a queue to track steps.

<ol>

 <li>Create a new project.</li>

 <li>Create a queue class. This class should be a template.</li>

 <li>Design the queue class using a vector to store data. Include the standard functions for a queue.</li>

 <li>Implement the queue class.</li>

 <li>Design a data structure to hold a single move.</li>

 <li>Create an instance of the queue class to hold the move data structure designed above.</li>

 <li>Copy and modify the code from Tasks 1 and 2 to store any moves made in the queue class. When the game is won, the queue should be used to print out all the moves made in order.</li>

 <li>Include in the lab report a screen shot(s) of the output of a test. Include a discussion of how you designed your move data structure and how you had to modify the code for automating the game.</li>

</ol>