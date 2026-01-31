

# Niri / Keybind




## Subject

* [System](#system)
* [Application](#application)
* [Window](#window)
* [Screenshot](#screenshot)
* [Brightness](#brightness)
* [Volume](#volume)




## System

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Shift + x`          | Exit                        | spawn `wlogout`                       |
| `Alt + Ctrl + x`           | Logout                      | `quit`                                |
| `Alt + Ctrl + Delete`      | Logout                      | `quit`                                |

> run `yay -Sy --needed wlogout` to install `wlogout`


| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Shift + z`          | Lock                        | spawn `swaylock`                      |
| `Alt + Ctrl + z`           | Monitors Power Off          | `power-off-monitors`                  |


| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Ctrl + l`           | Lock                        | spawn `swaylock`                      |
| `Alt + Ctrl + p`           | Monitors Power Off          | `power-off-monitors`                  |

> run `yay -Sy --needed swaylock` to install `swaylock`




## Application


### Application / Launcher

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Shift + d`          | Launcher drun               | spawn `rofi -show drun`               |
| `Alt + Shift + r`          | Launcher run                | spawn `rofi -show run`                |


### Application / Terminal

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Enter`              | Terminal                    | spawn `xfce4-terminal`                |
| `Alt + Shift + a`          | Terminal                    | spawn `xfce4-terminal`                |
| `Alt + Ctrl + a`           | Terminal                    | spawn `foot`                          |
| `Alt + Shift + t`          | Terminal                    | spawn `sakura`                        |
| `Alt + Ctrl + t`           | Terminal                    | spawn `kitty`                         |


### Application / Favorite

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Shift + f`          | File Manager                | spawn `thunar`                        |
| `Alt + Shift + g`          | File Manager                | spawn `pcmanfm`                       |
| `Alt + Shift + e`          | Text Editor                 | spawn `mousepad`                      |
| `Alt + Shift + b`          | Web Browser                 | spawn `firefox --new-tab about:blank` |
| `Alt + Shift + v`          | Volume Control              | spawn `pavucontrol`                   |
| `Alt + Shift + n`          | Network Connection          | spawn `kitty --class 'nmtui' --title 'Network Settings' nmtui`  |




## Window


### Window / Close

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + q`                | Window Close                | `close-window`                        |
| `Alt + F4`                 | Window Close                | `close-window`                        |


### Window / Fullscreen

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + f`                | Window Toggle Fullscreen    | `fullscreen-window`                   |


### Window / Resize

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + Ctrl + Up`        | Window Resize               | `set-window-height "-5%"`             |
| `Super + Ctrl + Down`      | Window Resize               | `set-window-height "+5%"`             |
| `Super + Ctrl + Left`      | Window Resize               | `set-column-width "-5%"`              |
| `Super + Ctrl + Right`     | Window Resize               | `set-column-width "+5%"`              |


| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + Ctrl + k`         | Window Resize               | `set-window-height "-5%"`             |
| `Super + Ctrl + j`         | Window Resize               | `set-window-height "+5%"`             |
| `Super + Ctrl + h`         | Window Resize               | `set-column-width "-5%"`              |
| `Super + Ctrl + l`         | Window Resize               | `set-column-width "+5%"`              |




## Screenshot

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Print`                    | Screenshot Fullscreen       | `screenshot-screen`                   |
| `Super + Print`            | Screenshot Window           | `screenshot-window`                   |
| `Ctrl + Print`             | Screenshot Region           | `screenshot`                          |




## Brightness

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `XF86MonBrightnessDown`    | Brightness Up               | spawn `brightnessctl set +5%`         |
| `XF86MonBrightnessUp`      | Brightness Down             | spawn `brightnessctl set 5%-`         |

> run `sudo pacman -Sy --needed brightnessctl` to install `brightnessctl`




## Volume

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `XF86AudioMute`            | Volume Mute                 | spawn `pamixer --toggle-mute`         |
| `XF86AudioRaiseVolume`     | Volume Up                   | spawn `pamixer -i 5`                  |
| `XF86AudioLowerVolume`     | Volume Down                 | spawn `pamixer -d 5`                  |

> run `sudo pacman -Sy --needed pamixer` to install `pamixer`
