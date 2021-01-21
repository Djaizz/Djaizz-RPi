# Technical Issues

- [undefined symbol: __atomic_fetch_add_8](https://github.com/piwheels/packages/issues/59)
  - work-around: add `export LD_PRELOAD=/usr/lib/arm-linux-gnueabihf/libatomic.so.1` to the `~/.bashrc`
