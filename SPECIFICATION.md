# Prisma — Specification

## Goal
Deliver a premium, adaptive KDE Plasma experience
with rich chromatic blur, layered materials and
a productive desktop layout.

## Platform
- KDE Plasma 6.8 and Wayland initially
- Fedora KDE Plasma Desktop 45 as the reference environment
- Support other compatible distributions where practical

## Appearance
- Wallpaper-derived and manual KDE accent support
- Coordinated dark and light appearances
- Dynamic colours with contrast-aware foregrounds and surfaces
- Chromatic glass, frosted glass, satin, solid and elevated materials
- Preserve local background colours in blur
- Rich dark appearance without excessive saturation
- Live updates wherever supported by the desktop and application toolkit
- Consistent typography, geometry, spacing and interaction states

## Desktop
- Floating chromatic top panel with grouped controls
- Compact floating application dock
- Native Plasma panels and existing functional widgets only
- Existing icon and cursor packs only
- Productive, keyboard-accessible and mouse-accessible navigation

## Coverage
- Plasma Style and Global Theme
- Panels, dock, launchers, KRunner and desktop menus
- Tray widgets, popups, notifications, tooltips and OSDs
- Window decorations, dialogs and application controls
- Qt Widgets, Qt Quick, Kirigami and GTK integration
- Login, lock, splash and session screens where supported
- Desktop overview, task switching and window management effects
- Optional terminal and application appearance integrations

## Implementation
- Native KDE functionality first
- KWin blur and compositing
- Plasma Union preferred for application styling, subject to validation
- Shared colour roles and assets wherever supported
- Minimal dependencies, source files and runtime overhead
- No custom functional widgets or icon packs
- No continuous polling unless strictly necessary
- Document toolkit and platform limitations

## Quality
- Readable across bright, dark and multicoloured wallpapers
- Responsive at high refresh rates and different display scales
- Accessible controls and interaction states
- Safe installation, updates, removal and restoration
- Version-controlled source and reproducible releases
- Preserve upstream licenses and attribution
