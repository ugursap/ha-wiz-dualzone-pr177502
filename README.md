# WiZ dual zone (temporary)

Home Assistant's core `wiz` integration from **2026.10.2**, with
[home-assistant/core#177502](https://github.com/home-assistant/core/pull/177502)
applied (`pywizlight==0.6.6`). Zone-based dual-head WiZ lights (Squire, HALO
RL Dual Zone) get separate **Zone A** / **Zone B** light entities; the Zone A
entity keeps the original unique ID.

Only additions on top of the PR: `version` in `manifest.json` and a resolved
`translations/en.json` (custom components can't use `strings.json` key refs).

Temporary: remove from HACS and restart once #177502 is released in core.
