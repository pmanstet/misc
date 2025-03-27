# Quick local CMake install

## Requirements

- Linux or compatible OS
- Bash or compatible shell
- `wget`
- `tar`
- work for CMake versions > 3.20

## Usage/Demo 

```shell
wget https://raw.githubusercontent.com/pmanstet/misc/refs/heads/main/cmake/cmakeenv && chmod +x cmakeenv
./cmakeenv 3.31 5 linux-x86_64 .cmake331
source .cmake331/bin/activate
which cmake
source .cmake331/bin/deactivate
which cmake
```
