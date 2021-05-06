**NOTE:** Open3D added a similar project [here](https://github.com/intel-isl/open3d-cmake-find-package). Make sure you checkout that first since this repo might get outdated really fast.

# Open3D C++ Example

This is a really dummy project, but you could use it to test if your `Open3D`
build is working.

## Requirements

Please follow [these](http://www.open3d.org/docs/release/tutorial/C++/cplusplus_interface.html) instructions.

## Notes

- You don't actually need `C++17` support, just change it if your compiler does
  not support this.
- This project only supports GNU/Linux, so I've removed all the border code
  plate for Windows. If you are using Windows, well, I'm sorry for you, there is
  a much better life out there.

## Build

Easy and cheasy:

```sh
mkdir build/
cd build
cmake ..
make
```
