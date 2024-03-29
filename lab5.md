viewable at https://samuraichamp.github.io/cse15l-lab-reports/lab5
# Part 1: Debugging Scenario
## Student
Hello, I'm having an issue with my `deleteIndex` method in the `MyMinHeap` class as shown below<br>
![Image](code.png)<br>
I implemented this method using helper methods premade for us as well as using the ArrayList data made earlier. When I run the tests given to us with a bash script I made, I get a pass as shown below<br>
![Image](test.png)<br>
![Image](bash.png)<br>
However, after I submit to Gradescope, I got the following output from the final tests<br>
![Image](result.png)<br>
I'm guessing there is something wrong with my `deleteIndex` method relating to its use of the `percolateUp` helper method. Please help!
## TA
Is there ever a time when deleting an index from your heap might result in the need for an index to be percolated up? If so, your method needs to take advantage of the `percolateUp` helper method somehow.
## Student
Thank you that worked! Looks like I didn't account for that scenario and didn't have any code to help with that! <br>
![Image](newCode.png)<br>
![Image](newResult.png)<br>
# Part 2: Reflection
I thought learning different vim shortcuts was really fun! Vim itself seems like kind of a pain to use but the activity where we had to use as few keypresses as possible was super cool and it made researching different vim commands and finding the best way to do something really fun.
