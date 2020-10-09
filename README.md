# calg

This project is a fork of [c-algorithms](https://github.com/fragglet/c-algorithms) with an updated [Meson](https://mesonbuild.com/) build system and some personal tweaks. Installation can be done directly from source in the following way:

```
$ git clone https://github.com/seatonullberg/calg && cd calg
$ meson setup build && cd build
$ meson compile
$ meson test
$ meson install
```

The documentation can be built from source as well:

```
$ meson compile doxygen
```

Files will be generated in `docs/html/`.