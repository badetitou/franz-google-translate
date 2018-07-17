# Textto for Franz

An unofficial [Franz](https://meetfranz.com/) recipe for [Google Translate](https://translate.google.com/).

## Installing

### Windows

With git and PowerShell:

```bash
mkdir $env:APPDATA\Franz\recipes\dev\
git clone git@github.com:badetitou/franz-google-translate.git $env:APPDATA\Franz\recipes\dev\franz-google-translate
```

With Explorer:

1. Download the `franz-google-translate.zip` from github.  Extract it to its own folder (`franz-google-translate`).
2. Open `%appdata%/Franz/recipes/dev/`.  The `dev` folder may not exist, so go ahead and create it.
3. Copy the `franz-google-translate` folder into the plugins directory.
4. Reload Franz.

### Mac

```bash
mkdir ~/Library/Application\ Support/Franz/recipes/dev/
git clone git@github.com:badetitou/franz-google-translate.git ~/Library/Application\ Support/Franz/recipes/dev/franz-google-translate
```

### Linux

```bash
mkdir ~/.config/Franz/recipes/dev
git clone git@github.com:badetitou/franz-google-translate.git ~/.config/Franz/recipes/dev/franz-google-translate
```