# SDE
Sensible Desktop Environment

## Project Goals

SDE is a Linux desktop environment that aims to be simple, fast, secure, and beautiful; SDE should look amazing by default and allow user replaceable styles, themes, and icons; The desktop environment will support both [X11](https://www.x.org/) and [Wayland](https://wayland.freedesktop.org/). The project is inspired by [suckless](https://suckless.org/) software such as [dwm](https://dwm.suckless.org/), [st](https://st.suckless.org/), and [dmenu](https://tools.suckless.org/dmenu/). One of the primary goals of SDE is to use as little resources (i.e. memory, CPU utilization, GPU usage, etc.) as dwm does, while providing a complete desktop experience. SDE should work on all init systems, i.e. SystemD, runit, openrc, s6, etc. While the development work will be done on Linux, SDE should work on the BSDs and other open source POSIX-compliant operating systems.

Applications will be written in [Qt6](https://www.qt.io/product/qt6) and [C++17](https://www.iso.org/standard/68564.html), while core components such as the window manager and compositor will be written in [C17](https://www.iso.org/standard/74528.html).

## License

[MIT License](LICENSE)
