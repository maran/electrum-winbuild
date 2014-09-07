#### Electrum windows build

Create unattended Electrum Windows builds on Linux using docker.

##### Getting started

Install [Docker](https://www.docker.com/). On Ubuntu 14.04 you can do
this by using `sudo apt-get install docker.io`

Clone this repository and run ./build 1.9.8 (or whatever the latest stable release is) and if
all goes well your windows binary should appear in the releases folder.

##### General remarks

The first time you run this script it will need to install and configure
a docker container. This might take a while. All builds after the
initial one will be quicker since docker caches the vm state.

* Only stable builds are supported so far, not building from git yet.

* Only the Standalone Executable is working so far.
