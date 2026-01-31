

# Niri / Keybind




## Subject

* [System](#system)
* [Application](#application)
* [Screenshot](#screenshot)
* [Brightness](#brightness)
* [Volume](#volume)




## System

| Keybind                | Action                     | Command                             |
| ---------------------- | -------------------------- | ----------------------------------- |
| `Alt + Shift + x`      | Exit                       | `wlogout`                           |
| `Alt + Ctrl + x`       | Logout                     | `quit`                              |
| `Alt + Ctrl + Delete`  | Logout                     | `quit`                              |

> run `yay -Sy --needed wlogout` to install `wlogout`


| Keybind                | Action                     | Command                             |
| ---------------------- | -------------------------- | ----------------------------------- |
| `Alt + Shift + z`      | Lock                       | `swaylock`                          |
| `Alt + Ctrl + z`       | Monitors Power Off         | `power-off-monitors`                |


| Keybind                | Action                     | Command                             |
| ---------------------- | -------------------------- | ----------------------------------- |
| `Alt + Ctrl + l`       | Lock                       | `swaylock`                          |
| `Alt + Ctrl + p`       | Monitors Power Off         | `power-off-monitors`                |

> run `yay -Sy --needed swaylock` to install `swaylock`







## Screenshot

| Keybind              | Action                     | Command                             |
| -------------------- | -------------------------- | ----------------------------------- |
| `Print`              | Screenshot Fullscreen      | `screenshot-screen`                 |
| `Super + Print`      | Screenshot Window          | `screenshot-window`                 |
| `Ctrl + Print`       | Screenshot Region          | `screenshot`                        |




## Brightness

| Keybind                  | Action                     | Command                             |
| ------------------------ | -------------------------- | ----------------------------------- |
| `XF86MonBrightnessDown`  | Brightness Up              | `brightnessctl set +5%`             |
| `XF86MonBrightnessUp`    | Brightness Down            | `brightnessctl set 5%-`             |

> run `sudo pacman -Sy --needed brightnessctl` to install `brightnessctl`




## Volume

| Keybind                   | Action                     | Command                             |
| ------------------------- | -------------------------- | ----------------------------------- |
| `XF86AudioMute`           | Volume Mute                | `pamixer --toggle-mute`             |
| `XF86AudioRaiseVolume`    | Volume Up                  | `pamixer -i 5`                      |
| `XF86AudioLowerVolume`    | Volume Down                | `pamixer -d 5`                      |

> run `sudo pacman -Sy --needed pamixer` to install `pamixer`
