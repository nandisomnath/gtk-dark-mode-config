# GTK-DARK-MODE-CONFIG

There is two version of gtk is currently used  gtk-3.0
and gtk-4.0 , we will config it differently using 
`.config` folder in other directory and also we can use
`gsettings` if possible. Also we will use shell env variable for basic configs


# Clone 

clone this repo to copy config files

```bash
git clone https://github.com/nandisomnath/gtk-dark-mode-config.git
cd gtk-dark-mode-config
```

your current directory have to `gtk-dark-mode-config` to run other commands


## Configuration

We will make the config as general as possible.

> [!TIP]
> For gnome you should check `dconf` settings. gnome use `dconf` for 
> their global setting including theme.

you can use almost all desktop environments for this 
Follow the steps:

1. gtk-3.0 config

```bash
mkdir -p ~/.config/gtk-3.0
cp  .config/gtk-3.0/settings.ini ~/.config/gtk-3.0/
```

2. gtk-4.0 config

```bash
mkdir -p ~/.config/gtk-4.0
cp  .config/gtk-4.0/settings.ini ~/.config/gtk-4.0/
```
