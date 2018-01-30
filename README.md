# DDBridge Driver

This is the debianized version of the Digital Device DDBridge Driver. This
package uses the dkms build system to automatically update the module on
kernel updates. To build a Debian/Ubuntu/Devuan package, checkout
this source and invoke

    debuild -b

The packages will be created in parent folder.

### Patches

Upstream can only accept patches which don't break compilation for older 
kernels (as far back as 2.6.37).

