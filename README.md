# My fork of st
This is my fork of st, it uses version 0.9.

# Patches
* [alpha](https://st.suckless.org/patches/alpha/)
<!-- * [xresources-reload-signal](https://st.suckless.org/patches/xresources-with-reload-signal/) -->
* [xresources](https://st.suckless.org/patches/xresources/)
* [ligature](https://st.suckless.org/patches/ligatures/)
* [scrollback](https://st.suckless.org/patches/scrollback/)
* [externalpipe](https://st.suckless.org/patches/externalpipe/)
* [newterm](https://st.suckless.org/patches/newterm/) - is not used because externalpipe and this patch are not compatible

# st - simple terminal
st is a simple terminal emulator for X which sucks less.


# Requirements
In order to build st you need the Xlib header files.


# Installation
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


# Running st
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

# Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

