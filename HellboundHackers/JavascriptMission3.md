#Javascript Mission 3

####Background
When you open the 3rd mission you are met with what looks like a Basic Authentication prompt. No other information or hints.

####Solution
My first instinct is to view the source. It should always be the first instinct of a Web Application pentester, even though it is widely neglected. 

In the source you will see an encrypted javascript. The javascript has been URL encoded. You can easily decode the script at http://meyerweb.com/eric/tools/dencoder/ . Once decoded, the username and password will be evident.

This too was an easy challenge.
