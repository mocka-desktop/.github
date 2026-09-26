Mocka is a desktop environment for GhostBSD that replaces MATE one component
at a time until every part has been replaced. Every component is written from
scratch, reverse engineered from how the existing tools behave, and stays
compatible with MATE so both can be mixed during the transition.

## Components

| Component | Description | Status |
|-----------|-------------|--------|
| [mocka-dock](https://github.com/mocka-desktop/mocka-dock) | Taskbar-style dock applet for the MATE panel | Alpha (0.0.1) |
| mocka-menu | Application menu with Classic and full-screen Launcher layouts | Planned |
| Settings tool | Desktop appearance and UI settings, replacing mate-control-center | Planned |

## Goals

- BSD-first: no Linux-specific assumptions
- Compatible with MATE while components are replaced
- BSD-3-Clause licensed
- GTK 3

## Getting Mocka

Mocka components ship with [GhostBSD](https://www.ghostbsd.org). Each
repository also has build instructions for FreeBSD.

## Contributing

Bug reports and feedback are welcome in each component's issue tracker.

## Support the project

Mocka is developed as part of GhostBSD. You can support development on
[Patreon](https://www.patreon.com/GhostBSD).
