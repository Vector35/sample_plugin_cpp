# Binary Ninja C++ Plugin Template

This is a Binary Ninja plugin template for building plugins using the C++ API.
Included is support for automated builds using the GitHub Actions CI.

## Compatibility

This repo has been tested on the following versions of Binary Ninja:
* Binary Ninja 4.2.6455
* Binary Ninja 4.1.5747
* Binary Ninja 4.0.4958

And the following operating systems:
* Windows 11
* Windows 10
* Ubuntu 24.04
* Ubuntu 22.04
* macOS 15
* macOS 14

Other versions may work, though! Later versions of operating systems will likely load fine, though later versions of Binary Ninja may need to be recompiled and possibly have the CI patches reworked.

## Credits

The CI configuration and patches are based upon the work of various Open Source projects made by members of the Binary Ninja community:

* [setup-binary-ninja](https://github.com/emesare/setup-binary-ninja) by emesare (ISC License)
* [binexport](https://github.com/google/binexport) by Google (Apache 2.0 License)
