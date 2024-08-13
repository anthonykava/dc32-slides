# DEF CON 32 Talk: Solving the "Lover, Stalker, Killer" Murder with strings, grep, and Perl
## Given 2024-08-11 @ 1200 PDT (1900 UTC), streamed on [DCTV](https://dctv.defcon.org) via [Twitch](https://www.twitch.tv/defconorg) and [YouTube](https://www.youtube.com/user/defconconference)

**TW: DISCUSSION OF VIOLENCE (no graphic images), BAD WORDS (it's DEF CON, so that's par for the course)**

**DISCLAIMER:** Personal views only. Views do not represent my employer(s), or anyone else. No endorsements are intended nor should any be construed. If your presentation lasts longer than 20 minutes call a DEF CON Goon.

### [This is the deck](DC32-S533-Kava-v24-08-10-1224.pdf) that I used for the talk I gave on the Warstories Track at [DEF CON 32](https://defcon.org/html/defcon-32/dc-32-index.html) in Las Vegas.

[![Slide deck GIF animation preview](preview.gif)](DC32-S533-Kava-v24-08-10-1224.pdf)

<br>

## If you want to do something nice to honour Cari Farver's memory, please consider donating to the Cari Farver Memorial Scholarship Fund. Visit: https://farverscholarship.org

<br>

This investigation had a huge digital component, and I worked that side of it and did the digital forensics examinations.  This talk covered some of the specific open source tools adapted to help solve this case.

On the stage, I used Eye of Gnome (eog(1)) to show slides stored as individual JPEG images copied to a tmpfs RAM disk.  The goal was speed and simplicity although it would have helped if I knew my screen wasn't mirroring for the first couple minutes! (Thankfully, a helpful hacker in the audience yelled-out, and we were able to quickly remedy it.)

This PDF was made by gluing the JPEG slides together into one file. The deck is 133 slides, of which about 128 are talk content (I feel safer with powers of 2), and they were shown in 20 minutes or less for an average rate of >= 6.4 slides/min.

This was cramming a lot of info into a short timespan and intended to feel like a lightning talk with an over-caffeinated tempo reminescent of [Clifford Stoll's wonderful 2006 TED Talk](https://www.ted.com/talks/clifford_stoll_the_call_to_learn).

And this only covers like 1% of the case!

For more information, the [Netflix documentary](https://www.netflix.com/title/81611991) is a great place to start, and there's a lot of detail and background in Leslie Rule's book, *[A Tangled Web: A Cyberstalker, a Deadly Obsession, and the Twisting Path to Justice](https://www.kensingtonbooks.com/9780806539997/a-tangled-web/)*.

There has also been coverage on shows like [Dateline NBC](https://www.nbcnews.com/dateline/video/full-episode-scorned-1247985219637) and [ABC 20/20](https://abc.com/episode/ef002d2b-4401-4333-840a-35a1071fc4aa). There's even a [Lifetime Movie](https://www.mylifetime.com/movies/the-disappearance-of-cari-farver) dramatisation that features the very talented [Erik Athavale](https://www.imdb.com/name/nm5813845/) playing a version of me that's younger with more hair (and personality!).

And, yes, there are Easter Eggs or subtle references in multiple slides.  I hope you find them.

The recorded video should eventually be posted to the [DEF CON Media Server](https://media.defcon.org) and [YouTube](https://www.youtube.com/user/defconconference). An older version of my slide deck is already on the Media Server, but the copy found here is the one that was used (and it will probably also replace the older copy on the DEF CON site sometime after people are back home from the con). For DC31 it took about two months for videos to appear.

I did a [Reddit AMA](https://www.reddit.com/r/IAmA/comments/1bax5zv/i_am_the_nerd_from_netflixs_lover_stalker_killer/) months back that answered a lot of questions. If you haven't seen it, I highly recommend watching the wonderful [Netflix documentary, "Lover, Stalker, Killer"](https://www.netflix.com/title/81611991), before watching or reading this presentation.

Feel free to reach-out just to connect or to ask questions.  My contact methods are found at https://forensic.coffee.

THANK YOU to DEF CON, the Goons, especially my excellent assigned Speaker Goon, all those who attended in-person or streamed, and all of you who might see this presentation after the con.  Please remember Cari Farver and all victims of violent crime, and let's agree to let those who harmed them be forgotten.

-- Kava 2024-08-12 21.30 UTC
<br>
<br>
  
*Excerpt from the [DEF CON 32 Website](https://defcon.org/html/defcon-32/dc-32-speakers.html):*

> Solving the "Lover, Stalker, Killer" Murder with strings, grep, and Perl
> Sunday at 12:00 in LVCC - L3 - W322-W327 (Warstories Track)
> 20 minutes | Demo 💻
> Anthony Kava
> 
> Cari Farver did not disappear off the face of the Earth. She was murdered in cold blood, and her killer went on to impersonate her online, for over three years. The suspect hid their tracks with VPNs, proxies, and anonymizing apps. This talk will go behind the scenes of Netflix's "Lover, Stalker, Killer" to detail the open source software and bespoke methods used to prove a no-body homicide case based almost entirely on digital evidence.
> 
> Dateline NBC, S26E1 "Scorned" (2017) Rule, Leslie. "A Tangled Web: A Cyberstalker, a Deadly Obsession, and the Twisting Path to Justice". Citadel Press, 2020. Netflix, "Lover, Stalker, Killer" (2024)
>
> Anthony Kava
>
> Anthony Kava is a hacker and carries a badge. Got his start breaking Apple IIs then moved, somehow, to breaking baddies. Works as a cyber crime investigator and digital forensics examiner with a penchant for infosec. Kava is a recognized Soylent drinker, scourge to software vendors, and has been portrayed by a Canadian in a Lifetime movie. Dreams in Perl. Enjoys long walks on the dark web.
>
> LinkedIn: https://linkedin.com/in/anthonykava<br>
> Website: https://forensic.coffee
