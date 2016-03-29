#Grep Quest
##40xp

####Problem
Locate the flag in all the words at /problems/grep-quest_0/grepy-words/

####Solution
I kept coming back to this one after trying others. I approched it thinking it was an addition to the URL for the page, however this was wrong. I noticed the site had a `shell` that you could use so I searched through the directories. Navigated to the directory with a massive list of txt files. 

I used the command `grep -r _` to search all the files in the directories for contents with underscores. 

Flag - {1_am_a_h1dd3n_p0tat0}
