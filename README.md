SymbiontDCOS RootFS
===================

This is the root context OS for the Symbiont Slim system.  It is designed to
be the running system.  All container images and portable services run from 
this context layer.

System updates are atomic in nature.  There are no package managers installed
in this context.  The only way to upgrade the system is via `updatectl`.  This
will download a new subvolume and configure the bootloader to launch it at 
next boot.


## Note:  
`updatectl` is not complete yet.  Therefore, everything is still manual...






