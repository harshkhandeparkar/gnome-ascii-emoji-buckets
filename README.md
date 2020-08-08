# ASCII Emoji Buckts
Emoji Buckets is a shell extension for the [GNOME](https://www.gnome.org/) desktop.

## About
This is a fork of the GNOME shell extensions [emoji-buckets](https://github.com/harlemsquirrel/gnome-emoji-buckets) with ASCII emojis (¯\\\_(ツ)_/¯) instead of normal ones :shrug:

## Installation


### Install manually
These are UTF-8 symbols so it should work on almost every system without any extra fonts, yay!

#### Option 1
You can download [this](gnome-ascii-emoji-installer.sh) script and run it locally to install the latest version.

#### Option 2
You can install this extension by downloading a released version and extracting the files into the following directory.
```
~/.local/share/gnome-shell/extensions/ascii_emoji_buckets@HarshKhandeparkar
```

Log out or restart the GNOME shell to make it available in GNOME Tweak. Note that on Wayland restarting the GNOME shell is not working as of 3.22.2.

## Troubleshooting

One of the best ways to troubleshoot is to watch the logs with `journalctl` and restart the extension. You can reload this extension with the handy [Gnome Shell Extension Reloader](https://extensions.gnome.org/extension/1137/gnome-shell-extension-reloader/) extension.

```
journalctl --since="`date '+%Y-%m-%d %H:%M'`" -f | grep ascii_emoji_buckets
```

> Go support the original developer [harlemsquirrel](https://github.com/harlemsquirrel)
