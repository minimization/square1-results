# Buildroot Source Changes
Checked on 2020-03-05-15:21

Last time there was a change was [2020-03-02-16:49](https://github.com/minimization/square1-results/blob/master/docs/archives/2020-03-02-16:49/data/buildroot-changes.md)
## SOURCE DEPENDENCIES ADDED
Total New Sources Added: 5

PA = Package Added  R = Requires Added Package  OLD = Not New
* dotnet3.1 PA
* flashrom PA
  * fwupd  R OLD
* libconfuse PA
  * libftdi  R
* libftdi PA
  * flashrom  R
  * lirc  R OLD
* libgit2_0.28 PA
  * kf5-ktexteditor  R OLD
  * libgit2-glib  R OLD
## SOURCE DEPENDENCIES REMOVED
Total Sources Removed: 1

PR = Package Removed  N = No longer Needs removed package, or was also removed
* libgit2_0.27 PR
  * kf5-ktexteditor  N
  * libgit2_0.27-devel  N
  * libgit2-glib  N
