# MinimapMenu

A compact minimap button organizer for WoW 1.12 / Octo that collects addon icons into one movable, labeled menu.

## Features

- Collects supported minimap addon buttons behind one hamburger-menu icon
- Uses the original addon buttons so their left-click, right-click, middle-click, drag, and tooltip behavior remains available
- Shows every collected button in a labeled vertical menu
- Questline-style row highlighting makes entries easy to follow
- Left-clicking a row opens the addon and closes the menu
- Clicking an icon directly keeps the menu open for addons with secondary interactions
- Left- or right-click the minimap launcher to toggle the menu
- Drag the launcher around the edge of the minimap
- Drag the menu by its title to move it independently
- Launcher and menu positions are saved per character
- Close button and Escape key support
- Automatically rescans for addon buttons created after login
- Includes support for Turtle WoW's Battleground Finder and Shop buttons

## Commands

- `/mmenu` — Show command help
- `/mmenu rescan` — Search for newly created minimap buttons
- `/mmenu list` — List all collected button frame names
- `/mmenu reset` — Reset the launcher and menu positions
- `/minimapmenu` — Full-length alternative to `/mmenu`

## Compatibility

MinimapButtonBag must be disabled while using MinimapMenu. Both addons move the original minimap button frames and cannot safely manage them at the same time.
