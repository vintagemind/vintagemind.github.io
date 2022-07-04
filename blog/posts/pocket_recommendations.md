[⬅️ Back](vintagemind.github.io/blog)

## Pocket Recommendations Suddenly Disappeared From Firefox Homepage


<img width="1507" alt="Screen Shot 2022-07-01 at 2 12 32 pm" src="https://user-images.githubusercontent.com/63845509/176822131-26e13431-1231-48c3-9815-e2e9cc5a01e0.png">




Pocket recommendations suddenly disappeared from homepage! How do I get it back? I'll gladly tell you!
It used to be under Settings -> Home -> Recommended By Pocket. And the "Recommended By Pocket" option has just mysteriously disappeared into thin air. 
Sounds like you? You've come to the right place. 

As you can [see](https://support.mozilla.org/en-US/questions/1370851#answer-1490472), I have answered this question before but nevertheless, since this blog is also a vault of memories and info for myself, I've decided to add this.

This is not a very recommended solution in the sense that you always need to be extremely carefully when going and changing settings in about:config. Because, if you accidentally change some very important configurations, the result won't be nice at all...so do at your own risk please. 

1) Try first to delete Firefox and reinstall. 
2) If the above didn't work, go to **about:config** and set "**browser.newtabpage.activity-stream.feeds.system.topstories**" to **true**.

Hope that gives your "Recommended By Pocket" option back in settings. 
