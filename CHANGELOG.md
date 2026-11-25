# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), versions follow [Semantic Versioning](https://semver.org/).

## [Unreleased]

### Changed
- Narrower grout: one 6 px joint between tiles in a section (was 10 px), and small ceramic corners for buttons, sliders, dialogs and badges.
- Icons sit on small square inlays instead of circles; tile controls (brightness, position) get square corners too.
- State colours as four glazes: celadon for running or secure, gold for warmth and attention, cobalt for cooling, oxblood for open or alarm. Covers, locks, alarms, vacuums, valves and people now follow them instead of the default colours.
- card-mod: a tile lights up by its state (on, open, playing, heating, cleaning ...) instead of by a list of device kinds. A paused player or a closed cover stays dark. Sliders on a lit tile use a deeper glaze, so they stay visible (before: the light's own colour or the same celadon as the tile).
- card-mod: the selected sidebar entry keeps the normal selection overlay.

## [1.0.0] - 2026-11-24

### Added
- First release: one theme with light and dark mode.
- Every card is a glazed tile with a soft bulge and a gloss edge, the gaps between cards are the grout. Works without add-ons.
- Gold for thermostat rings, sliders and gauges; Didone serif from the system for titles and big numbers.
- Optional card-mod rules: tiles of switched-on devices become a bright celadon tile, sidebar entries become small tiles, dashboard title and section headings use the Didone serif.
