# Buildroot Source Changes
Checked on 2020-02-21-21:25

Last time there was a change was [2020-02-14-06:53](https://github.com/minimization/square1-results/blob/master/docs/archives/2020-02-14-06:53/data/buildroot-changes.md)
## SOURCE DEPENDENCIES ADDED
Total New Sources Added: 5

PA = Package Added  R = Requires Added Package  OLD = Not New
* accounts-qml-module PA
* hidapi PA
  * libfido2  R
* libcbor PA
  * libfido2  R
* libfido2 PA
  * openssh  R OLD
* python-breathe PA
  * libcbor  R
## SOURCE DEPENDENCIES REMOVED
Total Sources Removed: 7

PR = Package Removed  N = No longer Needs removed package, or was also removed
* oldstandard-sfd-fonts PR
  * fontconfig  N
  * perl-Tk  N
  * perl-Tk-Pod  N
* perl-Test-RequiresInternet PR
  * perl-libwww-perl  N
* pipewire0.2 PR
* python-linecache2 PR
* python-traceback2 PR
* rubygem-atomic PR
  * rubygem-thread_safe  N
* rubygem-thread_safe PR
  * rubygem-tzinfo  N
