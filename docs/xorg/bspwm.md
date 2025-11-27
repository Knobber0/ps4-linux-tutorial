# Bspwm Optimizations

| Bspwm tweaks                           | Description                                                                      |
|----------------------------------------|----------------------------------------------------------------------------------|
| border_width 1                         | 1-pixel borders only                                                             |
| window_gap 0                           | Zero gaps everywhere                                                             |
| borderless_monocle true                | No borders when only one window on workspace                                    |
| gapless_monocle true                   | No gaps in monocle mode                                                          |
| single_monocle true                    | Forces monocle when only one window                                              |
| focus_follows_pointer false            | No expensive mouse tracking                                                     |
| Picom: shadow = false                  | No shadows                                                                       |
| Picom: fading = false                  | No fades                                                                         |
| Picom: blur = none                     | Blur off                                                                         |
| Picom: corner-radius = 0               | Sharp corners                                                                    |
| Picom flags: --vsync --glx-no-stencil  | Minimal tear-free compositing                                                    |
| AQ_NO_MODIFIERS=1                      | Fixes stuttering and DDB errors                                                  |
| RADV_PERFTEST=nggc,rt,sco                      | Enables Next Generation Geometry Culling, Rasterizer Toggle and Shader Cache Optimizations |