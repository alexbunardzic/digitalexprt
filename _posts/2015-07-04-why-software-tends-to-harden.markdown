---
layout: post
title: "Why Software Tends to Harden?"
date: 2015-07-04T10:30:54-07:00
---

The nature of a software product is to be soft, meaning maleable, pliable, easy to mold and modify. The very word 'soft' is in the name of the product -- software.

Isn't it surprising to see how many, if not most of the software products tend to harden as we work on them? We've all been there (and most likely more often than once): start some software development project, and get excited at first while observing how quickly we make useful and significant changes and continue adding value. But the initial buzz quickly wears off. Soon enough we get to the point where we realize that, all of a sudden, the honey moon appears to be over. Our shiny new product, that was up until yesterday so eager to emnbrace change and go into any direction we ask it to go, has now turned into a grumpy old curmudgeon.

This is the much dreaded point where we hit the wall, full speed, and experience rude awakening that's telling us that our product has hardened into a solid, impenetrable mass. Any attempt to add new features, or modify existing features, or even remove superfluous features, turns into a disaster. Touch this newly hardened software product, and it will bite back. All of a sudden, our codebase become averse to change. At this point, many teams resign to the fact that they have built a so called 'ball of mud', and label it 'legacy' and then learn to live with its quirks and foibles. Or, as is often the case, many team members at that point quit, and start looking for another opportunity for a fresh start.

This seemingly inevitable pattern is the bane of software developers' existence. It truly spoils all the joy we experience as we embark upon a brand new, exciting project. So the most pressing question for every software developer/engineer/programmer is -- _why_? Why does each software development project inevitably have to erode and be ttransformed from soft and pliable to hardened and immovable legacy writeoff?

Solve the above question, and you've made the world a better place. Easier said than done, but we'll try to supply some diagnostic, forensics, as well as some remedies in the articles to follow here.

<div id="disqus_thread"></div>
<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES * * */
    var disqus_shortname = 'alexbunardzic';
    
    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function() {
        var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
        dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>