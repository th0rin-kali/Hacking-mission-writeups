# Uncle Arnolds local band review

Your friend is being cheated out of hundreds of dollars. Help him!! 

####Information Gathering
You are given a website where people can select a number and vote on a band they like. You friend placed a bet that his band would win.
All his band members died and the owner still wants to carry on with the bet. $500 is at stake. 

####The Task
A fairly simple webpage with some PHP coded elements and buttons. Raging Inferno are last (Your friends band) and you need to get them on top, so what are you going to do? 

####The Solution
Using Firebug for Firefox or Chrome Inspect Element, right click the 'Vote!' button on Raging Inferno
This takes you to the code snippet for that button. 
The line you need is above <select name="vote">
Drop this tag to reveal the other code entries.
We need to change the value of '5' to represent a higher value
Change <option value="5">5</option> to <option value="9999">5</option>
This will send the value 9999 to the server as a vote for Raging Inferno instead of just 5. 

You will be notified that you have completed the task. 

Well Done! 
