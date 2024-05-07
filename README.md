### A TAS I made to achieve Perfect Rebirth Screen in NES Tetris. (Original Unmodified ROM)

Great thanks to Meat Fighter for making (this tetris bot)[https://meatfighter.com/nintendotetrisai/], it really saved me a ton of work. 

Unfortunately this bot has no knowledge of the crash theory and even attempted to patch the game to prevent crashing. 

I had the power of TAS to crash doge, why patch the game instead? That makes it very boring. 

So I search & replaced all memory.write statements in the bot's lua code so all the glitches and game crashes functions as intended. 

Then I just pause and make whatever adjustments I need to make to doge the crash whenever one happens. 

This is called a **perfect** rebirth screen because it goes through 5 complete level rollovers which not only rolls the level counter back to 0 but also keep the line counter at a multiple of 17600. 

This now has barely any difference than starting a fresh new game and the 810 lines marathon appears at exactly the same spot as a new game. 

I actually made it go for level 255 one more time after 5 rollovers has been completed just as a proof that the 810 lines level is now at the same spot as a new game. 

After reaching level 255 for one last time, I don't wanna just top out and die. Instead, I successfully managed to trigger a very bizarre and rare game crash behavior at level 255 to end the run. After collaborating with the game for over 9 hours, trying my best to reduce the stress of the game's ancient code, I betrayed at the last level before we could get the 6th level rollover. HAHAHAHA! 

To my surprise, the game's RNG rewarded me with an extremely bizarre crash behavior that draws random shapes onto the board and it no longer takes in left and right inputs. After a few seconds, the ending screen appears without even have top out
