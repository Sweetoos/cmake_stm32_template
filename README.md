# STM32 with CMake

To setup 

```shell
cmake -S . -B build -G Ninja -DCMAKE_TOOLCHAIN_FILE=cmake/arm-gcc-toolchain.cmake
```

To build 
```shell
ninja -C build
```

To program
```shell
ninja -C build program
```