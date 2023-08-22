# Quicksilver
Automatically fetch the lyrics of the currently playing song and display them in your terminal!

![lyrics](https://cdn.discordapp.com/attachments/1142900449662468186/1143013981972344933/photo_5120808238105865551_w.jpg)
## Supported Players
Quicksilver uses the MPRIS interface to fetch the title, artist, and album names, which it then uses to fetch the lyrics. - examples of players with MPRIS support:
* Spotify
* VLC Media player
* Rhythmbox
* Audacious
* C* Music Player (CMUS)
* Music Player Daemon (MPD)

> With version 1.4.1 and above, browser media detection is also possible.

> For MPD player support install `python-mpd2` package as well.

## Planned Features
* Auto Scrolling Lyrics
* Add YouTube Music as the main lyrics source
* minor appearance tweaks
* a method of detecting when the lyrics are wrong and chosing a different song/source
