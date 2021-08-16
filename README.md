This script watch the connections of the video outputs and applies the resolution stored in configuration's file.
Use this script to restore a non-standard monitor resolution when connecting. For example, you connect a TV and want to get a resolution that is not stated in the edid file.
Configure the resolution yourself and call '--save' to save the configuration file

Requirements:
md5sum
cvt
xrandr
edid-decode
stdbuf
udevadm

Preferably notify-send
