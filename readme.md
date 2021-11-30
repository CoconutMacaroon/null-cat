# null-cat

`null-cat` is a program that will print a file until a null character (`\0`) is reached. The null character will
not be printed.

## Building it

To build a `.deb` file of `null-cat`, you need a few things. First, I've tested this on Debian 11, so I suggest
using that.
1. To install the required packages, run `sudo apt-get update -y && sudo apt-get install git devscripts
build-essential lintian pandoc -y`.
2. Clone the Git repo (`git clone https://github.com/CoconutMacaroon/null-cat.git`)
3. `cd` into the directory (`cd null-cat`)
4. Build it by running the build script (`./build`).
5. The built `.deb` files will be in the parent directory of the Git repo. Assuming you have been following along,
you can navigate there by doing `cd ..`
