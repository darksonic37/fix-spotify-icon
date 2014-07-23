# fix-spotify-icon

Since Ubuntu 14.04, Spotify uses a low resolution icon in the system tray. It's not too difficult to fix it the first time. But the icon is overwritten whenever Spotify updates. In other words, you have to fix the icon every time Spotify is updated.

This script minimizes the pain with a simple `fix-spotify-icon` command that you can run when the Spotify icon breaks.

## Installation

1. Download the script using either `wget` or `curl`:

```shell
$ wget -O fix-spotify-icon.sh https://raw.githubusercontent.com/faviouz/fix-spotify-icon/master/fix-spotify-icon.sh
```

```shell
$ curl -L -s -S https://raw.githubusercontent.com/faviouz/fix-spotify-icon/master/fix-spotify-icon.sh > fix-spotify-icon.sh
```

2. `chmod` the script and move it:

```shell
$ chmod +x fix-spotify-icon.sh
$ sudo mv fix-spotify-icon.sh /usr/local/bin/fix-spotify-icon
```

## Usage

When the Spotify icon breaks you just have to run:

```shell
$ fix-spotify-icon
```
