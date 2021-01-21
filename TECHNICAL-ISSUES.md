# Technical Issues

- [undefined symbol: __atomic_fetch_add_8](https://github.com/piwheels/packages/issues/59)
  - work-around: add `export LD_PRELOAD=/usr/lib/arm-linux-gnueabihf/libatomic.so.1` to `~/.bashrc`

- LLVM Version
  - add `export LLVM_CONFIG=/usr/bin/llvm-config-9` to `~/.bashrc`
