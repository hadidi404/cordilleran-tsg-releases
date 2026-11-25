# Cordilleran TSG Releases

Official Android builds for the Digitalized Learning Platform of the "Digitalization of Cordilleran Sports and Games with AI Analytics" Project.

## Install

Download and install the Cordilleran TSG Launcher. It installs the game and keeps it updated automatically.

## For the team

Each release needs two files:

- `game.apk`
- `version.json`

Example `version.json`:

```json
{
  "versionCode": 1,
  "versionName": "1.0.0",
  "minVersionCode": 1,
  "notes": "First release"
}
```

Bump the Bundle Version Code in Unity before every build and always sign with the same keystore.

## App Versions

### AB Testing Version
[Download Build](https://github.com/hadidi404/cordilleran-tsg-releases/releases/download/1.4-ab/CordilleranTSG-AB-0.1.0-10.apk)   

This version of the app contains two versions of screen layouts and/or input controls for each of the 3 games inside it where the player must choose a version to test.

