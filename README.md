[![GitHub release (latest by date)](https://img.shields.io/github/v/release/xpack-dev-tools/riscv-none-embed-gcc-xpack)](https://github.com/xpack-dev-tools/riscv-none-embed-gcc-xpack/releases)
[![npm (scoped)](https://img.shields.io/npm/v/@xpack-dev-tools/riscv-none-embed-gcc.svg)](https://www.npmjs.com/package/@xpack-dev-tools/riscv-none-embed-gcc)

## The xPack GNU RISC-V Embedded GCC

This open source project is hosted on GitHub as
[`xpack-dev-tools/riscv-none-embed-gcc-xpack`](https://github.com/xpack-dev-tools/riscv-none-embed-gcc-xpack)
and provides the platform specific binaries for the
[xPack GNU RISC-V Embedded GCC](https://xpack.github.io/riscv-none-embed-gcc/).

This distribution plans to follow the official
[SiFive](https://www.sifive.com) releases.

The binaries can be installed automatically as **binary xPacks** or manually as
**portable archives**.

In addition to the package meta data, this project also includes
the build scripts.

## User info

This section is intended as a shortcut for those who plan
to use the GNU RISC-V Embedded GCC binaries. For full details please read the
[xPack GNU RISC-V Embedded GCC](https://xpack.github.io/riscv-none-embed-gcc/) pages.

### Easy install

The easiest way to install GNU RISC-V Embedded GCC is using the **binary xPack**, available as
[`@xpack-dev-tools/riscv-none-embed-gcc`](https://www.npmjs.com/package/@xpack-dev-tools/riscv-none-embed-gcc)
from the [`npmjs.com`](https://www.npmjs.com) registry.

#### Prerequisites

The only requirement is a recent
`xpm`, which is a portable
[Node.js](https://nodejs.org) command line application. To install it,
follow the instructions from the
[xpm](https://xpack.github.io/xpm/install/) page.

#### Install

With the `xpm` tool available, installing
the latest version of the package is quite easy:

```sh
xpm install --global @xpack-dev-tools/riscv-none-embed-gcc@latest
```

This command will always install the latest available version,
into the central xPacks store, which is a platform dependent folder
(check the output of the `xpm` command for the actual folder used on
your platform).

This location is configurable using the environment variable
`XPACKS_REPO_FOLDER`; for more details please check the
[xpm folders](https://xpack.github.io/xpm/folders/) page.

xPacks aware tools, like the **GNU MCU Eclipse plug-ins** automatically
identify binaries installed with
`xpm` and provide a convenient method to manage paths.

#### Uninstall

To remove the installed xPack, the command is similar:

```sh
xpm uninstall --global @xpack-dev-tools/riscv-none-embed-gcc
```

### Manual install

For all platforms, the **xPack GNU RISC-V Embedded GCC** binaries are
released as portable archives that can be installed in any location.

The archives can be downloaded from the
GitHub [releases](https://github.com/xpack-dev-tools/riscv-none-embed-gcc-xpack/releases/) page.

For more details please read the [Install](https://xpack.github.io/riscv-none-embed-gcc/install/) page.

## Maintainer info

- [How to build](https://github.com/xpack-dev-tools/riscv-none-embed-gcc-xpack/blob/xpack/README-BUILD.md)
- [How to make new releases](https://github.com/xpack-dev-tools/riscv-none-embed-gcc-xpack/blob/xpack/README-RELEASE.md)

## Support

The quick answer is to use the [xPack forums](https://www.tapatalk.com/groups/xpack/);
please select the correct forum.

For more details please read the [Support](https://xpack.github.io/riscv-none-embed-gcc/support/) page.

## License

The original content is released under the
[MIT License](https://opensource.org/licenses/MIT), with all rights
reserved to [Liviu Ionescu](https://github.com/ilg-ul/).

The binary distributions include several open-source components; the
corresponding licenses are available in the installed
`distro-info/licenses` folder.

## Download analytics

- GitHub [`xpack-dev-tools/riscv-none-embed-gcc-xpack`](https://github.com/xpack-dev-tools/riscv-none-embed-gcc-xpack/) repo
  - latest xPack release
[![Github All Releases](https://img.shields.io/github/downloads/xpack-dev-tools/riscv-none-embed-gcc-xpack/latest/total.svg)](https://github.com/xpack-dev-tools/riscv-none-embed-gcc-xpack/releases/)
  - all xPack releases [![Github All Releases](https://img.shields.io/github/downloads/xpack-dev-tools/riscv-none-embed-gcc-xpack/total.svg)](https://github.com/xpack-dev-tools/riscv-none-embed-gcc-xpack/releases/)
  - previous GNU MCU Eclipse all releases [![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/riscv-none-gcc/total.svg)](https://github.com/gnu-mcu-eclipse/riscv-none-gcc/releases/)
- npmjs [`@xpack-dev-tools/riscv-none-embed-gcc`](https://www.npmjs.com/package/@xpack-dev-tools/riscv-none-embed-gcc/) xPack
  - latest release, per month
[![npm (scoped)](https://img.shields.io/npm/v/@xpack-dev-tools/riscv-none-embed-gcc.svg)](https://www.npmjs.com/package/@xpack-dev-tools/riscv-none-embed-gcc/)
[![npm](https://img.shields.io/npm/dm/@xpack-dev-tools/riscv-none-embed-gcc.svg)](https://www.npmjs.com/package/@xpack-dev-tools/riscv-none-embed-gcc/)
  - all releases [![npm](https://img.shields.io/npm/dt/@xpack-dev-tools/riscv-none-embed-gcc.svg)](https://www.npmjs.com/package/@xpack-dev-tools/riscv-none-embed-gcc/)
- GitHub [individual file counters](https://somsubhra.github.io/github-release-stats/?username=xpack-dev-tools&repository=riscv-none-embed-gcc-xpack) (grouped per release)

Credit to [Shields IO](https://shields.io) and [Somsubhra/github-release-stats](https://github.com/Somsubhra/github-release-stats).
