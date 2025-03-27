# Quick local CMake install

## Requirements

- Linux or compatible OS
- Bash or compatible shell
- `wget`
- `tar`
- for CMake versions > 3.20 only

## Usage/Demo 

```shell
# install
wget https://raw.githubusercontent.com/pmanstet/misc/refs/heads/main/cmake/cmakeenv && chmod +x cmakeenv
./cmakeenv 3.31 5 linux-x86_64 .cmake3315

# enable
source .cmake3315/bin/activate
which cmake
cmake --version

# disable
source .cmake3315/bin/deactivate
which cmake
cmake --version

# uninstall
rm -rf .cmake3315
```
