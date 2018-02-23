FROM debian:6

# Use sources list from the archive
ADD sources.list /etc/apt/sources.list

# Make sure apt-get is up to date and dependent packages are installed
RUN \
  apt-get -o Acquire::Check-Valid-Until=false update && \
  apt-get install -y automake autogen build-essential ca-certificates \
    gcc-multilib \
    clang llvm-dev  libtool libxml2-dev uuid-dev libssl-dev pkg-config \
    patch make xz-utils cpio wget unzip git mercurial bzr rsync --no-install-recommends
