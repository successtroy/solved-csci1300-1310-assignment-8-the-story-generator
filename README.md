Download Link: https://assignmentchef.com/product/solved-csci1300-1310-assignment-8-the-story-generator
<br>



<ol>

 <li>Design and create code in python using control structures (branching and looping) and user input.</li>

</ol>

For this assignment, you need to submit your program to moodle code runner. Please include comments in your code that explain what your code is doing.

In the game Mad-libs, players are asked for parts of speech, such a noun, adjective, or adverb, and those words are plugged into a template to generate a sometimes-funny story.




For this problem, write a program that plays a game of Mad-libs. Your program needs to store a list of story templates, when the user selects a number between 1 -5 select that template, and ask the user for parts of speech to fill in the template.




When the program starts, you should first ask the user if they want to play a game.




Your question should look like:

“Do you want to play a game? (y) or (n)”




The user types <strong><em>y</em></strong>​ if they want to play and <strong><em>n</em></strong>​ if they don’t. If the user answers <strong><em>y</em></strong>​​, then your program should ask the user to enter the template number:




“Please select a template between 1 and 5:”




Let’s assume the user enters 2, you need to ask the entries for each of the missing word type in the  template 2, such as:




“Enter a noun:
”

“Enter an adjective:
”

“Enter another noun:
”

“Enter another adjective:
”




<strong>Note: </strong>Template 2 looks like this​

“It was the &lt;adjective1&gt; of &lt;noun1&gt;, it was the &lt;adjective2&gt; of &lt;noun2&gt;”




There will be multiple templates with different requirements, your program will need to handle an arbitrary list of requirements. Build a new variable that includes the user entries in place of the word-type placeholders and print the variable to show the user the new sentence.




If the user types “n” when asked if they want to play, your program should print <strong>“good</strong>​<strong> bye” </strong>and exit.​




The user should be allowed to play the game as many times as they like. Each time after they play your program should ask if they would like to play again, and if they answer <strong><em>y</em></strong>​​, your program should repeat the game, beginning at the spot where you ask the user to enter the template number. If the user does not enter a number between 1 and 5 your program should print <strong>“Invalid</strong>​<strong> Template” </strong>and​ your program should repeat the game by asking the user if they want to play again.




Your program needs to include the following templates.

<ol>

 <li>“Be kind to your &lt;noun&gt;-footed &lt;plural noun&gt;, or a duck may be somebody’s &lt;noun&gt;.”</li>

 <li>“It was the &lt;adjective1&gt; of &lt;noun1&gt;, it was the &lt;adjective2&gt; of &lt;noun2&gt;.”</li>

 <li>&lt;plural noun&gt;? I don’t have to show you any &lt;adjective&gt; &lt;plural noun&gt;!</li>

 <li>My &lt;relative&gt; always said &lt;noun&gt; was like a box of &lt;noun&gt;. You never know what you’re gonna get.</li>

 <li>One &lt;time of day&gt;, I &lt;verb&gt; a &lt;noun&gt; in my pajamas. How he got in my pajamas, I don’t know.</li>

</ol>







<h2>Challenge Problem (do not submit to moodle)</h2>

Store the templates in a file and read in a new template for each new game. There are several on-line Mad-Libs games that you can use for creating your own templates. This would not be tested so please do not submit to moodle.


