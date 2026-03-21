# systemd-free Linux Distributions (as of early 2026)
# Actively maintained distros that do NOT use systemd by default
# Many offer alternative inits or let you choose during install/setup

## Main / Popular ones

- Void Linux          → runit
  (default and only init; independent, uses XBPS package manager)

- Alpine Linux        → OpenRC
  (very lightweight, musl libc + BusyBox, popular for containers/servers)

- Devuan              → sysVinit (default)
  also supports OpenRC, runit, and others
  (Debian fork specifically to avoid systemd)

- Artix Linux         → OpenRC, runit, dinit, or s6
  (Arch-based rolling release; choose init at install)

- antiX               → sysVinit
  (Debian-based, extremely lightweight, anti-bloat, good for old hardware)

- MX Linux            → sysVinit
  (Debian-based, user-friendly midweight, excellent tools)

- Gentoo              → OpenRC (default non-systemd)
  (source-based; systemd can be avoided completely)

- Funtoo              → OpenRC
  (Gentoo fork, community-driven)

- Hyperbola GNU/Linux-libre → OpenRC
  (fully free software, long-term support, no binary blobs)

- Chimera Linux       → dinit
  (modern, musl-based, clean design, gaining popularity)

- Slackware           → BSD-style init scripts / sysV-like
  (classic, traditional; never adopted systemd)

- GoboLinux           → custom / sysVinit-like
  (very unique filesystem layout)

- Nitrux              → s6 or alternatives
  (KDE-focused, independent)

## Niche / Specialized ones

- Guix System         → Shepherd
  (GNU project, functional package management)

- CRUX                → BSD-style init scripts

- TinyCore Linux      → very minimal custom init

- Puppy Linux variants → often sysVinit (many systemd-free flavors)

## Notes
Most mainstream distros (Ubuntu, Fedora, Arch default, openSUSE, Debian, etc.)
use systemd by default.

Last checked/updated : March 2026
