FROM ubuntu:16.04

# Make sure apt-get is up to date and dependent packages are installed
RUN \
  apt-get update && \
  apt-get install -y automake autogen build-essential ca-certificates           \
    gcc-arm-linux-gnueabi g++-arm-linux-gnueabi libc6-dev-armel-cross           \
    gcc-multilib  g++-multilib mingw-w64 clang llvm-dev                         \
    libtool libxml2-dev uuid-dev libssl-dev swig pkg-config patch               \
    make xz-utils cpio wget zip unzip p7zip git mercurial bzr texinfo help2man  \
    binutils-multiarch rsync                                                    \
    --no-install-recommends