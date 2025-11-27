# Dwm Optimizations

| Dwm tweaks (patch or config.h)         | Description                                                                      |
|----------------------------------------|----------------------------------------------------------------------------------|
| Border width = 1                       | Thin borders only                                                               |
| Gaps = 0                               | No gaps anywhere (set both inner and outer to 0)                                 |
| Swallow patch                          | Enable swallowing – terminal eats compile windows, saves GPU                    |
| Hide vacant tags                       | Tags with no windows disappear – cleaner bar                                     |
| No animations                          | dwm has zero built-in animations – already perfect                              |
| No transparency                        | All colors solid (no alpha)                                                      |
| Bar height = 18                        | Tiny bar – less redraw                                                           |
| Font: fixed or terminus 8              | Tiny bitmap font – zero GPU cost                                                 |
| Picom: shadow = false                  | No shadows                                                                       |
| Picom: fading = false                  | No fades                                                                         |
| Picom: blur = none                     | Blur off                                                                         |
| Picom: corner-radius = 0               | Sharp corners                                                                    |
| Picom flags: --vsync --glx-no-stencil  | Minimal compositing                                                              |
| AQ_NO_MODIFIERS=1                      | Fixes stuttering                                                                 |
| RADV_PERFTEST=nggc,rt,sco                      | Enables Next Generation Geometry Culling, Rasterizer Toggle and Shader Cache Optimizations |