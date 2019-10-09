[![Build Status](https://travis-ci.com/WojciechMigda/hello-arm.svg?branch=master)](https://travis-ci.com/WojciechMigda/hello-arm)

Simple "Hello ARM!" app for ARM architecture.

To cross-compile it and run on Ubuntu:

    $ cd .build && cmake .. -DCMAKE_TOOLCHAIN_FILE=../toolchain.cmake && make
    $ cd app && qemu-arm -L /usr/arm-linux-gnueabihf ./hello-arm
