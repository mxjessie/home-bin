# home-bin

here's a buncha tiny shell scripts and stuff for doing interesting or
inconvenient things

some of the more interesting things in here:

* `authdb-export`: given a backup of a sqlite database of 2FA secrets from the
  Google Authenticator app on Android, convert the secrets into scannable QR
  codes

* `burrow`: starts an ssh-forwarding reverse tunnel from the current host to a
  host of your choosing, with a randomly-chosen high port and with systemd
  power management suspended (e.g. so laptops don't sleep on lid close)

* `gh_org_sync`: synchronize (clone or pull) every repo in a github
  organization, for backup or local full-text search purposes. optionally uses
  a custom remote hostname

* `keysies` very lazy muscle-memory tool for loading all of the ssh keyfiles in
  $HOME/.ssh/

* `lsiommu`: list pci devices by their iommu grouping, for vm passthrough
  purposes

* `marco`: super simple silly 'who's on this network with me' nmap alias

* `mirror`: do yr makeup or take selfies with mplayer/mpv

* `mkfriends`: host a furry convention right on your desktop

* `mkresume`: set up an appropriate i3 layout and then launch all the stuff
  needed to do realtime resume development. kinda like a tex ide. requires
  miscellaneous currently-unavailable files to work, though

* `postpic`: terrible script to shrink and exif-clean an image file, for safe
  online posting

* `randoizer`: given a twitter .csv archive of your tweets, randomly stream
  them to your terminal in glorious eye-burning technicolor

* `tp-toggle`: toggle the synaptics touchpad on e.g. a thinkpad, for when the
  touchpad-toggle shortcut button is pressed

* `xlock`: using i3lock and optionally ffmpeg, lock the desktop. ffmpeg is used
  for a questionably-secure-but-aesthetically-appealing blurred background
  image while locked
