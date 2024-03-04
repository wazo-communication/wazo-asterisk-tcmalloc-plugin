# wazo-asterisk-tcmalloc-plugin

Modifies the memory allocator to use [TCmalloc](https://github.com/google/tcmalloc) instead of the default `glibc` `malloc`.

## Installation

```sh
wazo-plugind-cli -c "install git https://github.com/wazo-communication/wazo-asterisk-tcmalloc-plugin"
```

Caution: installing this plugin will restart Asterisk, which will interrupt any currently running call.

## Uninstallation

```sh
wazo-plugind-cli -c "uninstall wazocommunication/wazo-asterisk-tcmalloc"
```

Caution: uninstalling this plugin will restart Asterisk, which will interrupt any currently running call.
