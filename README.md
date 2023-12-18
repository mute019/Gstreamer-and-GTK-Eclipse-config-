# Gstreamer-and-GTK-Eclipse-config-

This part contains all the "LIBRARY" needed for configuring the linker in Eclipse to be able to run gstreamer, boost, glib 2.0 and gtk3.

Add the following to the C++ linker section: -l 
glib-2.0
gstvideo-1.0 (For videooverlay.h)
cairo
gdk-3
gtk-3
pangocairo-1.0
gstnet-1.0
gobject-2.0
gstbase-1.0
gstcheck-1.0
gstreamer-1.0
boost_filesystem
gstcontroller-1.0
boost_system

*Note: Add the following directory path to the C++ linker section if the GTK+3.0 does not work: -L

/usr/lib/x86_64-linux-gnu/

This part contains all the "INCLUDE" file directory for the stop.

/usr/lib/x86_64-linux-gnu/glib-2.0/include
/usr/include/atk-1.0/
/usr/include/gdk-pixbuf-2.0/
/usr/include/cairo/
/usr/include/harfbuzz/
/usr/include/pango-1.0/
/usr/include/gtk-3.0/
/usr/include/gstreamer-1.0
/usr/include/glib-2.0


