# mxnet-build-script
Script to build mxnet pip wheel


1. unzip the package in your EC2 instance
2. cd build_mxnet
3. docker build -t <image_name> .  => for example, docker build -t mxbuild .
4. docker run -it mxbuild bash
5. ./buildmx <flavor> => for example, ./buildmx cu100
