# Linux_OS20.04_gnome-shell-40.0_beta_source_deps_help
ubuntu , 21.04 , gnome-shell-40.0 , special os wayland webgl support , gtk4

Beta meta project portation gtk4 in ubuntu 20.04 idea

inpack gnome-shell-40.0.zip /tmp

cd /tmp/gnome-shell-40.0/build

sudo apt install gir1.2-gnomeautoar-0.1 libarchive-dev libgnome-autoar-0-dev libgraphene-1.0-dev libpolkit-agent-1-dev libstartup-notification0-dev libgjs-dev dh-migrations libaccountsservice-dev gnome-settings-daemon-dev gsettings-desktop-schemas-dev gtk-doc-tools libcanberra-gtk3-dev libcheese-dev libcheese-gtk-dev libcolord-dev libcolord-gtk-dev libcups2-dev libgirepository1.0-dev libgnome-desktop-3-dev libgnomekbd-dev libgnome-bluetooth-dev libibus-1.0-dev libgoa-1.0-dev libgrilo-0.3-dev libgsound-dev libgtop2-dev libgudev-1.0-dev libkrb5-dev libnm-dev libnma-dev libmm-glib-dev libpolkit-gobject-1-dev libpulse-dev libpwquality-dev libsecret-1-dev libsmbclient-dev libsnapd-glib-dev libudisks2-dev libupower-glib-dev libwacom-dev libwhoopsie-preferences-dev libxklavier-dev libxml2-dev xvfb python3-dbusmock libgck-1-dev libgcr-3-dev libp11-kit-dev  gir1.2-camel-1.2 gir1.2-ecal-2.0 gir1.2-edataserver-1.2 gir1.2-ical-3.0 libcamel1.2-dev libecal2.0-dev libedataserver1.2-dev libical-dev libmutter-6-dev libmozjs-68-dev comerr-dev dh-migrations docbook-to-man gir1.2-cheese-3.0 gir1.2-clutter-gst-3.0 gir1.2-colord-1.0 gir1.2-colordgtk-1.0 gir1.2-gkbd-3.0 gir1.2-grilo-0.3 gir1.2-gsound-1.0 gir1.2-gtkclutter-1.0 gir1.2-modemmanager-1.0 gir1.2-rest-0.7 gnome-settings-daemon-dev gobject-introspection gsettings-desktop-schemas-dev gtk-doc-tools krb5-multidev libaccountsservice-dev libbrotli-dev libcanberra-dev libcanberra-gtk-common-dev libcanberra-gtk3-dev libcheese-dev libcheese-gtk-dev libclutter-1.0-dev libclutter-gst-3.0-dev libclutter-gtk-1.0-dev libcogl-dev libcogl-pango-dev libcogl-path-dev libcolord-dev libcolord-gtk-dev libcups2-dev libcupsfilters-dev libcupsimage2-dev libdrm-dev libevdev-dev libgirepository1.0-dev libgles2-mesa-dev libgnome-bluetooth-dev libgnome-desktop-3-dev libgnomekbd-dev libgoa-1.0-dev libgoa-backend-1.0-dev libgrilo-0.3-dev libgsound-dev libgssrpc4 libgstreamer-plugins-base1.0-dev libgstreamer-plugins-good1.0-dev libgstreamer1.0-dev libgtop2-dev libgudev-1.0-dev libibus-1.0-dev libinput-dev libjson-glib-dev libkadm5clnt-mit11 libkadm5srv-mit11 libkdb5-9 libkrb5-dev libmm-glib-dev libmtdev-dev libnm-dev libnma-dev libnotify-dev liborc-0.4-dev liborc-0.4-dev-bin libpolkit-gobject-1-dev libpsl-dev libpulse-dev libpwquality-dev librest-dev libseccomp-dev libsecret-1-dev libsmbclient-dev libsnapd-glib-dev libsoup2.4-dev libsqlite3-dev libudev-dev libudisks2-dev libupower-glib-dev libwacom-dev libwhoopsie-preferences-dev libx11-xcb-dev libxklavier-dev libxml2-dev modemmanager-dev python3-bs4 python3-dbusmock python3-html5lib python3-lxml python3-markdown python3-packaging python3-pyparsing python3-soupsieve python3-webencodings xvfb

sudo ln -s /usr/include/gtk-3.0/gdk /usr/include/gdk

sudo ln -s /usr/include/gdk/gdkwayland.h /usr/include/gdk/wayland/gdkwayland.h

sudo ln -s /usr/include/gdk/gdkx.h  /usr/include/gdk/x11/gdkx.h

sudo ln -s /usr/lib/x86_64-linux-gnu/pkgconfig/gtk+-3.0.pc /usr/lib/x86_64-linux-gnu/pkgconfig/gtk4.pc

sudo ln -s /usr/lib/x86_64-linux-gnu/pkgconfig/libmutter-6.pc /usr/lib/x86_64-linux-gnu/pkgconfig/libmutter-8.pc

sudo ln -s /usr/lib/x86_64-linux-gnu/pkgconfig/mutter-cogl-pango-6.pc /usr/lib/x86_64-linux-gnu/pkgconfig/mutter-cogl-pango-8.pc

sudo ln -s /usr/lib/x86_64-linux-gnu/pkgconfig/mutter-cogl-6.pc /usr/lib/x86_64-linux-gnu/pkgconfig/mutter-cogl-8.pc

sudo ln -s /usr/lib/x86_64-linux-gnu/pkgconfig/mutter-clutter-6.pc /usr/lib/x86_64-linux-gnu/pkgconfig/mutter-clutter-8.pc

all .pc replace shell 3.36.7 to 40.0

special os https://youtu.be/MVhZ_QZGxaQ

Experiment final reinstall perfomance my original build mesa perfomance https://github.com/Griggorii/mesa-27.0.1-glib-2.31-ubuntu20.04-linux-wayland-graphics

Recomendated build 20.04 final 1) purge all dev 2) reinstall mesa https://github.com/Griggorii/mesa-27.0.1-glib-2.31-ubuntu20.04-linux-wayland-graphics default perfomance special video driver

sudo apt purge gir1.2-gnomeautoar-0.1 libarchive-dev libgnome-autoar-0-dev libgraphene-1.0-dev libpolkit-agent-1-dev libstartup-notification0-dev libgjs-dev dh-migrations libaccountsservice-dev gnome-settings-daemon-dev gsettings-desktop-schemas-dev gtk-doc-tools libcanberra-gtk3-dev libcheese-dev libcheese-gtk-dev libcolord-dev libcolord-gtk-dev libcups2-dev libgirepository1.0-dev libgnome-desktop-3-dev libgnomekbd-dev libgnome-bluetooth-dev libibus-1.0-dev libgoa-1.0-dev libgrilo-0.3-dev libgsound-dev libgtop2-dev libgudev-1.0-dev libkrb5-dev libnm-dev libnma-dev libmm-glib-dev libpolkit-gobject-1-dev libpulse-dev libpwquality-dev libsecret-1-dev libsmbclient-dev libsnapd-glib-dev libudisks2-dev libupower-glib-dev libwacom-dev libwhoopsie-preferences-dev libxklavier-dev libxml2-dev xvfb python3-dbusmock libgck-1-dev libgcr-3-dev libp11-kit-dev  gir1.2-camel-1.2 gir1.2-ecal-2.0 gir1.2-edataserver-1.2 gir1.2-ical-3.0 libcamel1.2-dev libecal2.0-dev libedataserver1.2-dev libical-dev libmutter-6-dev libmozjs-68-dev comerr-dev dh-migrations docbook-to-man gir1.2-cheese-3.0 gir1.2-clutter-gst-3.0 gir1.2-colord-1.0 gir1.2-colordgtk-1.0 gir1.2-gkbd-3.0 gir1.2-grilo-0.3 gir1.2-gsound-1.0 gir1.2-gtkclutter-1.0 gir1.2-modemmanager-1.0 gir1.2-rest-0.7 gnome-settings-daemon-dev gobject-introspection gsettings-desktop-schemas-dev gtk-doc-tools krb5-multidev libaccountsservice-dev libbrotli-dev libcanberra-dev libcanberra-gtk-common-dev libcanberra-gtk3-dev libcheese-dev libcheese-gtk-dev libclutter-1.0-dev libclutter-gst-3.0-dev libclutter-gtk-1.0-dev libcogl-dev libcogl-pango-dev libcogl-path-dev libcolord-dev libcolord-gtk-dev libcups2-dev libcupsfilters-dev libcupsimage2-dev libdrm-dev libevdev-dev libgirepository1.0-dev libgles2-mesa-dev libgnome-bluetooth-dev libgnome-desktop-3-dev libgnomekbd-dev libgoa-1.0-dev libgoa-backend-1.0-dev libgrilo-0.3-dev libgsound-dev libgssrpc4 libgstreamer-plugins-base1.0-dev libgstreamer-plugins-good1.0-dev libgstreamer1.0-dev libgtop2-dev libgudev-1.0-dev libibus-1.0-dev libinput-dev libjson-glib-dev libkadm5clnt-mit11 libkadm5srv-mit11 libkdb5-9 libkrb5-dev libmm-glib-dev libmtdev-dev libnm-dev libnma-dev libnotify-dev liborc-0.4-dev liborc-0.4-dev-bin libpolkit-gobject-1-dev libpsl-dev libpulse-dev libpwquality-dev librest-dev libseccomp-dev libsecret-1-dev libsmbclient-dev libsnapd-glib-dev libsoup2.4-dev libsqlite3-dev libudev-dev libudisks2-dev libupower-glib-dev libwacom-dev libwhoopsie-preferences-dev libx11-xcb-dev libxklavier-dev libxml2-dev modemmanager-dev python3-bs4 python3-dbusmock python3-html5lib python3-lxml python3-markdown python3-packaging python3-pyparsing python3-soupsieve python3-webencodings xvfb


