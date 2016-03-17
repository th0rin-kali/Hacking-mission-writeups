#Fischer's Animal Products

####Information Gathering
You have been asked to hack the site to gain acces to the email addresses so that your friend can troll them. 

####The Task
You open the site and it reveals a page with an input box to enter an email address to be added to the mailing list. Two other links that take you to 'Fur Coats' & 'Alligator Accessories'. 

####The Solution
If you have attempted this before looking up the solution, you may have played around with the mailing list, or tried some code injection on the form boxes like I did at first. On looking into SQLi (SQL Injection) in detail you will find that in some cases you can enter SQLi direct into the address bar. 

Click on 'Fur Coats'. A page appears and the first hint you get as to it being something to do with SQLi is the end of the URL `products.php?category=1`. As soon as I see that in a URL I fill with joy. It took several attempts for me to crack this, however, you want to be entering this code into the end of the URL. `UNION ALL SELECT NULL, *, NULL, NULL FROM email`.

A list of email addresses will appear on the screen in front of your eyes. Copy these to Notepad and navigate to your HackThisSite control Panel. Copy the name of the person who sent you the message in the opening script for the task `SaveTheWhales`. Navigate to the HTS homepage and login. Click HTS message centre and compose a message to `SaveTheWhales` copy in the emails you saved from earlier and send the message. 

You'll be notified that you have completed the challenge. 

Well Done!

N.B This was quite a tricky challenge to stick in the middle so don't get too down about looking it up. 
