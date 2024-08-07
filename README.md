# The problem with Wine shortcuts
By default, making a shortcut (or a Link) for a .exe program, makes it so it doesn't see any other files = your program won't find any dependencies like .dlls, thus won't start.


# So...
...here's the **simplest** solution to this problem! (that I could come up with, at least 😜)

# How-To
This template has three lines: 
* "cd **filepath**" - to enter the desired folder.
    > Replace **filepath** with your program's folder path in quotation marks, e.g. 'cd "/home/user/Windows Games/"'
  
* "wine **filename**" - to open the file while having access to all files.
   > Replace **filename** with your program's file name in quotation marks, e.g. 'wine "3D Pinball.exe"'
  
* "xrandr -s 0" - to restore your default resolution e.g. if you're playing an old game and it doesn't change it back automatically.

# Enjoy!
Now enjoy your Wine programs from the beautiful Linux desktop! :D
