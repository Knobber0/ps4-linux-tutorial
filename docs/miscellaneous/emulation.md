# This page will cover on how to install multiple emulators on multiple distros


## 1 - Arch based distros

- **NOTE: I will be using yay mostly because pacman may not have all packages.**

::: details Retroarch

- Install these 3 packages using the command provided below:
- `yay -S retroarch-assets-xmb --noconfirm`
- `yay -S retroarch-assets-ozone --noconfirm`
- `sudo pacman -S retroarch --noconfirm`
:::


::: details PCSX2


- Just install by running `yay -S pcsx2 --noconfirm`

:::


::: details Dolphin

- Just install by running `yay -S dolphin-emu --noconfirm`

:::

::: details Rpcs3

- Just install by running `yay -S rpcs3-bin --noconfirm`

- Also install *rpcs3-udev* with `yay -S rpcs3-udev --noconfirm`

- *rpcs3-udev* is need for the emulator to be able to utilize ps4 and ps3 controllers.

:::


::: details PPSSPP

- Just install by running `yay -S ppsspp --noconfirm`

:::


::: details Duckstation

- Just install by running `yay -S duckstation-gpl --noconfirm`

:::


## 2 - Debian based distros

::: details Retroarch

- Just install by running `sudo add-apt-repository ppa:libretro/stable && sudo apt-get update && sudo apt-get install retroarch`
:::


::: details PCSX2


- Just install by running `sudo add-apt-repository ppa:pcsx2-team/pcsx2-daily && sudo apt-get update && sudo apt-get install pcsx2-stable`

:::


::: details Dolphin

- Just install by running `sudo add-apt-repository ppa:ubuntuhandbook1/dolphin-emu && sudo apt-get update && sudo apt-get install dolphin-emu`

:::

::: details Rpcs3

- Just install by running `yay -S rpcs3-bin --noconfirm`

- Also install *rpcs3-udev* with `yay -S rpcs3-udev --noconfirm`

- *rpcs3-udev* is need for the emulator to be able to utilize ps4 and ps3 controllers.

:::


::: details PPSSPP

- Just install by running `yay -S ppsspp --noconfirm`

:::


::: details Duckstation

- Just install by running `yay -S duckstation-gpl --noconfirm`

:::
