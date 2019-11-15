# Programming-Gang

Assignment 4: Tower of TerrorFor this assignment, you will be modifying Assignment 3 with the use of loops using someone else’s
code. You need to remember what you have learned in class, lab, books and your assignments. Be sure to refer to them when you 
need to.There are 2 parts to this assignment. In the first part, you are going to need to modify the program’s structure, 
update algorithms and create a new flow chart to solve it. In the second part, you’ll be using those to help you modify the 
java program. So let’s get started!Part 1: Your loopy Haunted Tower of Terror adventure!You loved creating your Haunted House 
in Assignment 3 so much, that you decided to you want to go for gold and make one that is even better. To do this, though, you 
want to really practice your skills and modify your friend’s program. Hurrah!So, first, you will be partnered with someone to 
work on the assignment with. Once this is posted on Moodle, you will want to be sure to send them your Assignment 3 submission.
Don’t forget to ask for both the Word/Open Office document and the entire Netbeans project file. You’ll need to review their 
flow chart and pseudocode, and then take a look at their code.You may work with this person when it comes to understanding 
their approach and their code, so be sure to exchange contact information if you have not already done so. The first thing you 
will do is make sure that you fully understand their approach and their code. You will then do the following:With your partner
, review the modifications listed below Select one of your submissions to modify as a teamDetermine who will do what work on
the assignment (be sure to be explicit about this, both with your partner and in your submission)Set up a schedule and 
deadlines for completing the assignmentAll of this must be documented, included in your Word/Open Office document and turned in
with your new program.Modifications Required:Step 1: JavaDocsJavadoc is a tool that generates html documentation from Javadoc 
comments that you put in your code.  As was covered in Lab, you will be adding JavaDocs to your selected submission. 
COP 2210Dr. Debra DavisBoth partners MUST add a portion of the JavaDocs, and it was be clearly indicated in your JavaDocs, 
which partner added which related comments.As a review, here are two tutorials on the creation and use of 
JavaDocs:http://www.tutorialspoint.com/java/java_documentation.htmhttps://students.cs.byu.edu/~cs240ta/fall2012/tutorials/javadoctutorial.html
Once you have completed this step, you will tackle the functional modifications below, updating your JavaDocs as needed.
Step 2: Functional Modifications:You will need to make the following modifications, some of which will need appropriate use of 
loops:The user will have to navigate the Haunted Tower of Terror using an elevator. Each differentroom from the previous 
assignment will be a floor.oYou can decide which floor is which except for:The First Floor [Floor 1] (must be the front door 
from the previous assignment).The Basement [Floor 0], this is the bottom most floor of the Tower. It has two rooms, either 
which is accessible from the elevator. The Boiler RoomThe Storage RoomoThis room has a chest inside that has a key to the 
attic. The user must pick up this item, and stash it in their backpack.The Attic [Last Floor], this is the top most floor of 
the Tower. It has one room, and has a chest. The user may only enter the attic IF they have thekeyfrom the basement.All other 
floorsare rooms from the previous assignment. It is up to you what floor each room will take. They should function similarly to
how they did in the last assignment(exploring, items, etc.)
COP 2210Dr. Debra DavisThe user will have a backpack that contains all the items they’ve collected during their journey.
oThe backpack does NOT have to be an array.oThe backpack can be a simple string, which can contain all the items that a user 
has.oUse the contains method on the string that is acting as the user’s inventory to find out what items they currently contain.
e.g. inventory.contains(“string”) will return true if the word “string” is anywhere within the string inventory.
https://www.tutorialspoint.com/java/lang/string_contains.htm The user will start at the first floor (the front door) and 
must immediately decide where they want to go.oAllow your adventurers to go to any flooras many times as they want. 
(they can leaveand return to the first floor multiple times)oAllow your adventurers to engage in as many actions as they want 
in any floor (including exploring multiple items, if applicable)oGive them the option to leave the tower if they are still 
alivewhenthey are standing at the first floor AND have the key from the attic’s chest. You must allow backtracking.
The game ends when the adventurer leaves the tower:oThey must first get the key from the basement to the attic, then
oThey must goto the attic, thenoThey must get the key from the attic to the First Floor door, then
oThey must go back to the first floor and exit.You must include comments to every method and every variable 
(only where they are declared) that indicates what they do (methods) and what they are used for (variable).
All of the other requirements of Assignment 3 will still hold.IMPORTANT: If one of you already has backtracking in your 
Assignment 3, you MUSTuse the other partner’s code (which does not have backtracking)You are required to use, at minimum, 
one of each the following:oA for loopoA while loopoA do-while loopFor Part 1, modify the class structure(s), algorithms and 
flow chart for the new program, and then do several iterations of tests (i.e., analyze it and step through to make sure that 
it is logically correct). Also check the pseudocode for the tester class(where your main will go). 
Your documentation regarding who will do what by 
COP 2210Dr. Debra Daviswhen must also be included. Put these in a Word or Open Office document. You’ll turn that document in 
with the program that you create in Part 2.Important! As you are working on this, be sure to break this down into smaller 
pieces. Take it step-by-step, and don’t try to finish this in one sitting. It will make it MUST easier. Part 2: Modifying your
loopy Hunted Tower of Terror adventure programOnce you are done revising and testing the class structure and algorithms, 
you are ready to start modifying the code! 
1.   You should already have a Netbeans project. If you only have the source code,
you will need to create a project. Here’s a nice tutorial on how to do that in Netbeans. If you are using Dr. Java or Eclipse,
just do a quick search on youtube.com and you’ll find lots of candidates.http://www.youtube.com/watch?v=ezUHG1cuxkMBe sure to
give your project a nice, meaningful name (and make sure it adheres to Java’s naming conventions).
2.   Once you have your shell ready, there are a few things to know before you start translating your algorithm into code
At the top of your class file, be sure to include the following:
//********************************************************************************
// PANTHERID:  [PantherID]// CLASS: COP 2210 – [Semester Year]// ASSIGNMENT # [#]// DATE: [Date]
////PATHERID OF ORIGINAL CODER: [Panther of the person whose program you are //modifying]
//// I hereby swear and affirm that this work is solely my own, and not the work 
// or the derivative of the work of someone else, except as outlined in the 
// assignment instructions.//********************************************************************************
3.   Now start translating your changes into java code. Remember to code and then compile frequently. 
It will make it easier to find any bugs.
COP 2210Dr. Debra DavisAlso remember that you will need a separate tester class (where your main method will reside)
if there is not already one.IMPORTANT: Don’t forget to update your JavaDocs as needed!
4.   Once you get your program running correctly, run through 3 scenarios (we will, of course, be testing your other scenarios,
but use these for your output):Enter the Living Room at least 3 times and at least 5 other rooms
Finish in an upstairs room where the user dies after you have explored the entire houseFinish by successfully leaving the
house after exploring at least 5 rooms and 4 objects5.   Here is one more thing to do. Any input requested from the user
and/or output received from the user should be in a window (see E.1.14 and E.1.15 from lab 1). At this point, you probably 
have your output going to the console. For your final submission, it needs to go to a window (JOptionPane). 
Don’t forget any additional libraries that you need to import to do this.That’s it! Now you have written your first adventure
game! Of course, you’ll also need to turn it in to Moodle.Submission RequirementsYou must upload a zip file to Moodle 
that includes your complete source project in Netbeans, ready to load (We have been very lenient up until now regarding this.
From this assignment on, you will lose points if you do not include your complete project.), and also contains the output in 
separate data files, and your Word/Open Office document with your algorithm.  
VERY IMPORTANT: If you do not provide output in separate, easy to find data files, I will assume that your program does not 
work on those test cases, and grade accordingly. Do not embed the output in your source code.
