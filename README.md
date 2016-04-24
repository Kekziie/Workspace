# Kim

## Terminal Kommandos:

### Versteckte Files anzeigen.

```sh
$ defaults write com.apple.finder AppleShowAllFiles 1
$ killall Finder
```

### Versteckte Files verstecken.

```sh
$ defaults write com.apple.finder AppleShowAllFiles 0
$ killall Finder
```

### Homebrew installieren.

```sh
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
