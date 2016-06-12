# shutdown-dialog

![Example Dialog](http://i.imgur.com/iqAyyAD.png)

A shutdown dialog for WMs without it. Written in pyGTK, this should work on many systems out of the box. 

## installation

`# cp shutdown-dialog.py /usr/local/bin/shutdown-dialog`

## embedding in awesome wm

Put the following in your rc.lua hotkey section:

`awful.key({ modkey, "Shift" }, "l", awful.util.spawn_with_shell("shutdown-dialog") ),`

## extending

The code is pretty simple. Just look at it ;)
