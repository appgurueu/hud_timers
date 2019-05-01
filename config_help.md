# HUD Timers - Configuration

## Locations

JSON Configuration : `<worldpath>/config/hud_timers.json`

Text Logs : `<worldpath>/logs/hud_timers/<date>.json`

Explaining document(this, Markdown) : `<modpath/gamepath>/hud_timers/config_help.md`

Readme : `<modpath/gamepath>/hud_timers/Readme.md`

## Default Configuration
Located under `<modpath/gamepath>/hud_timers/default_config.json`
```json
{
  "hud_pos" : {"x": 0,"y": 0},
  "globalstep" : 0.1,
  "hud_timers_max" : 10,
  "format" : "%s : %s s"
}
```

## Usage

### `hud_pos`
Screen coordinates where the timer stack should start.

### `globalstep`
How often timers should be updated(interval, seconds).

### `hud_timers_max`
How many timers(maximum) may exist at a time.

### `format` : "%s : %s s"
The format for the timer label - first string is timer name, second one is seconds left.
