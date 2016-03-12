#Thinkpad X220: i3 config file (includes i3blocks.conf) 

This to guide people setting up a new i3 config file specifically on a X220. 
The most important part you should look at when you're setting up is the volume and brightness controls. 
This is just a conglomeration of things I've found elsewhere on the internet! 

###Requires (or at least uses):

- FontAwesome 
- i3blocks
- amixer
- feh 
- compton
- nm-applet


###Window assignments for:
- Google Play Music Desktop Player (workspace 10)
- Steam (workspace 9)


###scrolling enables horizontal two finger scrolling. Place it in /usr/local/bin/ 
```
#!/bin/bash
synclient HorizTwoFingerScroll=1 #enable horizontal two finger scrolling
```

