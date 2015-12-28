# Depbuilder: Dependency Builder

(Development is in progress.  Depbuilder is not yet functional.)

"Like NPM, but for native code."  Depbuilder is a tool for automatically building the third-party C and C++ libraries that your software depends on.

Depbuilder complements your system's package manager, if it exists.  You can install some packages system-wide with Apt, DNF, or Homebrew, and install some packages locally with Depbuilder.  This lets you more easily pin your software to specific versions of third-party packages.  Depbuilder lets you choose between system packages and local packges.

Depbuilder is cross-platform, and works on Linux, OS X, and Windows.  Unfortunately, there are some rather significant differences between the various platforms, so it may take some additional work to make sure that your dependencies can be built on all supported platforms.
