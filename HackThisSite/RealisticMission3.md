#Peace Poetry: HACKED

####Information Gathering
A little girl made a poetry website. It has been hacked by American fascists and replaced the homepage with Hitler-esque propaganda. They have asked you to restore the site. 

####The Task
At first it seems like there is no way of doing this. I sat myself wondering about this one for a while. `View Source` turns up nothing.
of note.

####The Solution
Right clicking the defaced homepage using `Inspect Element` shows some commented out text `<!--Note to the webmasterThis website has been hacked, but not totally destroyed. The old website is still up. I simply copied the old index.html file to oldindex.html and remade this one. Sorry about the inconvenience.-->`. This is great news. A hacker with a conscience. Append `oldindex.html` to the URL. The little girls website appears. 

In order to replace the defaced homepage with the old index page visit the `Submit poems` link. Here you will be able to `POST` new poems. In the interests of quickness I won't go into too much detail of how I found out how to sort this, however, copy the source code from the `oldindex.html` file, and enter `../index.html` in the 'Name of poem:' box. Paste the `oldindex.html` source code into the 'Poem:' box and hit 'add poem' 

You will be notified that you have completed this task. If you blindly followed this tutorial and have not understood how that worked read on. 

###What happened there then?
The HTC challenge URL `https://www.hackthissite.org/missions/realistic/3/` is the 'root' base of the website. The defaced index homepage is the root page. When you `POST` a poem you are submitting it to the site regardless of anything else and it creates a webpage for it. Even if there's a poem there with the same name as another it will overwrite it. This gives you a step as to how to replace the original index file. The `../` syntax in front of the `index.html` in the solution is telling the site to climb up one level to submit this poem. Essentially you are replacing the Index.html page of the site with new content. 

A bit of a tricky one but worthy of understanding what goes on. 
