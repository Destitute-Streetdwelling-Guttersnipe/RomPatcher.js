# Rom Patcher JS
A ROM patcher made in HTML5.

**Features:**
* Supported formats:
   * IPS
   * UPS
   * APS (N64/GBA)
   * BPS
   * RUP
   * PPF
   * Paper Mario Star Rod (.mod)
   * VCDiff (.xdelta, .vcdiff)
* can patch and create patches
* shows ROM CRC32, MD5 and SHA-1 before patching
* can remove headers before patching
* unzips files automatically
* made in Vanilla JS
* can be run in any modern web browser, including mobile
* support pre-defined patches

## Difference from marcrobledo/RomPatcher.js

* support pre-defined patches in URL hash (such as `#{"PATCHER":[{"name":"a_patcher_name","file":"data:;base64,VVBTMQAgboMAIG6D+pUXwPqVF8AybecD"}]}`)
