# Buildroot Source Changes
Checked on 2020-02-05-08:48

Last time there was a change was [2020-02-04-13:00](https://github.com/minimization/square1-results/blob/master/docs/archives/2020-02-04-13:00/data/buildroot-changes.md)
## SOURCE DEPENDENCIES ADDED
Total New Sources Added: 203

PA = Package Added  R = Requires Added Package  OLD = Not New
* acpica-tools PA
  * xen  R
* atril PA
* attica PA
  * kdelibs  R
  * kdelibs-devel  R
* automoc PA
  * kdelibs  R
  * kdelibs-devel  R
  * phonon-qt4  R
  * polkit-qt  R
* bridge-utils PA
* brltty PA
  * qemu  R
* caja PA
  * atril  R
* capstone PA
  * qemu  R
* catdoc PA
  * kf5-kfilemetadata  R
* cln PA
  * libqalculate  R
* crash PA
  * systemtap  R
* desktop-backgrounds PA
  * plasma-workspace  R
* dhcp PA
  * NetworkManager  R
* dnsmasq PA
  * libvirt  R
* dpkg PA
  * libabigail  R
* dtc PA
  * qemu  R
  * xen  R
* dwarves PA
  * kernel  R
* dyninst PA
* editorconfig PA
  * kf5-ktexteditor  R
* efivar PA
  * mokutil  R
* espeak PA
  * brltty  R
* f31-backgrounds PA
* fonttools PA
  * google-noto-emoji-fonts  R OLD
  * sazanami-fonts  R OLD
  * vlgothic-fonts  R OLD
  * fonttools  R
  * google-noto-emoji-fonts  R OLD
  * graphite2  R OLD
  * liberation-fonts  R OLD
  * nototools  R OLD
  * smc-anjalioldlipi-fonts  R OLD
  * smc-dyuthi-fonts  R OLD
  * smc-meera-fonts  R OLD
  * smc-rachana-fonts  R OLD
* fuse-sshfs PA
* gcr PA
  * gnome-online-accounts  R OLD
  * gvfs  R OLD
  * libgdata  R OLD
* glib2 PA
  * GConf2  R OLD
  * ModemManager  R OLD
  * NetworkManager  R
  * NetworkManager-libnm-devel  R
  * PackageKit  R OLD
  * PackageKit-glib-devel  R
  * accountsservice  R OLD
  * appstream  R OLD
  * arts  R OLD
  * at-spi2-atk  R OLD
  * at-spi2-core  R OLD
  * atk  R OLD
  * avahi  R OLD
  * babeltrace  R OLD
  * bluez  R OLD
  * cairo  R OLD
  * colord  R OLD
  * cups-filters  R OLD
  * dbus  R OLD
  * dbus-c++  R OLD
  * dbus-glib  R OLD
  * dconf  R OLD
  * dconf-devel  R
  * desktop-file-utils  R OLD
  * enchant  R OLD
  * enchant2  R OLD
  * evince  R OLD
  * firewalld  R OLD
  * freerdp  R OLD
  * fuse-sshfs  R
  * gamin  R OLD
  * gcr  R
  * gcr-devel  R
  * gdk-pixbuf2  R OLD
  * geoclue2  R OLD
  * gettext  R OLD
  * glib-networking  R
  * glibmm24  R OLD
  * gnome-autoar  R OLD
  * gnome-desktop3  R OLD
  * gnome-online-accounts  R OLD
  * gnome-online-accounts-devel  R
  * gobject-introspection  R OLD
  * gpgme-devel  R
  * granite  R OLD
  * grubby  R
  * gsettings-desktop-schemas  R OLD
  * gspell  R OLD
  * gssdp  R OLD
  * gstreamer1  R OLD
  * gtk2  R OLD
  * gtk3  R OLD
  * gtksourceview3  R OLD
  * gts  R OLD
  * gupnp-igd  R OLD
  * gvfs  R OLD
  * harfbuzz  R OLD
  * java-atk-wrapper  R OLD
  * json-glib  R OLD
  * libaccounts-glib-devel  R
  * libappstream-glib  R OLD
  * libblockdev  R OLD
  * libblockdev-utils-devel  R
  * libcacard  R
  * libcacard-devel  R
  * libcroco  R OLD
  * libdazzle  R OLD
  * libdnf  R OLD
  * libgdata  R OLD
  * libgdiplus  R OLD
  * libgee  R OLD
  * libgrss  R OLD
  * libgsf  R OLD
  * libgtop2  R OLD
  * libgudev  R OLD
  * libgusb  R OLD
  * libgxps  R OLD
  * libical  R OLD
  * libimobiledevice  R OLD
  * liblqr-1  R OLD
  * libmbim  R OLD
  * libmodulemd  R OLD
  * libmodulemd1  R OLD
  * libnice  R OLD
  * libnotify  R OLD
  * libosinfo  R OLD
  * libproxy  R OLD
  * libpsl  R OLD
  * libqalculate  R
  * libqb  R OLD
  * libqmi  R OLD
  * libquvi  R OLD
  * librepo  R OLD
  * libreport  R OLD
  * librsvg2  R OLD
  * libsecret  R OLD
  * libslirp  R
  * libsoup  R
  * libstoragemgmt  R OLD
  * libuser  R OLD
  * libverto  R OLD
  * libvirt  R
  * libwacom  R OLD
  * libxklavier  R OLD
  * mate-common  R OLD
  * nautilus  R OLD
  * openjfx  R OLD
  * osinfo-db-tools  R OLD
  * p11-kit  R OLD
  * pacemaker  R OLD
  * pango  R OLD
  * passwd  R OLD
  * perl-Glib  R OLD
  * phonon  R OLD
  * phonon-qt4  R
  * pipewire  R OLD
  * plasma-workspace  R
  * polkit  R OLD
  * polkit-pkla-compat  R OLD
  * poppler  R OLD
  * ppp  R
  * pulseaudio  R OLD
  * pygobject2  R OLD
  * pygobject3  R OLD
  * pygtk2  R OLD
  * qt  R OLD
  * qt5-qtbase  R OLD
  * qt5-qtwebengine  R OLD
  * qt5-qtwebkit  R OLD
  * qtwebkit  R
  * quilter  R OLD
  * rest  R OLD
  * serd  R OLD
  * shared-mime-info  R OLD
  * sord  R OLD
  * speech-dispatcher  R OLD
  * spice  R
  * sssd  R OLD
  * sysprof  R OLD
  * totem-pl-parser  R OLD
  * udisks2  R OLD
  * uhttpmock  R OLD
  * umockdev  R OLD
  * upower  R OLD
  * usermode  R OLD
  * vala  R OLD
  * volume_key  R OLD
  * vte291  R
  * webkit2gtk3  R OLD
  * weston  R OLD
  * wireshark  R
  * wmctrl  R OLD
  * wpebackend-fdo  R OLD
  * xapps  R OLD
  * xdg-dbus-proxy  R OLD
  * xkeyboard-config  R OLD
  * xreader  R OLD
  * ibus  R OLD
  * libblockdev  R OLD
  * libmodulemd  R OLD
  * libmodulemd1  R OLD
  * GConf2  R OLD
  * ModemManager  R OLD
  * NetworkManager  R
  * PackageKit  R OLD
  * PackageKit-glib  R
  * accountsservice  R OLD
  * appstream  R OLD
  * appstream-qt  R
  * arts  R OLD
  * at-spi2-atk  R OLD
  * at-spi2-core  R OLD
  * atk  R OLD
  * atkmm  R OLD
  * atril  R
  * babeltrace  R OLD
  * bluez  R OLD
  * cairo  R OLD
  * caja  R
  * caja-core-extensions  R
  * clisp  R OLD
  * colord  R OLD
  * cups-filters  R OLD
  * dbus-glib  R OLD
  * dconf  R OLD
  * denemo  R OLD
  * desktop-file-utils  R OLD
  * efl  R OLD
  * emacs  R OLD
  * enchant  R OLD
  * enchant2  R OLD
  * evince  R OLD
  * firewalld  R OLD
  * fontforge  R OLD
  * fuse-sshfs  R
  * gamin  R OLD
  * gcr  R
  * gcr-base  R
  * gdk-pixbuf2  R OLD
  * gdlmm  R OLD
  * gdm  R OLD
  * geoclue2  R OLD
  * git  R OLD
  * glib-networking  R
  * glibmm24  R OLD
  * gnome-autoar  R OLD
  * gnome-desktop3  R OLD
  * gnome-online-accounts  R OLD
  * gnuplot  R OLD
  * gobject-introspection  R OLD
  * granite  R OLD
  * graphviz  R OLD
  * gsettings-desktop-schemas  R OLD
  * gspell  R OLD
  * gssdp  R OLD
  * gstreamer1  R OLD
  * gstreamer1-plugins-bad-free  R OLD
  * gstreamer1-plugins-base  R OLD
  * gtk-sharp2  R
  * gtk2  R OLD
  * gtk3  R OLD
  * gtkmm24  R OLD
  * gtkmm30  R OLD
  * gtksourceview3  R OLD
  * gtkspell3  R OLD
  * gts  R OLD
  * gupnp  R OLD
  * gupnp-igd  R OLD
  * gvfs  R OLD
  * harfbuzz  R OLD
  * ibus  R OLD
  * inkscape  R OLD
  * java-atk-wrapper  R OLD
  * json-glib  R OLD
  * lash  R OLD
  * lasi  R OLD
  * libaccounts-glib  R OLD
  * libaccounts-glib-devel  R
  * libappstream-glib  R OLD
  * libblockdev  R OLD
  * libblockdev-btrfs  R
  * libblockdev-crypto  R
  * libblockdev-fs  R
  * libblockdev-kbd  R
  * libblockdev-loop  R
  * libblockdev-lvm  R
  * libblockdev-mdraid  R
  * libblockdev-part  R
  * libblockdev-swap  R
  * libcacard  R
  * libcanberra  R OLD
  * libcroco  R OLD
  * libdazzle  R OLD
  * libdnf  R OLD
  * libgdata  R OLD
  * libgdiplus  R OLD
  * libgdl  R OLD
  * libgee  R OLD
  * libgexiv2  R OLD
  * libglade2  R OLD
  * libgnomekbd  R OLD
  * libgrss  R OLD
  * libgsf  R OLD
  * libgtop2  R OLD
  * libgudev  R OLD
  * libgusb  R OLD
  * libgxps  R OLD
  * liblqr-1  R OLD
  * libmalaga  R
  * libmbim  R OLD
  * libmodulemd  R OLD
  * libmodulemd1  R OLD
  * libnice  R OLD
  * libnotify  R OLD
  * libosinfo  R OLD
  * libqmi  R OLD
  * libquvi  R OLD
  * librepo  R OLD
  * libreport  R OLD
  * librsvg2  R OLD
  * libsecret  R OLD
  * libslirp  R
  * libsoup  R
  * libstoragemgmt  R OLD
  * libudisks2  R
  * libuser  R OLD
  * libvirt-libs  R
  * libwacom  R OLD
  * libwmf  R OLD
  * libxklavier  R OLD
  * libxml++  R OLD
  * lilypond  R OLD
  * malaga  R OLD
  * mate-desktop  R OLD
  * mate-desktop-libs  R
  * nautilus  R OLD
  * openbox  R OLD
  * openjfx  R OLD
  * osinfo-db-tools  R OLD
  * pacemaker  R OLD
  * pango  R OLD
  * pangomm  R OLD
  * pangox-compat  R
  * passwd  R OLD
  * pcsc-lite  R OLD
  * perl-GTop  R OLD
  * perl-Glib  R OLD
  * polkit  R OLD
  * polkit-pkla-compat  R OLD
  * polkit-qt  R
  * polkit-qt5-1  R
  * ppp  R
  * pygobject2  R OLD
  * pygtk2  R OLD
  * qt  R OLD
  * qt5-qtbase  R OLD
  * qt5-qtmultimedia  R OLD
  * qt5-qtwayland  R OLD
  * qt5-qtwebkit  R OLD
  * qtwebkit  R
  * quilter  R OLD
  * rest  R OLD
  * rrdtool  R OLD
  * samba  R OLD
  * shared-mime-info  R OLD
  * speech-dispatcher  R OLD
  * spice-server  R
  * sysprof  R OLD
  * totem-pl-parser  R OLD
  * tracker  R OLD
  * tracker-miners  R OLD
  * udisks2  R OLD
  * uhttpmock  R OLD
  * umockdev  R OLD
  * upower  R OLD
  * usbauth-notifier  R OLD
  * usermode  R OLD
  * vala  R OLD
  * volume_key  R OLD
  * volume_key-libs  R
  * vte291  R
  * webkit2gtk3  R OLD
  * weston  R OLD
  * wireshark  R
  * wireshark-cli  R
  * wmctrl  R OLD
  * wpebackend-fdo  R OLD
  * wxGTK3  R OLD
  * xapps  R OLD
  * xdg-dbus-proxy  R OLD
  * xreader  R OLD
  * qemu  R
* glib-networking PA
  * libsoup  R
* gnu-efi PA
  * mokutil  R
* gpsd PA
  * plasma-workspace  R
* grantlee PA
  * kdelibs  R
* grubby PA
  * qemu  R
  * qemu-sanity-check  R
* gtk-sharp2 PA
  * avahi  R OLD
* herqq PA
  * kdelibs  R
* hwdata PA
  * libosinfo  R OLD
  * libpciaccess  R OLD
  * osinfo-db  R
  * pciutils  R OLD
  * usbutils  R OLD
* ipcalc PA
* ipmitool PA
* iputils PA
  * apache-commons-exec  R OLD
  * rubygem-em-http-request  R OLD
* kate4 PA
* kde-cli-tools PA
* kde-connect PA
  * kde-connect-libs  R
  * kf5-purpose  R
* kdecoration PA
  * kwin  R
  * plasma-breeze  R
* kde-l10n PA
* kdelibs PA
  * kate4  R
  * kde-l10n  R
  * plasma-breeze  R
* kernel PA
  * kernel  R
  * kernel-modules  R
  * qemu  R
  * qemu-sanity-check  R
  * qemu  R
  * qemu-sanity-check  R
* kf5-baloo PA
  * plasma-workspace  R
* kf5-frameworkintegration PA
  * plasma-breeze  R
* kf5-kactivities PA
  * kde-cli-tools  R
  * kf5-kactivities-stats  R
  * kf5-plasma  R
  * kwin  R
  * okular  R OLD
  * plasma-workspace  R
* kf5-kactivities-stats PA
  * plasma-workspace  R
* kf5-karchive PA
  * kf5-kdoctools  R
  * kf5-kemoticons  R
  * kf5-kfilemetadata  R
  * kf5-khtml  R
  * kf5-kiconthemes  R
  * kf5-kio  R
  * kf5-knewstuff  R
  * kf5-kpackage  R
  * kf5-ktexteditor  R
  * kf5-plasma  R
  * okular  R OLD
* kf5-kauth PA
  * kf5-kconfigwidgets  R
  * libksysguard  R
  * plasma-breeze  R
* kf5-kbookmarks PA
  * kf5-kio  R
  * okular  R OLD
* kf5-kcmutils PA
  * kaccounts-integration  R OLD
  * kde-cli-tools  R
  * kde-connect  R
  * kf5-kactivities  R
  * kscreenlocker  R
  * kwin  R
  * plasma-breeze  R
  * plasma-workspace  R
* kf5-kcompletion PA
  * kf5-kdelibs4support  R
  * kf5-kdesignerplugin  R
  * kf5-kio  R
  * kf5-knewstuff  R
  * kf5-knotifyconfig  R
  * kf5-ktextwidgets  R
  * kwin  R
  * libksysguard  R
  * okular  R OLD
  * plasma-breeze  R
* kf5-kconfigwidgets PA
  * kde-connect  R
  * kf5-frameworkintegration  R
  * kf5-frameworkintegration-devel  R
  * kf5-kbookmarks  R
  * kf5-kcmutils  R
  * kf5-kcmutils-devel  R
  * kf5-kdelibs4support  R
  * kf5-kdesignerplugin  R
  * kf5-kiconthemes  R
  * kf5-kio  R
  * kf5-knotifyconfig  R
  * kf5-ktextwidgets  R
  * kf5-kwallet  R
  * kf5-kxmlgui  R
  * kf5-plasma  R
  * kwin  R
  * libksysguard  R
  * okular  R OLD
* kf5-kcrash PA
  * kf5-baloo  R
  * kf5-kded  R
  * kf5-kdelibs4support  R
  * kf5-kglobalaccel  R
  * kf5-kinit  R
  * kf5-kio  R
  * kf5-kservice  R
  * kscreenlocker  R
  * kwin  R
  * okular  R OLD
  * plasma-workspace  R
* kf5-kdeclarative PA
  * kaccounts-integration  R OLD
  * kde-cli-tools  R
  * kf5-kactivities  R
  * kf5-kcmutils  R
  * kf5-plasma  R
  * kf5-purpose  R
  * kscreenlocker  R
  * kwin  R
  * plasma-workspace  R
* kf5-kded PA
  * kf5-kdelibs4support  R
  * plasma-workspace  R
* kf5-kdelibs4support PA
  * kde-cli-tools  R
  * kscreenlocker  R
  * plasma-workspace  R
* kf5-kdesignerplugin PA
  * kf5-kdelibs4support  R
* kf5-kdesu PA
  * kde-cli-tools  R
  * kf5-plasma  R
  * plasma-workspace  R
* kf5-kdewebkit PA
  * plasma-workspace  R
* kf5-kdoctools PA
  * kde-connect  R
  * kde-l10n  R
  * kf5-kconfigwidgets  R
  * kf5-kded  R
  * kf5-kdelibs4support  R
  * kf5-kdesignerplugin  R
  * kf5-kinit  R
  * kf5-kio  R
  * kf5-kjs  R
  * kf5-kjsembed  R
  * kf5-kpackage  R
  * kf5-kservice  R
  * kf5-kwallet  R
  * kf5-plasma  R
  * kwin  R
  * okular  R OLD
  * plasma-workspace  R
* kf5-kemoticons PA
  * kf5-kdelibs4support  R
* kf5-kfilemetadata PA
  * kf5-baloo  R
* kf5-kglobalaccel PA
  * kf5-kactivities  R
  * kf5-kdeclarative  R
  * kf5-kdelibs4support  R
  * kf5-khtml  R
  * kf5-kxmlgui  R
  * kf5-plasma  R
  * kscreenlocker  R
  * kwin  R
  * libksysguard  R
  * plasma-workspace  R
* kf5-kholidays PA
  * plasma-workspace  R
* kf5-khtml PA
  * okular  R OLD
* kf5-kiconthemes PA
  * kaccounts-integration  R OLD
  * kde-cli-tools  R
  * kde-connect  R
  * kf5-frameworkintegration  R
  * kf5-frameworkintegration-devel  R
  * kf5-kbookmarks  R
  * kf5-kcmutils  R
  * kf5-kdeclarative  R
  * kf5-kdelibs4support  R
  * kf5-kdesignerplugin  R
  * kf5-khtml  R
  * kf5-kio  R
  * kf5-knewstuff  R
  * kf5-kparts  R
  * kf5-ktexteditor  R
  * kf5-ktextwidgets  R
  * kf5-kwallet  R
  * kf5-kxmlgui  R
  * kf5-plasma  R
  * kwin  R
  * libksysguard  R
  * okular  R OLD
* kf5-kidletime PA
  * kf5-baloo  R
  * kscreenlocker  R
  * kwin  R
  * plasma-workspace  R
* kf5-kinit PA
  * kde-cli-tools  R
  * kf5-kio  R
  * kwin  R
  * plasma-workspace  R
* kf5-kio PA
  * kaccounts-integration  R OLD
  * kde-connect  R
  * kdegraphics-mobipocket  R OLD
  * kf5-baloo  R
  * kf5-frameworkintegration  R
  * kf5-kactivities  R
  * kf5-kdeclarative  R
  * kf5-kdelibs4support  R
  * kf5-kdesignerplugin  R
  * kf5-kdewebkit  R
  * kf5-khtml  R
  * kf5-kinit  R
  * kf5-knewstuff  R
  * kf5-knotifyconfig  R
  * kf5-kparts  R
  * kf5-krunner  R
  * kf5-ktexteditor  R
  * kf5-kxmlrpcclient  R
  * kf5-plasma  R
  * kf5-purpose  R
  * kwin  R
  * libksysguard  R
  * okular  R OLD
* kf5-kitemmodels PA
* kf5-kjobwidgets PA
  * kf5-kdewebkit  R
  * kf5-kio  R
  * kf5-kparts  R
* kf5-kjs PA
  * kf5-khtml  R
  * kf5-kjsembed  R
  * okular  R OLD
* kf5-kjsembed PA
  * plasma-workspace  R
* kf5-knewstuff PA
  * kf5-frameworkintegration  R
  * kwin  R
  * plasma-workspace  R
* kf5-knotifications PA
  * kde-connect  R
  * kf5-frameworkintegration  R
  * kf5-kdelibs4support  R
  * kf5-khtml  R
  * kf5-kio  R
  * kf5-knotifyconfig  R
  * kf5-kparts  R
  * kf5-kwallet  R
  * kf5-plasma  R
  * kf5-purpose  R
  * kwin  R
* kf5-knotifyconfig PA
  * plasma-workspace  R
* kf5-kpackage PA
  * kf5-frameworkintegration  R
  * kf5-kcmutils  R
  * kf5-kdeclarative  R
  * kf5-plasma  R
  * kf5-plasma-devel  R
  * plasma-breeze  R
* kf5-kparts PA
  * kf5-kdelibs4support  R
  * kf5-kdewebkit  R
  * kf5-khtml  R
  * kf5-ktexteditor  R
  * kf5-plasma  R
  * okular  R OLD
* kf5-kpeople PA
  * plasma-workspace  R
* kf5-kplotting PA
  * kf5-kdesignerplugin  R
* kf5-kpty PA
  * kf5-kdesu  R
  * okular  R OLD
* kf5-krunner PA
  * plasma-workspace  R
* kf5-kservice PA
  * kf5-kactivities  R
  * kf5-kcmutils  R
  * kf5-kcmutils-devel  R
  * kf5-kded  R
  * kf5-kdelibs4support  R
  * kf5-kdesu  R
  * kf5-kdewebkit  R
  * kf5-kemoticons  R
  * kf5-kemoticons-devel  R
  * kf5-kglobalaccel  R
  * kf5-kinit  R
  * kf5-kio  R
  * kf5-knewstuff  R
  * kf5-kparts  R
  * kf5-kpeople  R
  * kf5-krunner  R
  * kf5-ktextwidgets  R
  * kf5-kwallet  R
  * kf5-plasma  R
  * kf5-plasma-devel  R
  * kwin  R
  * libksysguard  R
  * plasma-breeze  R
* kf5-ktexteditor PA
  * plasma-workspace  R
* kf5-ktextwidgets PA
  * kf5-kdelibs4support  R
  * kf5-kdesignerplugin  R
  * kf5-khtml  R
  * kf5-kio  R
  * kf5-knewstuff  R
  * kf5-kparts  R
  * kf5-kxmlgui  R
  * kwin  R
  * plasma-workspace  R
* kf5-kunitconversion PA
  * kf5-kdelibs4support  R
* kf5-kwallet PA
  * kaccounts-integration  R OLD
  * kf5-kdewebkit  R
  * kf5-khtml  R
  * kf5-kio  R
  * okular  R OLD
  * plasma-workspace  R
  * subversion  R OLD
* kf5-kwayland PA
  * kde-connect  R
  * kf5-plasma  R
  * kscreenlocker  R
  * kwin  R
  * libkscreen-qt5  R
  * plasma-breeze  R
  * plasma-workspace  R
* kf5-kxmlgui PA
  * kf5-kactivities  R
  * kf5-kbookmarks  R
  * kf5-kcmutils  R
  * kf5-kdelibs4support  R
  * kf5-kdesignerplugin  R
  * kf5-khtml  R
  * kf5-kio  R
  * kf5-knewstuff  R
  * kf5-knotifyconfig  R
  * kf5-kparts  R
  * kf5-plasma  R
* kf5-kxmlrpcclient PA
  * plasma-workspace  R
* kf5-networkmanager-qt PA
  * plasma-workspace  R
* kf5-plasma PA
  * kf5-krunner  R
  * kscreenlocker  R
  * kwin  R
  * libksysguard  R
  * plasma-breeze  R
  * plasma-workspace  R
* kf5-prison PA
  * plasma-workspace  R
* kf5-purpose PA
  * okular  R OLD
* kf5-syntax-highlighting PA
  * kf5-ktexteditor  R
* koji PA
  * koji  R
  * libabigail  R
* kscreenlocker PA
  * kwin  R
  * plasma-workspace  R
* kwin PA
  * plasma-workspace  R
* lcov PA
  * libcacard  R
* libabigail PA
  * efivar  R
* libbsd PA
  * plasma-workspace  R
* libcacard PA
  * qemu  R
  * spice  R
* libdmtx PA
  * kf5-prison  R
* libfakekey PA
  * kde-connect  R
* libgit2 PA
  * kf5-ktexteditor  R
* libgit2_0.27 PA
  * kf5-ktexteditor  R
* libinput PA
  * efl  R OLD
  * kwin  R
  * qt5-qtbase  R OLD
  * qt5-qtwayland  R OLD
  * weston  R OLD
  * xorg-x11-drv-libinput  R OLD
* libiscsi PA
  * libvirt  R
  * qemu  R
* libkscreen-qt5 PA
  * plasma-workspace  R
* libksysguard PA
  * plasma-workspace  R
* libndp PA
  * NetworkManager  R
* libqalculate PA
  * plasma-workspace  R
* libslirp PA
  * qemu  R
* libsmi PA
  * wireshark  R
* libsoup PA
  * geoclue2  R OLD
  * gnome-online-accounts  R OLD
  * gssdp  R OLD
  * gupnp  R OLD
  * gvfs  R OLD
  * inkscape  R OLD
  * libappstream-glib  R OLD
  * libgdata  R OLD
  * libgrss  R OLD
  * libosinfo  R OLD
  * osinfo-db-tools  R OLD
  * rest  R OLD
  * tracker  R OLD
  * uhttpmock  R OLD
  * webkit2gtk3  R OLD
* libteam PA
  * NetworkManager  R
* libvirt PA
  * systemtap  R
* libXres PA
  * libksysguard  R
  * xorg-x11-server  R OLD
* libzip PA
  * ebook-tools  R OLD
  * okular  R OLD
* linux-firmware PA
* mariadb-connector-c PA
  * apr-util  R OLD
  * bind  R OLD
  * cyrus-sasl  R OLD
  * exim  R OLD
  * net-snmp  R OLD
  * postfix  R
  * qt  R OLD
  * qt3  R OLD
  * qt5-qtbase  R OLD
  * sphinx  R OLD
* mobile-broadband-provider-info PA
  * NetworkManager  R
* mokutil PA
* mono PA
  * graphviz  R OLD
  * gtk-sharp2  R
  * mono  R
  * avahi  R OLD
  * gtk-sharp2  R
  * mono  R
  * avahi  R OLD
  * gtk-sharp2  R
* mozilla-filesystem PA
* netcf PA
  * libvirt  R
* NetworkManager PA
  * kf5-networkmanager-qt  R
  * libproxy  R OLD
  * qt-mobility  R
  * tracker  R OLD
* ocaml-findlib PA
  * xen  R
* ocaml-labltk PA
  * ocaml-findlib  R
* ocaml-ocamlbuild PA
  * ocaml-findlib  R
* opensc PA
  * libcacard  R
* openwsman PA
  * libvirt  R
* osinfo-db PA
  * libosinfo  R OLD
* PackageKit-Qt PA
  * kf5-frameworkintegration  R
* pangox-compat PA
  * caja  R
* pcsc-lite-asekey PA
* pcsc-lite-ccid PA
* perl-Acme-Alien-DontPanic PA
  * perl-Alien-Base-ModuleBuild  R
  * perl-Alien-Build  R
  * perl-FFI-Platypus  R OLD
* perl-Alien-Base-ModuleBuild PA
  * perl-Acme-Alien-DontPanic  R
  * perl-Alien-Build  R
* perl-Alien-Build PA
  * perl-Acme-Alien-DontPanic  R
  * perl-Alien-Base-ModuleBuild  R
  * perl-Alien-FFI  R OLD
  * perl-Alien-Libxml2  R OLD
  * perl-Alien-cmake3  R OLD
  * perl-Alien-pkgconf  R OLD
  * perl-FFI-Platypus  R OLD
* perl-Archive-Tar PA
  * perl  R OLD
  * perl-Alien-Build  R
  * perl-Archive-Any-Lite  R OLD
  * perl-Archive-Extract  R OLD
  * perl-Archive-Extract-tar-Archive-Tar  R
  * perl-Archive-Extract-tbz-Archive-Tar-IO-Uncompress-Bunzip2  R
  * perl-Archive-Extract-tgz-Archive-Tar-Compress-Zlib  R
  * perl-Archive-Extract-tgz-Archive-Tar-IO-Zlib  R
  * perl-Archive-Extract-txz-Archive-Tar-IO-Uncompress-UnXz  R
  * perl-CPAN  R OLD
  * perl-Module-Build  R OLD
  * perl-Module-CPANTS-Analyse  R OLD
  * perl-TAP-Harness-Archive  R OLD
  * publican  R OLD
  * samba  R OLD
* perl-boolean PA
  * perl-YAML-PP  R
* perl-Devel-PPPort PA
  * perl  R OLD
  * perl-Hash-FieldHash  R OLD
  * perl-Module-Build-XSUtil  R OLD
  * perl-Module-Install  R OLD
  * perl-Mouse  R OLD
  * perl-Test-Apocalypse  R OLD
* perl-ExtUtils-CppGuess PA
  * perl-Inline-CPP  R
  * perl-Inline-Module  R
* perl-File-Share PA
* perl-Inline PA
  * perl-Alien-Base-ModuleBuild  R
  * perl-Inline-C  R
  * perl-Inline-CPP  R
  * perl-Inline-Filters  R
  * perl-Inline-Module  R
* perl-Inline-C PA
  * perl-Alien-Base-ModuleBuild  R
  * perl-Inline-CPP  R
  * perl-Inline-Filters  R
  * perl-Inline-Module  R
* perl-Inline-CPP PA
  * perl-Alien-Base-ModuleBuild  R
* perl-Inline-Files PA
  * perl-Inline  R
* perl-Inline-Filters PA
  * perl-Inline-CPP  R
* perl-Inline-Module PA
* perl-JSON-Color PA
  * perl-XXX  R
* perl-Pegex PA
  * perl-Inline-C  R
* perl-PerlIO-gzip PA
* perl-Scalar-List-Utils PA
  * autogen  R OLD
  * latexmk  R OLD
  * perl  R OLD
  * perl-Alien-Base-ModuleBuild  R
  * perl-Alien-Build  R
  * perl-AnyEvent  R OLD
  * perl-B-Hooks-EndOfScope  R OLD
  * perl-B-Utils  R OLD
  * perl-CGI-Application  R OLD
  * perl-CPAN-Changes  R OLD
  * perl-CPAN-Meta  R OLD
  * perl-CPAN-Meta-YAML  R OLD
  * perl-Capture-Tiny  R OLD
  * perl-Class-Load  R OLD
  * perl-Clone  R OLD
  * perl-Clone-Choose  R OLD
  * perl-Compress-Raw-Bzip2  R OLD
  * perl-Compress-Raw-Lzma  R OLD
  * perl-Config-Any  R OLD
  * perl-Const-Fast  R OLD
  * perl-Contextual-Return  R OLD
  * perl-Coro  R OLD
  * perl-Cpanel-JSON-XS  R OLD
  * perl-Crypt-CBC  R OLD
  * perl-DBD-SQLite  R OLD
  * perl-DBI  R OLD
  * perl-DBM-Deep  R OLD
  * perl-Data-Dumper  R OLD
  * perl-Data-OptList  R OLD
  * perl-Data-Perl  R OLD
  * perl-Data-Visitor  R OLD
  * perl-DateTime  R OLD
  * perl-DateTime-Format-Builder  R OLD
  * perl-DateTime-Locale  R OLD
  * perl-DateTime-TimeZone  R OLD
  * perl-Declare-Constraints-Simple  R OLD
  * perl-Devel-Cycle  R OLD
  * perl-Devel-Declare  R OLD
  * perl-Devel-FindPerl  R OLD
  * perl-Devel-OverloadInfo  R OLD
  * perl-Devel-PartialDump  R OLD
  * perl-Devel-Size  R OLD
  * perl-Devel-StackTrace  R OLD
  * perl-Encode  R OLD
  * perl-Error  R OLD
  * perl-Eval-Closure  R OLD
  * perl-Exception-Class  R OLD
  * perl-FFI-Platypus  R OLD
  * perl-File-Find-Object  R OLD
  * perl-File-Slurp  R OLD
  * perl-File-Temp  R OLD
  * perl-Function-Parameters  R OLD
  * perl-Future  R OLD
  * perl-GTop  R OLD
  * perl-Getopt-Long-Descriptive  R OLD
  * perl-Glib  R OLD
  * perl-HTML-Template  R OLD
  * perl-HTML-Tree  R OLD
  * perl-Hash-FieldHash  R OLD
  * perl-Hash-Merge  R OLD
  * perl-Hash-Util-FieldHash-Compat  R OLD
  * perl-IO-All  R OLD
  * perl-IO-Async  R OLD
  * perl-IO-Compress  R OLD
  * perl-IO-HTML  R OLD
  * perl-IO-Pipely  R OLD
  * perl-IO-Socket-SSL  R OLD
  * perl-IPC-Run  R OLD
  * perl-IPC-System-Simple  R OLD
  * perl-JSON  R OLD
  * perl-JSON-MaybeXS  R OLD
  * perl-JSON-PP  R OLD
  * perl-LWP-MediaTypes  R OLD
  * perl-List-MoreUtils  R OLD
  * perl-List-MoreUtils-XS  R OLD
  * perl-List-SomeUtils  R OLD
  * perl-Locale-Maketext  R OLD
  * perl-MCE  R OLD
  * perl-Module-CPANTS-Analyse  R OLD
  * perl-Module-CoreList  R OLD
  * perl-Mojolicious  R OLD
  * perl-Moo  R OLD
  * perl-MooX-Types-MooseLike  R OLD
  * perl-Moose  R OLD
  * perl-Moose-Autobox  R OLD
  * perl-MooseX-ConfigFromFile  R OLD
  * perl-MooseX-Getopt  R OLD
  * perl-MooseX-GlobRef  R OLD
  * perl-MooseX-InsideOut  R OLD
  * perl-MooseX-Types  R OLD
  * perl-MooseX-Types-Stringlike  R OLD
  * perl-Mouse  R OLD
  * perl-MouseX-Types  R OLD
  * perl-Object-Deadly  R OLD
  * perl-PDF-API2  R OLD
  * perl-PHP-Serialization  R OLD
  * perl-POE  R OLD
  * perl-POE-Test-Loops  R OLD
  * perl-PPI  R OLD
  * perl-PPIx-QuoteLike  R OLD
  * perl-PPIx-Regexp  R OLD
  * perl-PPIx-Utilities  R OLD
  * perl-Package-Anon  R OLD
  * perl-Package-DeprecationManager  R OLD
  * perl-Package-Generator  R OLD
  * perl-Package-Stash  R OLD
  * perl-Package-Stash-XS  R OLD
  * perl-Params-Classify  R OLD
  * perl-Params-Coerce  R OLD
  * perl-Params-Util  R OLD
  * perl-Params-Validate  R OLD
  * perl-Params-ValidationCompiler  R OLD
  * perl-Path-Class  R OLD
  * perl-PathTools  R OLD
  * perl-Pegex  R
  * perl-Perl-Critic  R OLD
  * perl-Perl-Critic-Pulp  R OLD
  * perl-Perl-MinimumVersion  R OLD
  * perl-Perl-PrereqScanner  R OLD
  * perl-Perl-Version  R OLD
  * perl-PkgConfig-LibPkgConf  R OLD
  * perl-Pod-MinimumVersion  R OLD
  * perl-Pod-Readme  R OLD
  * perl-Ref-Util  R OLD
  * perl-Return-Type  R OLD
  * perl-SQL-Statement  R OLD
  * perl-SUPER  R OLD
  * perl-Scope-Upper  R OLD
  * perl-Sereal  R
  * perl-Sereal-Decoder  R
  * perl-Sereal-Encoder  R
  * perl-Software-License-CCpack  R OLD
  * perl-Specio  R OLD
  * perl-Spellunker  R OLD
  * perl-Spiffy  R OLD
  * perl-Statistics-Basic  R OLD
  * perl-Storable  R OLD
  * perl-Struct-Dumb  R OLD
  * perl-Sub-Exporter-ForMethods  R OLD
  * perl-Sub-Identify  R OLD
  * perl-Sub-Install  R OLD
  * perl-Sub-Quote  R OLD
  * perl-Syntax-Highlight-Engine-Kate  R OLD
  * perl-Task-Weaken  R OLD
  * perl-Template-Toolkit  R OLD
  * perl-Term-Table  R OLD
  * perl-Test-Base  R OLD
  * perl-Test-CheckDeps  R OLD
  * perl-Test-CheckManifest  R OLD
  * perl-Test-CleanNamespaces  R OLD
  * perl-Test-Deep  R OLD
  * perl-Test-FailWarnings  R OLD
  * perl-Test-Identity  R OLD
  * perl-Test-Kwalitee  R OLD
  * perl-Test-Memory-Cycle  R OLD
  * perl-Test-MockModule  R OLD
  * perl-Test-MockObject  R OLD
  * perl-Test-MockRandom  R OLD
  * perl-Test-Object  R OLD
  * perl-Test-Refcount  R OLD
  * perl-Test-Simple  R OLD
  * perl-Test-Taint  R OLD
  * perl-Test-Valgrind  R OLD
  * perl-Test-Vars  R OLD
  * perl-Test2-Suite  R OLD
  * perl-TestML  R
  * perl-Text-Haml  R OLD
  * perl-Text-ParseWords  R OLD
  * perl-Thread-Queue  R OLD
  * perl-Tie-RefHash-Weak  R OLD
  * perl-Tie-ToObject  R OLD
  * perl-Try-Tiny  R OLD
  * perl-Type-Tie  R OLD
  * perl-Type-Tiny  R OLD
  * perl-Types-Path-Tiny  R OLD
  * perl-UNIVERSAL-can  R OLD
  * perl-UNIVERSAL-isa  R OLD
  * perl-URI  R OLD
  * perl-Unicode-UTF8  R OLD
  * perl-Validation-Class  R OLD
  * perl-XML-LibXML  R OLD
  * perl-XML-Simple  R OLD
  * perl-XML-Twig  R OLD
  * perl-XML-XPath  R OLD
  * perl-YAML  R OLD
  * perl-YAML-LibYAML  R OLD
  * perl-YAML-PP  R
  * perl-YAML-Tiny  R OLD
  * perl-autobox  R OLD
  * perl-autodie  R OLD
  * perl-constant-defer  R OLD
  * perl-indirect  R OLD
  * perl-libwww-perl  R OLD
  * perl-namespace-autoclean  R OLD
  * perl-pod2pdf  R OLD
  * perl-podlinkcheck  R OLD
  * perl-prefork  R OLD
  * perl-threads-shared  R OLD
  * perl-version  R OLD
  * po4a  R OLD
  * publican  R OLD
* perl-Sereal PA
  * perl-Devel-Cover  R OLD
  * perl-MCE  R OLD
* perl-Sereal-Decoder PA
  * perl-Devel-Cover  R OLD
  * perl-IO-Async  R OLD
  * perl-Sereal  R
  * perl-Sereal-Encoder  R
* perl-Sereal-Encoder PA
  * perl-Devel-Cover  R OLD
  * perl-IO-Async  R OLD
  * perl-Sereal  R
  * perl-Sereal-Decoder  R
* perl-TestML PA
  * perl-Inline  R
* perl-XXX PA
  * perl-Inline-Module  R
  * perl-Pegex  R
  * perl-TestML  R
* perl-YAML-PP PA
  * perl-Pegex  R
  * perl-XXX  R
* phonon-qt4 PA
  * kdelibs  R
  * kdelibs-devel  R
* plasma-breeze PA
  * kwin  R
* plasma-workspace PA
  * kde-cli-tools  R
* polkit-qt PA
  * kdelibs  R
* postfix PA
  * php  R OLD
  * quilt  R OLD
* ppp PA
  * NetworkManager  R
* pps-tools PA
  * gpsd  R
* proj PA
  * qt-mobility  R
* pyOpenSSL PA
* pyserial PA
  * gpsd  R
* python-cffi PA
* python-cryptography PA
* python-kerberos PA
* python-pycparser PA
* python-pycryptodomex PA
* python-requests-kerberos PA
* qemu PA
  * libvirt  R
  * qemu  R
* qemu-sanity-check PA
  * qemu  R
  * qemu-sanity-check  R
* qt5-qtvirtualkeyboard PA
  * kwin  R
* qt-mobility PA
  * qtwebkit  R
* qtsoap PA
  * herqq  R
* qtwebkit PA
  * kdelibs  R
* radvd PA
  * libvirt  R
* sblim-sfcc PA
* scrub PA
  * libvirt  R
* selinux-policy PA
  * mariadb  R OLD
  * bind  R OLD
  * memcached  R OLD
  * selinux-policy-devel  R
  * bind  R OLD
  * sssd  R OLD
* sheepdog PA
  * libvirt  R
* spice PA
  * qemu  R
* spice-protocol PA
  * qemu  R
  * spice  R
* sysfsutils PA
  * bridge-utils  R
* systemtap PA
  * gcc  R OLD
  * glib2  R
  * glibc  R OLD
  * java-11-openjdk  R OLD
  * libvirt  R
  * mariadb  R OLD
  * nodejs  R OLD
  * perl  R OLD
  * php  R OLD
  * postgresql  R OLD
  * python27  R OLD
  * python3  R OLD
  * qemu  R
  * ruby  R OLD
  * sssd  R OLD
  * tcl  R OLD
  * xorg-x11-server  R OLD
  * qemu  R
* usbredir PA
  * qemu  R
* util-linux PA
  * bcache-tools  R OLD
  * btrfs-progs  R OLD
  * cryptsetup  R OLD
  * e2fsprogs  R OLD
  * efl  R OLD
  * grubby  R
  * libblockdev  R OLD
  * libvirt  R
  * lvm2  R OLD
  * nfs-utils  R OLD
  * parted  R OLD
  * qt-mobility  R
  * sanlock  R OLD
  * systemd  R OLD
  * usermode  R OLD
  * volume_key  R OLD
  * xfsprogs  R OLD
  * efl  R OLD
  * glib2  R
  * iscsi-initiator-utils  R OLD
  * libblockdev  R OLD
  * nfs-utils  R OLD
  * systemd  R OLD
  * udisks2  R OLD
  * libdnf  R OLD
  * NetworkManager  R
  * apr  R OLD
  * apr-util  R OLD
  * babeltrace  R OLD
  * bcache-tools  R OLD
  * btrfs-progs  R OLD
  * cryptsetup  R OLD
  * e2fsprogs  R OLD
  * gdisk  R OLD
  * glusterfs  R OLD
  * gupnp  R OLD
  * infinipath-psm  R OLD
  * lash  R OLD
  * libSM  R OLD
  * libappstream-glib  R OLD
  * libblockdev  R OLD
  * libpsm2  R OLD
  * ndctl  R OLD
  * nfs-utils  R OLD
  * ntfs-3g  R OLD
  * pacemaker  R OLD
  * parted  R OLD
  * python3  R OLD
  * samba  R OLD
  * sanlock  R OLD
  * sssd  R OLD
  * tracker  R OLD
  * wget  R OLD
  * xapian-core  R OLD
  * xen  R
  * xen-devel  R
  * xfsprogs  R OLD
  * beakerlib  R OLD
  * breeze-icon-theme  R OLD
  * brlapi  R
  * compat-openssl10  R OLD
  * cyrus-sasl  R OLD
  * dracut  R OLD
  * execstack  R OLD
  * fakeroot  R OLD
  * fedora-logos  R OLD
  * gdm  R OLD
  * glibc  R OLD
  * grubby  R
  * json-c  R OLD
  * jsoncpp  R OLD
  * libblockdev-part  R
  * libblockdev-swap  R
  * libkcapi  R OLD
  * libvirt  R
  * nfs-utils  R OLD
  * ocaml  R OLD
  * openssh  R OLD
  * openssl  R OLD
  * os-prober  R OLD
  * perl-Graphics-TIFF  R OLD
  * policycoreutils  R OLD
  * postgresql  R OLD
  * quilt  R OLD
  * stunnel  R OLD
  * suitesparse  R OLD
  * systemd  R OLD
  * udisks2  R OLD
  * usermode  R OLD
  * xfsprogs  R OLD
  * xmlto  R OLD
* virglrenderer PA
  * qemu  R
* vte291 PA
  * qemu  R
* wireshark PA
  * libvirt  R
* xcb-util-cursor PA
  * kwin  R
* xen PA
  * qemu  R
* yajl PA
  * libvirt  R
  * xen  R
* zfs-fuse PA
  * libvirt  R
## SOURCE DEPENDENCIES REMOVED
Total Sources Removed: 0
