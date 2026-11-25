# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), versions follow [Semantic Versioning](https://semver.org/).

## [Unreleased]

### Fixed
- card-mod: keyboard focus on tiles is a 2 px ring in the focus colour (gold in dark mode, dark celadon in light mode) in the grout around the tile. Before, a lit tile hid the frontend's thin focus ring completely, and on other tiles it was 1 px in the state colour.

## [1.1.1] - 2026-11-25

### Fixed
- Light mode: text of plain buttons and active tabs was too faint (3.6:1). It now uses the dark celadon (5.5:1).
- Switches in current frontends ignored the old switch colours; they are gold now, like the sliders.
- The keyboard focus ring is gold in dark mode and dark celadon in light mode instead of the default grey.
- Light mode: the heating arc of the thermostat uses a darker gold, so the half-transparent arc stays visible on pale glaze.
- Error, red and blue are hex values again, so tinted error surfaces and badges get the glaze colours too.
- card-mod: the sidebar uses the text font of the cards, its title the Didone serif. A water heater lights its tile in any mode except off.

### Changed
- Removed the thermostat ring variables: the frontend sets them on the ring itself, so they never took effect. The rings keep the heating and cooling colours.
- Screenshots: light mode without card-mod and settings in light mode added; the entities card now shows a switch.
- The serif stack tries Noto Serif Display earlier. README: what changes on Android and Linux, and which parts of the mock a theme cannot reach.

## [1.1.0] - 2026-11-25

### Changed
- Narrower grout: one 6 px joint between tiles in a section (was 10 px), and small ceramic corners for buttons, sliders, dialogs and badges.
- Icons sit on small square inlays instead of circles; tile controls (brightness, position) get square corners too.
- State colours as four glazes: celadon for running or secure, gold for warmth and attention, cobalt for cooling, oxblood for open or alarm. Covers, locks, alarms, vacuums, valves and people now follow them instead of the default colours.
- card-mod: a tile lights up by its state (on, open, playing, heating, cleaning ...) instead of by a list of device kinds. A paused player or a closed cover stays dark. Sliders on a lit tile use a deeper glaze, so they stay visible (before: the light's own colour or the same celadon as the tile).
- card-mod: the selected sidebar entry keeps the normal selection overlay.
- Screenshots show tile controls (brightness, position) and the new colours.

## [1.0.0] - 2026-11-24

### Added
- First release: one theme with light and dark mode.
- Every card is a glazed tile with a soft bulge and a gloss edge, the gaps between cards are the grout. Works without add-ons.
- Gold for thermostat rings, sliders and gauges; Didone serif from the system for titles and big numbers.
- Optional card-mod rules: tiles of switched-on devices become a bright celadon tile, sidebar entries become small tiles, dashboard title and section headings use the Didone serif.
