# shutdown-dialog

![Example Dialog](http://i.imgur.com/iqAyyAD.png)

A shutdown dialog for WMs without it. Written in pyGTK, this should work on many systems out of the box. 

## installation

```
# cp shutdown-dialog.py /usr/local/bin/shutdown-dialog
# chmod 755 /usr/local/bin/shutdown-dialog
```

## embedding in awesome wm

Put the following in your rc.lua hotkey section:

`awful.key({ modkey, "Shift" }, "l", awful.util.spawn_with_shell("shutdown-dialog") ),`

Then restart awesome. If everything is set up corretly, <kbd>Mod</kbd>+<kbd>Shift</kbd>+<kbd>L</kbd> should bring up the dialog.

## extending

The code is pretty simple. Just look at it ;)
