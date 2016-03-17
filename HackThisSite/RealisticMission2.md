#Chicago American Nazi Party

####Information Gathering
You have been asked to hack a Nazi party website and deface it. You need to login as Administrator to stop their planned rally. 

####The Task
On opening the site, you are met with a very simple page with some pictures and text. Not really much going on here. How are we going to get anywhere on this site? 

####The Solution
If you trusted your gut, you will already have right clicked to `View Source`. A very handy thing to do in any circumstance. You will likely have noticed a helpfully hidden webpage called `update.php`. Navigating to this page opens a distinctly simple login page. Trying any manner of login detail with 'Administrator' as the login is met with a strong repsonse. It's time to use other tactics. SQL Injection or SQLi for short is something we could try here. Enter `' or 1=1--` in the username field and hit 'Submit'. The webpage will redirect and you'll have completed this challenge. 

#####Well Done! 
