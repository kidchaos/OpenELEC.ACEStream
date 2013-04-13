OpenELEC.ACEStream
=================

**AceStream support for OpenELEC**

**How-To Install:**
* # cd ~
* # git clone https://github.com/OpenELEC/OpenELEC.tv
* # git clone https://github.com/oneevil/OpenELEC.ACEStream
* # cp -a OpenELEC.ACEStream/devel/boost OpenELEC.tv/packages/devel
* # cp -a OpenELEC.ACEStream/lang/Python OpenELEC.tv/packages/lang
* # cp -a OpenELEC.ACEStream/oem OpenELEC.tv/packages
* # cp -a OpenELEC.ACEStream/python/system/M2Crypto OpenELEC.tv/packages/python/system
* # cp -a OpenELEC.ACEStream/python/system/PyAMF OpenELEC.tv/packages/python/system
* # cp -a OpenELEC.ACEStream/security/openssl OpenELEC.tv/packages/security
* # cp -a OpenELEC.ACEStream/torrenter OpenELEC.tv/packages
* # cp -a OpenELEC.ACEStream/shell OpenELEC.tv/packages

**Find file "options" in the project directories:** (for example)
* # cd /OpenELEC.tv/project/ION/options

**Replace this string:**
* OEM_SUPPORT="no"

**On:**
* OEM_SUPPORT="yes"

**And compile:**
* # cd ~/OpenELEC.tv
* # PROJECT=ION ARCH=x86_64 make release
