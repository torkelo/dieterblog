+++
title = "Handing off uzbl to a new project leader"
date = "2010-11-22T15:05:35-04:00"
tags = ["uzbl"]
+++
Yesterday I did the <a href="http://www.uzbl.org/news.php?id=30">newspost on uzbl.org</a> which explains the reasoning.  I can add it feels pretty weird "giving away" and "leaving behind" a project you spent so much time on and which grew a large (well, for a FOSS side project with a hacker audience) base of users and contributors, and which served as inspiration for various other projects.<!--more--></p>

<p>But I know this was the right thing to do.  On one hand there were more and more contributions coming in and changes being proposed but on the other hand I disliked being involved so deeply in a "frontend" project.  Early last year, I happened to <a href="/uzbl_a_browser_that_adheres_to_the_unix_philosophy">see some problems with browsing and had some cool ideas to attempt alleviate them</a>, so it was fun kickstarting the project and making some things working, but I don't want to be the guy <i>maintaining a browser</i>.<br />

My demotivation has been holding back the progress of the project, but luckily my request for change did not go unanswered.  Brendan stepped up, shared some ideas and because he is well aware of all the work currently going on (including his own) he seems like a good candidate to take uzbl wherever he thinks it should go.</p>

<p>Also, because of the "I just want something that works completely, damnit!" I've never been a full-time Uzbl user.  (I think most uzbl users - and users of "hacker browsers" in general - still keep another browser for some specific sites and whatnot).  And I think some implementation decisions were a bit too radical and caused a bit too much complexity in return of too little flexibility.  Which is very ironic, because clearly plenty of folks love the uzbl architecture, and most say it just needs some finetuning (I.e. some people use the fast C-based cookie daemon rather then the python one, and it seems the problems with the escaping is something most people are okay with working around while waiting for a proper fix, whereas the non-perfect design frustrated me but I wasn't interested fixing it myself).  I'm getting intrigued in the advantages an integrated, single-language, tightly-coupled programming api can bring (like how <a href="http://luakit.org/">luakit</a> provides lua-bindings to WebkitGtk+), a design like this clearly has its own tradeoffs but at least it seems more easy to build something that works reasonably.  So I could try that and see how that works out.  Although I'm not looking forward to learning yet another language..<br />

Maybe this is just kind-of a "burnout", I don't know, Brendan (and others) have told me I can sound like I'm trying to discourage.  So I'll stop now.  At least now, everybody is happy ;-)</p>

<p>Stay tuned for the cool things Brendan will announce shortly, it will make uzbl better for existing and new users.<br />

Good luck, Uzbl community, although I can't help but watching closely...</p>