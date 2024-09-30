`gd_libuvc-theta` is a modified version of `libuvc` that includes support for Ricoh Theta cameras. `libuvc` is a cross-platform library for USB video devices, built atop `libusb`. It enables fine-grained control over USB video devices exporting the standard USB Video Class(UVC) interface, enabling developers to write drivers for previously unsupported devices, or just access UVC devices in a generic fashion.

## Getting and Building gd_libuvc-theta

To build, you can just run these shell commands:

    git clone https://github.com/GuideDog-ETRI/gd_libuvc-theta.git
    cd gd_libuvc-theta
    mkdir build
    cd build
    cmake -DCMAKE_BUILD_TYPE=Release ..
    make &&sudo make install

## Developing with libuvc

The documentation for `libuvc` can currently be found at https://libuvc.github.io/.

Happy hacking!
