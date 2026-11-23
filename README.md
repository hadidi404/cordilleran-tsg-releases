# Cordilleran TSG Releases

Official Android builds for Cordilleran TSG.

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
