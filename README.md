# scpcb-1.3.12-ng
A buggy unfinished recompilation of the dev "1.3.12" branch of scp containment breach using blitz3d-ng.

Some things that don't work properly:\
-Audio issues\
  -Certain sounds won't play\
  -Certain sounds won't stop playing (just type stfu in console (f3) to stop currently playing sounds)\
  -This is due to blitz3d-ng using a completely different audio implementation and things like audio streaming just don't work, I kinda hacked my way around this one to get it playable.\
-Gameplay issues\
  -The starting cutscene (not the intro) can bug out sometimes, running up and down the stairs seems to fix it eventually\
  -Some room collision is broken (this is a 1.3.12 bug not mine) just be careful around the cowbell room as you may get stuck\
  -And probably a lot more I'm forgetting, I made this like a year ago\
-Graphical issues\
  -Bumpmaps don't work at all (another blitz3d-ng "feature")\
  -Monitors have Z-fighting issues\
  -The blur effect still doesn't display correctly in 1440p (I tried my best to fix it)

So what's the point of all this?\
Well a few improvements you might notice are improved performance (generally), new rooms, reskinned rooms, and 1440p support (ONLY WITH DGVOODOO (https://dege.freeweb.hu/dgVoodoo2/dgVoodoo2/)).\
Other than that the game is mostly playable, you should be able to complete the game although I'm yet to do a full run on this build.

Feel free to contribute, the audio streaming issues are top priority at the moment but I'd also like to see the blur effect render properly in 1440p (refer to "Dreamfilter.bb").
