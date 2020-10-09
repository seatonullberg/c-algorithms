# collections

This project is a fork of [c-algorithms](https://github.com/fragglet/c-algorithms) with an updated [Meson](https://mesonbuild.com/) build system and some personal tweaks. Installation can be done directly from source in the following way:

```
$ git clone https://github.com/seatonullberg/collections && cd collections
$ meson setup build && cd build
$ meson compile
$ meson test
$ meson install
```

The library will then be available on your system as `libcollections.so`.