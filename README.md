# Zhme's Linux From Scratch
My implementation of Linux From Scratch - Version r12.2-894-systemd-multilib

TODO -> change location of the <package management> section to an earlier point
of the book. It would seem relevant to understand why the various commands use 
'prefix'/'destdir' of '/usr/','/usr/lib','/lib/','/bin/','/usr/bin', etc.

The concept of package management should be easier to digest after fully building
LFS once or twice, but the analysis of the contents of that section should be
contemplated prior to installing packages. Is the package management design you 
intend to implement necessary before building the system? No. Although it will
be useful to have a perspective of the system tools.

## Automation
Intent -> write bash scripts to automate the entirety of the installation.
Currently using JSON for package stats for quick alterations...
  YAML? 
