# mpv-web-ui
**mpv web ui** is a simple (quick and very dirty) web based user interface for
the [mpv mediaplayer](http://mpv.io/). It serves a web page on port 8000,
providing controls for play/pause, seekin and adjusting volume. More
functionality can be added trivially and the UI can be refined by anyone with
basic web design skills.

To use it, simply copy `webui.lua` and `webui.html` to `~/.mpv/scripts`. mpv
will then run it automatically. Note that as the port is hard coded, only one
instance can be run at a time. This should be quite trivial to fix.
