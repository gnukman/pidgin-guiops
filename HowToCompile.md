#How to compile.

# Linux #

If you compiled Pidgin from source, the following will suffice to compile this plugin:

  * Download the source code tarball
  * Extract the tarball
  * open a console window
  * type "make"
  * you should then get a file pidgin-guiops.so
  * copy pidgin-guiops.so to your ~/.purple/plugins directory

If you didn't compile Pidgin from source, you will get errors while compiling the GUIOps plugin. To solve this, install the packages (thanks tolean.dj, craigwharding):

  * pidgin-dev
  * libpurple-dev

and compile again.


# Win32 #

As of version 0.5.1, the source code package contains a script cross\_compile.sh. Execute this script to compile the win32 dll on a Debian or Ubuntu machine.