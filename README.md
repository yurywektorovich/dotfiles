<div align="center">
    <h1>bspwm Palenight dotfiles</h1>
</div>

[![HitCount](http://hits.dwyl.com/yurywektorovich/dotfiles.svg)](http://hits.dwyl.com/yurywektorovich/dotfiles)

### Contents

1. [Setup](#setup)
2. [Fonts](#fonts)
3. [Dependencies](#dependencies)
4. [Screenshots](#screenshots)
5. [Application Theming](#appTheming)

<a name="setup"></a>

### Setup

- **OS**: Manjaro
- **Shell**: Zsh
- **WM**: bspwm
- **Terminal:** urxvt
- **Notification:** Dunst
- **Powermenu:** Rofi
- **File Manager**: Thunar
- **Bar:** Polybar (limepanel)
- **Browser:** Vivaldi
- **Editor**: VScode
- **Color Scheme**: Palenight
- **GTK3 Theme**: Juno
- **Icons**: OieOxy
- **Cursor**: Breeze Hacked

<a name="fonts"></a>

#### Fonts

- Fira Code
- Nerd Font Icons

<a name="dependencies"></a>

### Dependencies

| Dependency |                                  Description                                  |
| :--------: | :---------------------------------------------------------------------------: |
|  `bspwm`   |                                Window manager                                 |
|   `feh`    |              Fast image viewer used as wallpaper setting utility              |
|  `picom`   | Window compositor, eliminates screen tearing and allows for cool fade effects |
|   `rofi`   |                             Application launcher                              |

<a name="screenshots"></a>

### <center>Screenshots</center>

<p>
  <img width="83%" src="https://raw.githubusercontent.com/yurywektorovich/dotfiles/master/pictures/rice/_001.png" />
  <img width="83%" src="https://raw.githubusercontent.com/yurywektorovich/dotfiles/master/pictures/rice/_002.png" />
  <img width="83%" src="https://raw.githubusercontent.com/yurywektorovich/dotfiles/master/pictures/rice/_003.png" />
  <img width="83%" src="https://raw.githubusercontent.com/yurywektorovich/dotfiles/master/pictures/rice/_004.png" />
</p>

<a name="appTheming"></a>

### Application Theming

#### Spotify

1. [Install `Spicetify`](https://github.com/khanhas/spicetify-cli)
2. chown spotify directory: `sudo chown $USER -R /opt/spotify`
3. run `spicetify` once to generate config
4. `spicetify backup apply enable-devtool` to enable devtools
5. Copy my spicetify folder to `~/.config`
6. run `spicetify update restart`
