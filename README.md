# saxmap
A haxxorized keyboard map for the Swedish keybård läjaut

## Installation
To install this layout you have to do things.

### Debian
Copy the `se` file to `\usr\share\X11\xkb\symbols\`, this will not affect
the default Swedish key map but if you have made your own changes these guys
will be overwritten.

Run: `sudo dpkg-reconfigure xkb-data` too apply the changes.

Activate the key map by simply running `setxkbmap se prog` or through whatever
weak GUI you are using.

### Other distros and things
Google it. 
