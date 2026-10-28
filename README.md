# Prism releases

Public installers for the Prism browser (PromethionTech). Source stays private.

## Install

1. Download `PrismSetup.exe` from the [latest release](https://github.com/Promethion-Dev-Tech/prism-releases/releases/latest).
2. Run it. If SmartScreen warns, click **More info** then **Run anyway** (builds are not Authenticode-signed yet).
3. Prism installs per-user under `%LOCALAPPDATA%\PromethionTech\Prism`.

The installer also registers an updater. About every four hours, and at logon, it checks this repository's `latest.json` and installs newer versions.

Current: **0.16.1**
