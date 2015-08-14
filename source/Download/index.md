title: Download
---
<ul>
<li>[↓ Windows](http://static.red-lang.org/dl/win/red-054.exe)</li>
<li>[↓ GNU/Linux](http://static.red-lang.org/dl/linux/red-054)</li>
<li>[↓ Mac OS X](http://static.red-lang.org/dl/mac/red-054)</li>
</ul>

### Note for Linux
For Linux 64-bit distros, you need to install 32-bit supporting libraries. So, for Debian-based distros, install them using:
``` bash
$ sudo apt-get install ia32-libs libc6-i386
```
If you are using a Debian 7+ or Ubuntu 13.10+ version, you should use the multiarch way:
``` bash
$ dpkg --add-architecture i386
$ apt-get update
$ apt-get install libc6:i386
```
