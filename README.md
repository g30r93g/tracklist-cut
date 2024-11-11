# TracklistCut

A NextJS application to create chaptered sections of videos, cut the video at chapters and export them.

## Motivation
I listen to a lot of drum and bass, and particularly like listening to DJ sets.
Listening to them in the car helps me focus on the driving, but sometimes I need to be able to skip a track.
Doing so on YouTube or SoundCloud goes to the next set and it's incredibly frustrating if I do so accidentally.

At the moment, my solution to skippable tracks is to download the desired track as an m4a and cut it.
To do so, I get a tracklist from either [1001tracklists.com](https://www.1001tracklists.com) or the comments section.
I then create a [CUE sheet](https://en.wikipedia.org/wiki/Cue_sheet_(computing)) and run it through [m4acut](https://github.com/nu774/m4acut/tree/master) to give me the individual tracks in the set.

The aim of this application is to be able to generate the cue sheet visually for a specified track.
