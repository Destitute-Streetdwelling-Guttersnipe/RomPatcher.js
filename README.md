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

* support pre-defined patch files in URL hash (such as `#{"PATCHER":[{"name":"Boaty-McBoatface","file":"data:;base64,VVBTMQAgboMAIG6D+pUXwPqVF8AybecD"}]}`)
* can create patch file in URL hash

Taking advantage of the ability to extract patch files from a ZIP archive, I can put base64-encoded ZIP archive in URL. For example: `#{"PATCHER":[{"name":"Patchy-McPatchface","file":"data:;base64,UEsDBBQDAAAIAGVcP1gc30QhFQAAABgAAAAJAAAASG9vdHkudXBzCw0INmRQyGsG4V9TxQ+AsFHuc2YAUEsBAj8DFAMAAAgAZVw/WBzfRCEVAAAAGAAAAAkAJAAAAAAAAAAggLSBAAAAAEhvb3R5LnVwcwoAIAAAAAAAAQAYAABTqN/+U9oBgJv7vf9T2gEAEm26CVTaAVBLBQYAAAAAAQABAFsAAAA8AAAAAAA=","patches":[{"name":"Hooty-McOwlface","file":"Hooty.ups"},{"name":"S.S.-ShouldveBeenABridge","file":"Hooty.ups"}]}]}`


## Known sites that use Rom Patcher JS
* [Romhacking.net](https://www.romhacking.net/)
* [Smash Remix](https://smash64.online/remix/)
* [Radical Red](https://patch.radicalred.net/)
* [Rocket Edition](https://rocket-edition.com/download/)
