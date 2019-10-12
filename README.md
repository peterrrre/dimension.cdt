# Dimension.CDT (Contract Development Toolkit)
## Version : 1.5.0

Dimension.CDT is a toolchain for WebAssembly (WASM) and set of tools to facilitate contract writing for the dimension platform.  In addition to being a general purpose WebAssembly toolchain, [Dimension](https://github.com/peterrrre/dimension) specific optimizations are available to support building Dimension smart contracts.
## Important!
Dimension.CDT Version 1.3.x introduced quite a few breaking changes.  To have binary releases we needed to remove the concept of a core symbol from Dimension.CDT. This meant drastic changes to symbol, asset and other types/functions that were connected to them. Since these changes would be disruptive, we decided to add as many disruptive changes needed for future contract writing, so that disruption should only occur once. Please read the **_Differences between Version 1.2.x and Version 1.3.x_** section of this readme.



**If you have previously installed Dimension.CDT, please run the `uninstall` script (it is in the directory where you cloned Dimension.CDT) before downloading and using the binary releases.**



### Guided Installation (Building from Scratch)
```sh
$ git clone --recursive https://github.com/peterrrre/dimension.cdt
$ cd eosio.cdt
$ ./build.sh
$ sudo ./install.sh

