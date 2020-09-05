<div align="center">
    <h1>bspwm Palenight dotfiles</h1>
</div>

[![HitCount](http://hits.dwyl.com/yurywektorovich/dotfiles.svg)](http://hits.dwyl.com/yurywektorovich/dotfiles)

##### Setup:
+ **OS**: manjaro
+ **Shell**: zsh
+ **Terminal:** urxvt
+ **Notification:** dunst
+ **Powermenu:** rofi
+ **File Manager**: thunar
+ **Bar:** polybar (limepanel)
+ **Spotify theme:** 
+ **Browser:** vivaldi
+ **Editor**: vscode
+ **Color Scheme**: palenight

# <center>Screenshots</center>
<p>
  <img width="70%" src="https://github.com/yurywektorovich/dotfiles/blob/master/pictures/rice/_01.png?raw=true" />
  <img width="70%" src="https://raw.githubusercontent.com/yurywektorovich/dotfiles/master/pictures/rice/_02.png" />
  <img width="70%" src="https://github.com/yurywektorovich/dotfiles/blob/master/pictures/rice/_03.png?raw=true" />
</p>

<a name="appTheming"></a>
## Application Theming ##

### Spotify ###
1. [Install `Spicetify`](https://github.com/khanhas/spicetify-cli)
2. chown spotify directory: `sudo chown $USER -R /opt/spotify`
3. run `spicetify` once to generate config
4. `spicetify backup apply enable-devtool` to enable devtools
5. Copy my spicetify folder to `~/.config`
6. run `spicetify update restart`