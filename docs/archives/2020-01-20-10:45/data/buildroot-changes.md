# Buildroot Source Changes
Checked on 2020-01-20-10:45

Last time there was a change was [2020-01-13-09:30](https://github.com/minimization/square1-results/blob/master/docs/archives/2020-01-13-09:30/data/buildroot-changes.md)
## SOURCE DEPENDENCIES ADDED
Total New Sources Added: 381

PA = Package Added  R = Requires Added Package  OLD = Not New
* accountsservice PA
  * gdm  R
* appstream PA
  * extra-cmake-modules  R OLD
  * kf5-kirigami2  R
  * kf5-frameworkintegration  R
  * plasma-workspace  R
* appstream-data PA
* atril PA
* attica PA
  * kdelibs  R
* babel PA
* basesystem PA
* beakerlib PA
  * chkconfig  R
* boost169 PA
* botan2 PA
  * qca  R
* breeze-icon-theme PA
* caja PA
  * atril  R
* catdoc PA
  * kf5-kfilemetadata  R
* chkconfig PA
* chmlib PA
  * okular  R
* cifs-utils PA
  * sssd  R
* cln PA
  * libqalculate  R
* closure-compiler PA
* copy-jdk-configs PA
* crypto-policies PA
* cups-filters PA
* dbus-broker PA
* desktop-backgrounds PA
  * plasma-workspace  R
* ding-libs PA
  * sssd  R
  * sssd  R
  * gssproxy  R
  * sssd  R
* dnf PA
  * dnf  R
  * dnf-plugins-core  R
* dnf-plugins-core PA
* dracut PA
* dwz PA
* ebook-tools PA
  * kf5-kfilemetadata  R
  * okular  R
* editorconfig PA
  * kf5-ktexteditor  R
* efi-rpm-macros PA
* emacs-auctex PA
* f31-backgrounds PA
* fdupes PA
  * generic-logos  R
  * kf5-khtml  R
* fedora-logos PA
* filesystem PA
  * basesystem  R
  * bash  R OLD
  * caja  R
  * color-filesystem  R OLD
  * dracut  R
  * gawk  R OLD
  * initscripts  R
  * kde-filesystem  R OLD
  * rpm-mpi-hooks  R OLD
  * xdg-user-dirs  R OLD
* fpc-srpm-macros PA
* fuse3 PA
  * fuse-sshfs  R
  * fuse-sshfs  R
* fuse-sshfs PA
* gdm PA
  * sssd  R
* generic-logos PA
* generic-release PA
* ghc-srpm-macros PA
* gl-manpages PA
* gnat-srpm-macros PA
* gnome-doc-utils PA
  * PackageKit  R
* go-rpm-macros PA
* gpsd PA
  * plasma-workspace  R
* grantlee PA
  * kdelibs  R
* gssproxy PA
* herqq PA
  * kdelibs  R
* hscolour PA
* initscripts PA
* ipcalc PA
* kaccounts-integration PA
  * kf5-purpose  R
* kde-cli-tools PA
* kde-connect PA
  * kf5-purpose  R
* kdecoration PA
  * kwin  R
  * plasma-breeze  R
* kdegraphics-mobipocket PA
  * okular  R
* kdelibs PA
  * plasma-breeze  R
* kde-settings PA
  * kdelibs  R
  * kf5-kdelibs4support  R
* kf5-attica PA
  * kf5-knewstuff  R
  * kf5-kxmlgui  R
* kf5-baloo PA
  * plasma-workspace  R
* kf5-frameworkintegration PA
  * plasma-breeze  R
* kf5-kactivities PA
  * kde-cli-tools  R
  * kf5-kactivities-stats  R
  * kf5-plasma  R
  * kwin  R
  * okular  R
  * plasma-workspace  R
* kf5-kactivities-stats PA
  * plasma-workspace  R
* kf5-kbookmarks PA
  * kf5-kio  R
  * okular  R
* kf5-kcmutils PA
  * kaccounts-integration  R
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
  * okular  R
  * plasma-breeze  R
* kf5-kdeclarative PA
  * kaccounts-integration  R
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
  * okular  R
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
  * kaccounts-integration  R
  * kde-connect  R
  * kdegraphics-mobipocket  R
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
  * okular  R
* kf5-kirigami2 PA
  * kf5-plasma  R
  * kf5-purpose  R
  * okular  R
* kf5-kitemmodels PA
* kf5-kjobwidgets PA
  * kf5-kdewebkit  R
  * kf5-kio  R
  * kf5-kparts  R
* kf5-kjs PA
  * kf5-khtml  R
  * kf5-kjsembed  R
  * okular  R
* kf5-kjsembed PA
  * plasma-workspace  R
* kf5-knewstuff PA
  * kf5-frameworkintegration  R
  * kwin  R
  * plasma-workspace  R
* kf5-knotifyconfig PA
  * plasma-workspace  R
* kf5-kpackage PA
  * kf5-frameworkintegration  R
  * kf5-kcmutils  R
  * kf5-kdeclarative  R
  * kf5-plasma  R
  * plasma-breeze  R
* kf5-kparts PA
  * kf5-kdelibs4support  R
  * kf5-kdewebkit  R
  * kf5-khtml  R
  * kf5-ktexteditor  R
  * kf5-plasma  R
  * okular  R
* kf5-kpeople PA
  * plasma-workspace  R
* kf5-kplotting PA
  * kf5-kdesignerplugin  R
* kf5-kpty PA
  * kf5-kdesu  R
  * okular  R
* kf5-krunner PA
  * plasma-workspace  R
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
* kf5-libkexiv2 PA
  * okular  R
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
  * okular  R
* kf5-solid PA
  * kf5-baloo  R
  * kf5-kio  R
  * kf5-krunner  R
  * kf5-plasma  R
* kf5-sonnet PA
  * kf5-kdesignerplugin  R
  * kf5-khtml  R
  * kf5-ktexteditor  R
  * kf5-ktextwidgets  R
* kf5-syntax-highlighting PA
  * kf5-ktexteditor  R
* kf5-threadweaver PA
  * kf5-krunner  R
  * okular  R
  * plasma-workspace  R
* kscreenlocker PA
  * kwin  R
  * plasma-workspace  R
* kwin PA
  * plasma-workspace  R
* libaccounts-glib PA
  * kaccounts-integration  R
  * kf5-purpose  R
  * libaccounts-qt  R
* libaccounts-qt PA
  * kaccounts-integration  R
  * kf5-purpose  R
* libbsd PA
  * plasma-workspace  R
* libcomps PA
  * dnf  R
* libdmtx PA
  * kf5-prison  R
* libdnf PA
  * PackageKit  R
  * dnf  R
  * dnf  R
* libfakekey PA
  * kde-connect  R
* libgdiplus PA
* libgit2 PA
  * kf5-ktexteditor  R
* libgit2_0.27 PA
  * kf5-ktexteditor  R
* libgnomekbd PA
  * xapps  R
* libicns PA
  * fedora-logos  R
  * generic-logos  R
* libkscreen-qt5 PA
  * plasma-workspace  R
* libksysguard PA
  * plasma-workspace  R
* libmodulemd PA
  * dnf  R
  * libdnf  R
* libmodulemd1 PA
  * libdnf  R
  * dnf  R
  * libdnf  R
* libqalculate PA
  * plasma-workspace  R
* librepo PA
  * libdnf  R
* libsolv PA
  * libdnf  R
* libtomcrypt PA
* libupnp PA
  * kf5-solid  R
* libusbauth-configparser PA
  * usbauth-notifier  R
* libverto PA
  * gssproxy  R
  * krb5  R OLD
* libXfont2 PA
* libxklavier PA
  * libgnomekbd  R
* libXres PA
  * libksysguard  R
  * xorg-x11-server  R OLD
* libxshmfence PA
* linux-firmware PA
* Lmod PA
* logrotate PA
* lua-filesystem PA
  * Lmod  R
  * lua-json  R
* lua-json PA
  * Lmod  R
* lua-lpeg PA
  * lua-json  R
* lua-lunit PA
  * lua-json  R
  * lua-posix  R
* lua-posix PA
  * Lmod  R
  * copy-jdk-configs  R
* lua-term PA
  * Lmod  R
* mailcap PA
* mallard-rng PA
* mate-common PA
  * atril  R
  * caja  R
  * mate-desktop  R
* mate-desktop PA
  * caja  R
* mathjax PA
  * atril  R
  * xreader  R
* maven-javadoc-plugin PA
* media-player-info PA
  * kf5-solid  R
* mod_http2 PA
* nim-srpm-macros PA
* nodejs-ansi PA
  * nodejs-gauge  R
  * nodejs-npmlog  R OLD
* nodejs-are-we-there-yet PA
* nodejs-argparse PA
* nodejs-asap PA
  * nodejs-promise  R
* nodejs-better-assert PA
  * nodejs-character-parser  R
  * nodejs-promise  R
* nodejs-burrito PA
* nodejs-caller-callsite PA
* nodejs-callsite PA
* nodejs-character-parser PA
* nodejs-clone PA
  * nodejs-transformers  R
* nodejs-constantinople PA
* nodejs-css PA
  * nodejs-transformers  R
* nodejs-css-parse PA
  * nodejs-css  R
  * nodejs-css-stringify  R
* nodejs-css-stringify PA
  * nodejs-css  R
* nodejs-dateformat PA
* nodejs-delayed-stream PA
* nodejs-delegates PA
  * nodejs-are-we-there-yet  R
* nodejs-duplexer PA
* nodejs-ejs PA
  * nodeunit  R
* nodejs-end-of-stream PA
* nodejs-es6-weak-map PA
* nodejs-event-emitter PA
* nodejs-eventemitter2 PA
* nodejs-exit PA
  * nodejs-grunt  R OLD
  * nodejs-grunt-legacy-util  R
* nodejs-expect-dot-js PA
  * nodejs-ms  R
* nodejs-figures PA
  * nodejs-maxmin  R
* nodejs-fill-keys PA
  * nodejs-proxyquire  R
* nodejs-findup-sync PA
* nodejs-formatio PA
* nodejs-gauge PA
* nodejs-getobject PA
  * nodejs-grunt-legacy-util  R
* nodejs-grunt-known-options PA
* nodejs-grunt-legacy-log PA
* nodejs-grunt-legacy-log-utils PA
  * nodejs-grunt-legacy-log  R
* nodejs-grunt-legacy-util PA
* nodejs-gzip-size PA
  * nodejs-maxmin  R
* nodejs-has-unicode PA
  * nodejs-gauge  R
* nodejs-hooker PA
  * nodejs-grunt-legacy-log  R
  * nodejs-grunt-legacy-util  R
* nodejs-interpret PA
* nodejs-is-object PA
  * nodejs-fill-keys  R
* nodejs-lolex PA
* nodejs-lru-queue PA
* nodejs-maxmin PA
* nodejs-merge-descriptors PA
  * nodejs-fill-keys  R
* nodejs-module-not-found-error PA
  * nodejs-proxyquire  R
* nodejs-monocle PA
* nodejs-ms PA
* nodejs-next-tick PA
* nodejs-object-assign PA
  * nodejs-figures  R
* nodejs-package PA
* nodejs-path-parse PA
* nodejs-pretty-bytes PA
  * nodejs-maxmin  R
* nodejs-promise PA
  * nodejs-transformers  R
* nodejs-promises-aplus-tests PA
  * nodejs-promise  R
* nodejs-proxyquire PA
  * nodejs-readdirp  R
* nodejs-readdirp PA
  * nodejs-monocle  R
* nodejs-rechoir PA
* nodejs-samsam PA
  * nodejs-formatio  R
  * nodejs-sinon  R OLD
* nodejs-set-immediate-shim PA
  * nodejs-readdirp  R
* nodejs-source-map-support PA
* nodejs-sprintf-js PA
  * nodejs-argparse  R
* nodejs-temporary PA
  * nodejs-grunt-legacy-util  R
* nodejs-transformers PA
* nodejs-underscore-dot-string PA
  * nodejs-argparse  R
  * nodejs-grunt-legacy-log  R
  * nodejs-grunt-legacy-util  R
* nodejs-uri-path PA
* nodejs-util PA
* nodejs-with PA
* nodejs-yargs PA
* nodeunit PA
  * nodejs-clone  R
  * nodejs-findup-sync  R
  * nodejs-grunt-legacy-log  R
* ocaml-srpm-macros PA
* okular PA
* optipng PA
  * fedora-logos  R
* os-prober PA
* PackageKit PA
  * appstream  R
* PackageKit-Qt PA
  * kf5-frameworkintegration  R
* pangox-compat PA
  * caja  R
* perl-AnyEvent-BDB PA
* perl-BDB PA
  * perl-AnyEvent-BDB  R
  * perl-Coro  R OLD
* perl-bignum PA
* perl-Class-Iterator PA
  * perl-File-Find-Iterator  R
* perl-Compress-Bzip2 PA
* perl-Config-Perl-V PA
* perl-criticism PA
* perl-Curses PA
* perl-Date-ISO8601 PA
  * perl-DateTime-TimeZone-SystemV  R
  * perl-DateTime-TimeZone-Tzfile  R
* perl-DateTime-TimeZone-SystemV PA
  * perl-DateTime-TimeZone-Tzfile  R
* perl-DateTime-TimeZone-Tzfile PA
* perl-Devel-Size PA
* perl-Digest-HMAC PA
  * perl-NTLM  R
* perl-File-Fetch PA
* perl-File-Find-Iterator PA
* perl-File-Listing PA
* perl-File-PathList PA
  * perl-Perl-Critic-StricterSubs  R
* perl-HTTP-Cookies PA
* perl-HTTP-Negotiate PA
* perl-Inline-Module PA
* perl-IO-CaptureOutput PA
* perl-IPC-SysV PA
* perl-JSON-Color PA
  * perl-XXX  R
* perl-local-lib PA
* perl-Module-Manifest-Skip PA
* perl-NTLM PA
* perl-Params-Classify PA
  * perl-DateTime-TimeZone-SystemV  R
  * perl-DateTime-TimeZone-Tzfile  R
* perl-Perl-Critic-Bangs PA
* perl-Perl-Critic-Compatibility PA
* perl-Perl-Critic-Dynamic PA
* perl-Perl-Critic-Moose PA
* perl-Perl-Critic-Nits PA
* perl-Perl-Critic-PetPeeves-JTRAMMELL PA
* perl-Perl-Critic-Storable PA
* perl-Perl-Critic-StricterSubs PA
* perl-Perl-Critic-Swift PA
* perl-Perl-Critic-Tics PA
* perl-perlfaq PA
* perl-perlindex PA
* perl-PerlIO-gzip PA
* perl-PerlIO-via-QuotedPrint PA
* perl-srpm-macros PA
* perl-Test-Perl-Critic-Progressive PA
* perl-Unicode-Collate PA
* perl-XXX PA
  * perl-Inline-Module  R
  * perl-TestML  R OLD
* pkcs11-helper PA
  * qca  R
* plasma-breeze PA
  * kwin  R
* plasma-workspace PA
  * kde-cli-tools  R
* plexus-interactivity PA
  * maven-javadoc-plugin  R
* plymouth PA
  * gdm  R
* polkit-pkla-compat PA
* polkit-qt PA
  * kdelibs  R
* pps-tools PA
  * gpsd  R
* proj PA
  * qt-mobility  R
* pyparsing PA
* pyserial PA
  * gpsd  R
* pytest PA
  * babel  R
  * fuse-sshfs  R
  * future  R OLD
  * numpy  R OLD
  * pycairo  R OLD
  * python-atomicwrites  R
  * python-attrs  R
  * python-chardet  R
  * python-click  R
  * python-dateutil  R
  * python-flask  R
  * python-freezegun  R
  * python-html5lib  R
  * python-hypothesis  R OLD
  * python-imagesize  R
  * python-jinja2  R
  * python-mako  R OLD
  * python-packaging  R
  * python-parameterized  R OLD
  * python-pip  R OLD
  * python-pluggy  R
  * python-recommonmark  R OLD
  * python-requests  R OLD
  * python-setuptools  R OLD
  * python-setuptools_scm  R OLD
  * python-six  R OLD
  * python-sphinx  R OLD
  * python-sphinxcontrib-applehelp  R
  * python-sphinxcontrib-devhelp  R
  * python-sphinxcontrib-htmlhelp  R
  * python-sphinxcontrib-jsmath  R
  * python-sphinxcontrib-qthelp  R
  * python-sphinxcontrib-serializinghtml  R
  * python-urllib3  R
  * python-wcwidth  R
  * python-werkzeug  R
  * pytz  R
  * pyxattr  R
  * rpmlint  R
* python2-setuptools PA
  * babel  R
  * pycairo  R OLD
  * python-dns  R OLD
  * python-docutils  R OLD
  * python-jinja2  R
  * python-markupsafe  R
  * python-six  R OLD
* python-atomicwrites PA
* python-attrs PA
* python-chardet PA
* python-click PA
* python-CommonMark PA
* python-dateutil PA
* python-flask PA
  * librepo  R
* python-freezegun PA
  * babel  R
  * python-dateutil  R
  * python-pip  R OLD
* python-html5lib PA
* python-idna PA
* python-imagesize PA
* python-isodate PA
* python-itsdangerous PA
* python-jinja2 PA
* python-markupsafe PA
* python-mimeparse PA
* python-more-itertools PA
* python-munkres PA
* python-packaging PA
* python-pbr PA
* python-pluggy PA
* python-py PA
* python-rpm-generators PA
* python-scour PA
* python-snowballstemmer PA
* python-sphinxcontrib-applehelp PA
* python-sphinxcontrib-devhelp PA
* python-sphinxcontrib-htmlhelp PA
* python-sphinxcontrib-jsmath PA
* python-sphinxcontrib-qthelp PA
* python-sphinxcontrib-serializinghtml PA
* python-traceback2 PA
* python-unittest2 PA
* python-urllib3 PA
* python-wcwidth PA
* python-werkzeug PA
* pytz PA
  * babel  R
* pyxattr PA
  * librepo  R
* qca PA
  * kdelibs  R
  * okular  R
  * kde-connect  R
  * okular  R
* qt5-qt3d PA
* qt5-qtconnectivity PA
* qt5-qtenginio PA
* qt5-qtimageformats PA
  * qt5  R OLD
  * qt5-qt3d  R
* qt5-qtserialport PA
* qt5-qtvirtualkeyboard PA
  * kwin  R
* qt5-qtwayland PA
* qt-mobility PA
  * qtwebkit  R
* qtsoap PA
  * herqq  R
* qtwebkit PA
  * kdelibs  R
* rdma-core PA
* redhat-menus PA
* rpcbind PA
* rpmdevtools PA
* rpmlint PA
* R-rpm-macros PA
* rubygem-crass PA
  * rubygem-loofah  R
* rubygem-erubi PA
* rubygem-fattr PA
* rubygem-hpricot PA
* rubygem-loofah PA
  * rubygem-rails-html-sanitizer  R
* rubygem-marcel PA
* rubygem-mimemagic PA
  * rubygem-marcel  R
* rubygem-mustache PA
* rubygem-rails-html-sanitizer PA
* rubygem-rake-compiler PA
  * rubygem-hpricot  R
* rubygem-rspec2-mocks PA
* rubygem-rspec-mocks PA
* rubygem-rspec-support PA
* rubygem-rubyzip PA
* rubygem-turbolinks-source PA
* rubygem-websocket PA
* rubypick PA
* rust-srpm-macros PA
* sblim-sfcc PA
* signon PA
  * kaccounts-integration  R
* sip PA
* sssd PA
* taglib PA
  * kf5-kfilemetadata  R
* usbauth-notifier PA
* xapps PA
  * xreader  R
* xcb-util-cursor PA
  * kwin  R
* xemacs-packages-base PA
* xmvn PA
* xorg-x11-drv-libinput PA
* xorg-x11-fonts PA
* xorg-x11-server-utils PA
* xreader PA
* zchunk PA
  * libdnf  R
  * librepo  R
  * libsolv  R
* zsh PA
  * Lmod  R
## SOURCE DEPENDENCIES REMOVED
Total Sources Removed: 0
