# JS Title Crashing

I found this exploit when trying to make a more malicous version of yourareanidiot.cc.
A while back there was an exploit involing making a list full of data which would crash
the memory after a while. Most major browsers fixed these easily by killing the script after a while
and limiting the amount of memory it can use. Well I found something else. If you change the tab title
instead of just changing the list. It will go out of memory ater a while but because it's changing the
tab's title it goes into the visual and the browser can't change the title that quick due to the amount
of changes being made which increases the memory and crashes the browser. To show this how powerful this
exploit is, when I opened it for one second on my mac the chrome browser instantly froze and went to 0.05 fps
per a second and in around a minute or so the mac crashed and restarted automatically. I haven't seen
it anywhere else so I think this is a pretty new exploit. Something similar can also be done using the
tab icon. This would be more effective on firefox as they allow a fps rate of around 10 with the browser icon
where as chrome has one of 5.
