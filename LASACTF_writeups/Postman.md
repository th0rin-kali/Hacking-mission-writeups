#Postman  
##50xp

####Problem
Kyle made a super secure website only accessable by the Google Ultron brwser. Figure out how to login to the site

####Solution
Took me a while to figure this one out. I tried HTTP Header changes in Chrome and FF, to no avail. However, after a while I turned to trusty Linux terminal and curl. 

Using curl to modify the http headers with this script
`curl --referer kyleisacoolguy.org -H "SpecialAuth:Kyle" -A 'Google Ultron'` 'http://web.lasactf.com:45025/'

Flag - {h3aders_ar3_c00l}
