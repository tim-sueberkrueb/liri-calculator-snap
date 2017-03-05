## Liri Calculator Snap
Experimental snap package for Liri Calculator

### Dependencies
For building you need:
* All dependencies of [Liri Calculator][liri-calculator-gh]
* [snapcraft][snapcraft-gh]

Runtime dependencies:
* [platform-snap][platform-snap-gh]

### Build

From the root of the repository, run:

```
QTDIR=<path-to-qt> snapcraft
```

### Install

From your build directory, run:

```sh
sudo snap install --dangerous liri-platform*.snap
sudo snap connect liri-calculator:platform liri-platform:platform
```
[liri-calculator-gh]: http://github.com/lirios/calculator
[snapcraft-gh]: https://github.com/snapcore/snapcraft
[platform-snap-gh]: https://github.com/lirios/platform-snap
