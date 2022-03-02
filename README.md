# I just didn't like the Icons It used, I like my panel small and current icon was barely visible, So I changed them, there are no further changes
### If you wanna put these icons in your currently installed extension, copy my icons and put it inside ~/.local/share/gnome-shell/extensions/caffeine@patapon.info/icons

## gnome-shell-extension-caffeine

Click to inhibit auto suspend and screensaver.

This extension supports gnome-shell 3.4 to 41

* master: 40 -> 41
* gnome-shell-3.36-3.38: 3.36 -> 3.38
* gnome-shell-3.32-3.34: 3.32 -> 3.34
* gnome-shell-3.10-3.30: 3.10 -> 3.30
* gnome-shell-before-3.10: 3.4 -> 3.8

![Screenshot](https://github.com/rishuinfinity/gnome-shell-extension-caffeine/raw/master/screenshot.png)

![Preferences](https://github.com/rishuinfinity/gnome-shell-extension-caffeine/raw/master/screenshot-prefs.png)

Empty circle = normal auto suspend and screensaver. Filled circle = auto suspend and
screensaver off.

## Installation from e.g.o

https://extensions.gnome.org/extension/517/caffeine/

## Installation from git

```sh
git clone git://github.com/rishuinfinity/gnome-shell-extension-caffeine.git
cd gnome-shell-extension-caffeine
./update-locale.sh
glib-compile-schemas --strict --targetdir=caffeine@patapon.info/schemas/ caffeine@patapon.info/schemas
cp -r caffeine@patapon.info ~/.local/share/gnome-shell/extensions
```

Restart the shell and then enable the extension.
