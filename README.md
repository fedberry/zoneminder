## ZoneMinder

The FedBerry project team has coordinated with the ZoneMinder project to produce a special build of ZoneMinder specifically for the Raspberry Pi.

Here are some important features:

- Built against ffmpeg with hardware accel: mmal, omx, omx-rpi, and neon enabled
- libvlc method temporarily disabled until hardware accel bug is fixed. See ticket [18594](https://trac.videolan.org/vlc/ticket/18594).
- Uses Nginx rather than Apache
- After package installation, remember to follow all the steps found in /usr/share/doc/zoneminder-nginx/README


