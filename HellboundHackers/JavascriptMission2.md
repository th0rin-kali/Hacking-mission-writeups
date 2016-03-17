#Javascript Mission 2

####Background
When you open the 2nd mission you are met with what looks like a Basic Authentication prompt. No other information or hints. 

####Solution
My first instinct in this instance is to try and get rid of the box to get to the source code. Luckily pressing `ESC` twice makes the box disappear. This lets you get into the source, however, in this instance I thought I'd attack it from another angle. 

Right click the empty page. Click into `Inspect Element` in Chrome or FireFox. Navigate to the `Resources` item. Drop down `Frames` then `Scripts`. You'll see a Javascript file called `level2script.js`. Clicking on this file will reveal the password in the code without much reviewing of the code. 

One of the easier JS challenges I must admit. 
