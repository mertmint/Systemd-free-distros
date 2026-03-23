# systemd-free Linux Distributions (as of early 2026)
# Actively maintained distros that do NOT use systemd by default
# Many offer alternative inits or let you choose during install/setup


- Void Linux          → runit
  (default and only init; independent, uses XBPS package manager)
https://voidlinux.org

- Alpine Linux        → OpenRC
  (very lightweight, musl libc + BusyBox, popular for containers/servers)
https://www.alpinelinux.org

- Devuan              → sysVinit (default)
  also supports OpenRC, runit, and others
  (Debian fork specifically to avoid systemd)
https://www.devuan.org

- Artix Linux         → OpenRC, runit, dinit, or s6
  (Arch-based rolling release; choose init at install)
https://artixlinux.org

- antiX               → sysVinit
  (Debian-based, extremely lightweight, anti-bloat, good for old hardware)
https://antixlinux.com

- MX Linux            → sysVinit
  (Debian-based, user-friendly midweight, excellent tools)
https://mxlinux.org

- Gentoo              → OpenRC (default non-systemd)
  (source-based; systemd can be avoided completely)
https://www.gentoo.org

- Hyperbola GNU/Linux-libre → OpenRC
  (fully free software, long-term support, no binary blobs)
https://www.hyperbola.info

- Chimera Linux       → dinit
  (modern, musl-based, clean design, gaining popularity)
https://chimera-linux.org

- Slackware           → BSD-style init scripts / sysV-like
  (classic, traditional; never adopted systemd)
http://www.slackware.com


## Notes
Most mainstream distros (Ubuntu, Fedora, Arch default, openSUSE, Debian, etc.)
use systemd by default.

Last updated : 23 March 2026
