OpenELEC.ACEStream
=================

**AceStream support for OpenELEC**

**How-To Install:**
* # cd ~
* # git clone https://github.com/OpenELEC/OpenELEC.tv
* # git clone https://github.com/oneevil/OpenELEC.ACEStream
* # cp -R OpenELEC.ACEStream/* OpenELEC.tv/packages/

**Find file "options" in the project directories:** (for example)
* # cd /OpenELEC.tv/project/ION/options

**Replace this string:**
* OEM_SUPPORT="no"

**On:**
* OEM_SUPPORT="yes"

**And compile:**
* # cd ~/OpenELEC.tv
* # PROJECT=ION ARCH=x86_64 make release
