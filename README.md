# Square1 source dependency tracking results

Square1 is a project designed to keep the core buildroot as small as possible.

The core buildroot is the packages in @buildsys-build, and everything needed to build those packages.  The core buildroot should be self-hosting.  Self-hosting means that they should be able to build all the packages needed to build all the packages.

The source depdenency tracker allows us to see when packages have been added or removed from the core buildroot, and why.

The easiest way to see these changes is through the [change md files](https://github.com/minimization/square1-results/blob/master/docs/buildroot-changes.md)
