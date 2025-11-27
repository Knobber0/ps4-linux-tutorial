# Awesome Optimizations

| AwesomeWM tweaks                       | Description                                                                      |
|----------------------------------------|----------------------------------------------------------------------------------|
| beautiful.border_width = 1             | 1-pixel borders only                                                             |
| beautiful.border_normal = "#000000"    | Black borders                                                                    |
| beautiful.border_focus = "#000000"     | No color change on focus                                                         |
| beautiful.useless_gap = 0              | Zero gaps everywhere                                                             |
| beautiful.titlebar_enabled = false     | No title bars – huge FPS win                                                     |
| awful.rules: floating + no borders     | Floating windows get 1px border only                                             |
| No shadow widgets                      | client:disconnect_signal("shadow") or just don’t use them                        |
| No client animations                   | Disable all wibox/titlebar animations                                            |
| Solid black wallpaper                  | awful.screen.connect_for_each_screen(function(s) gears.wallpaper.solid("#000000") end) |
| Wibar height = 18                      | Tiny top bar                                                                     |
| Font: "fixed 8" or "Terminus 8"        | Bitmap font – zero GPU cost                                                      |
| Picom: shadow = false                  | No shadows                                                                       |
| Picom: fading = false                  | No fades                                                                         |
| Picom: blur = none                     | Blur off                                                                         |
| Picom: corner-radius = 0               | Sharp corners                                                                    |
| Picom flags: --vsync --glx-no-stencil  | Minimal tear-free compositing                                                    |
| AQ_NO_MODIFIERS=1                      | Fixes stuttering and DDB errors
| RADV_PERFTEST=nggc,rt,sco                      | Enables Next Generation Geometry Culling, Rasterizer Toggle and Shader Cache Optimizations |