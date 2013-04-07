OneELEC.ACEStream
=================

**AceStream support for OpenELEC**

**How-To Install:**
* # cd ~
* # git clone https://github.com/OpenELEC/OpenELEC.tv
* # git clone https://github.com/oneevil/OpenELEC.ACEStream
* # cp -a OpenELEC.ACEStream/lang/Python OpenELEC.tv/packages/lang
* # cp -a OpenELEC.ACEStream/oem OpenELEC.tv/packages
* # cp -a OpenELEC.ACEStream/python/system/M2Crypto OpenELEC.tv/packages/python/system
* # cp -a OpenELEC.ACEStream/python/system/PyAMF OpenELEC.tv/packages/python/system
* # cp -a OpenELEC.ACEStream/security/openssl OpenELEC.tv/packages/security

**Find file "options" in the project directories:** (for example)
* # cd /OpenELEC.tv/project/ION/options

Replace this string:
* OEM_SUPPORT="no"

On:
* OEM_SUPPORT="yes"
* # cd ~/OpenELEC.tv
* # PROJECT=ION ARCH=x86_64 make release