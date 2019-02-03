# selfex
Creator for Self-extracting utilities.
## Installation
Go to [the Releases page](https://github.com/nift4/selfex/releases/latest) and download the Installer. Then run it.
## Usage
### Import script into payload
INFO: You can add other free-named things into `selfex/payload/`.
Put your utility that should run by selfex in `selfex/payload/` and name it as `__selfex_entry__`.
### Information about the runtime while running the generated selfex binary
In `.` is the content of payload, in `..` the previous workdir.
### Generate your self-extracting binary
Type `./selfex/build` and have fun with `object.bin`.
IMPORTANT: Run the build script outside of the selfex directory. Also not `./bla/selfex/build` and not `./build`. Only `./selfex/build`
