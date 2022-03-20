# ASCII Emoji Buckts
Emoji Buckets is a shell extension for the [Gnome](https://www.gnome.org/) desktop.

## About
This is a fork of the GNOME shell extensions [emoji-buckets](https://github.com/harlemsquirrel/gnome-emoji-buckets) with ASCII emojis (¯\\\_(ツ)_/¯) instead of normal ones :shrug:

## Installation

#### Option 1
Install it from the official gnome extensions website, [here](https://extensions.gnome.org/extension/3408/ascii-emoji-buckets/).

#### Option 2
You can download [this](ascii-emoji-installer.sh) script and run it locally to install the latest version.

#### Option 3
You can install this extension by downloading a released version and extracting the files into the following directory.
```
~/.local/share/gnome-shell/extensions/ascii_emoji_buckets@HarshKhandeparkar
```

Log out or restart the Gnome shell and enable it in Gnome Extensions or Gnome Tweaks app.

## Troubleshooting

One of the best ways to troubleshoot is to watch the logs with `journalctl` and restart the extension. You can reload this extension with the handy [Gnome Shell Extension Reloader](https://extensions.gnome.org/extension/1137/gnome-shell-extension-reloader/) extension.

```
journalctl --since="`date '+%Y-%m-%d %H:%M'`" -f | grep ascii_emoji_buckets
```

> Go support the original developer [harlemsquirrel](https://github.com/harlemsquirrel)
