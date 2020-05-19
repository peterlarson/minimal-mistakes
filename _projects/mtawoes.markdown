---
title: "petersmtawoes.com" 
exerpt: "A website for deciding which NYC subway to take." 
header:
 teaser: assets/images/mta_problems_now.png
last_modified_at: 2018-07-01
---

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/mta_problems_now.png" alt="">

Every day when I commute to work I have a couple trains I can take, but it can feel like a gamble to decide which one to take. 

What makes this more frustrating is that the MTA's reported arrival times can sometimes be fairly inaccurate, and delays might not be reported until you're already stuck halfway across a bridge. 

I knew that the data about train delays had to happen, and so I made a simple website that uses Twitter's free API to see which trains have the most complaints. 

<a href="petersmtawoes.com"> petersmtawoes.com </a>

The two metrics on the site calculate different things. **Problems Now** reflects what percent of the tweets returned for a specific line happened in the last hour, and **Delays Lately** is the percentage of tweets that contain the word "delay"

On the backend the logic exists in an AWS lambda, so maintaining the site is more or less free. But because twitter's free api is rate-limited the site will stop working for a while if you reload it 50 or so times in a short interval. So don't do that.  