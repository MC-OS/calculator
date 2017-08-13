# Calculator
[![Translation status](https://l10n.elementary.io/widgets/calculator/-/svg-badge.svg)](https://l10n.elementary.io/projects/calculator/?utm_source=widget)

![Screenshot](data/screenshot.png?raw=true)

## Building, Testing, and Installation

You'll need the following dependencies:
* cmake
* libgranite-dev
* valac

It's recommended to create a clean build environment

    mkdir build
    cd build/
    
Run `cmake` to configure the build environment and then `make` to build

    cmake -DCMAKE_INSTALL_PREFIX=/usr ..
    make
    
To install, use `make install`, then execute with `io.elementary.calculator`

    sudo make install
    io.elementary.calculator
