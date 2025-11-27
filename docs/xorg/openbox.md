# OpenBox Optimizations

| Openbox tweaks                         | Description                                                                      |
|----------------------------------------|----------------------------------------------------------------------------------|
| Titlebar height = 0                    | No title bars                                                 |
| Border width = 1px                     | Thin borders only                                                                |
| All shadows off                       | Shadows are death on PS4                                                         |
| All animations off                     | Zero fade/snapping                                                               |
| Margins = 0 everywhere                 | No wasted screen space                                                           |
| Desktop icons disabled                 | Right-click menu off                                                             |
| Picom: shadow = false                  | No shadows                                                                       |
| Picom: fading = false                  | No fades                                                                         |
| Picom: blur = none                     | Blur off                                                                         |
| Picom: corner-radius = 0               | Sharp corners                                                                    |
| Picom flags: --vsync --glx-no-stencil  | Minimal compositing                                                              |
| AQ_NO_MODIFIERS=1                      | Stops stuttering and DDB spam                                                    |
| RADV_PERFTEST=nggc,rt,sco		   	       | Enables Next Generation Geometry Culling,Rasterizer Toggle and Shader Cache Optimizations. |