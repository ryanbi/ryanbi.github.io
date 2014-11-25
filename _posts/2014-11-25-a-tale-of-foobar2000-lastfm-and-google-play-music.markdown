---
layout: post
title:  "A Tale of foobar2000, last.fm, and Google Play Music."
date:   2014-11-25 21:57:00
categories: Blog life music
---

I like my [foobar2000](http://www.foobar2000.org/) music player. I have used it religiously for almost 10 years. I swear by it and it has not ever let me down a single time. And although I am by no means a music addict, listening to various ballads helps me calm down and relax.

![My foobar2000 setup](//i.imgur.com/chnlLuo.jpg)

I used [last.fm](http://last.fm) to count my track play counts. It worked really well for me since 8 years ago, and until now I have counted more than 85000 plays. If an average song is 4 minutes long, I have spent 230 days alone in my life just listening to music. I am not an active user there but knowing that how many play counts feels really satisfying.

I know that there is a script that [syncs foobar2000 playcounts with last.fm and can love a track inside it](http://www.hydrogenaud.io/forums/index.php?showtopic=76772). Why I didn’t do try that script? Well it was a hassle setting it up. After all why would you do that when [foo_audioscrobbler](http://www.foobar2000.org/components/view/foo_audioscrobbler) does its jobs perfectly, and if I really needed to sync, it will be only when my computer crashed… 

Until last month.

I swore that I made a backup at that time, but alas you won’t really know your backup works until the crash happened. And yes, it didn’t worked. Crap. I couldn’t care less about anything but my foobar2000 skins, extensions, and play counts. 

I can remade skins and install the same extensions, but… play counts? Perhaps nope. Then I remembered last.fm. What if I can sync my play counts to foobar2000?

Then I remembered that script and installed it.

As a music lover and an Android devotee, it is imperative to upload all my songs to Google Play Music. I liked the setup and it is the best music player on Android. However the only problem that I have is that it didn’t know what music that I like. 

Okay Google, Next. Next. Next. Next. Nope.

Then I had an idea: why not put the last.fm loved tracks into Google Play Music thumbs up? Then make a playlist auto-download the liked playlist. So Everytime I liked a music on my foobar2000, it goes to last.fm server, then it goes to Google Play Music, then to my phone downloaded. Neat.

So then I looked up for a program, script, anything. Nil. None. The only thing that works is for scrobbling tracks. I was disappointed.

Then I stumbled on [this thread on reddit that sync Pandora likes to Google Music](https://www.reddit.com/r/allaccessplaylists/comments/2hqflx/i_wrote_a_python_script_to_sync_pandora_likes_to/).  I know that last.fm has easy API access and if somehow I could edit the Python code it may go well.

So I rewrote the script based on that script and now I put those on my github. By no means is it a legit, clean and efficient code… but hey it works… After all I only wanted my liked music on my phone. And that is all that mattered for me
