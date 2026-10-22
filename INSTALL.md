# Installing a Codewhale Desktop preview

Download the file for your platform from [Releases](../../releases) and check
its SHA-256 against the `SHA256SUMS.txt` in the same release.

## macOS (Apple silicon)

1. Open the `.dmg` and drag **Codewhale** into **Applications**.
2. Open Codewhale from Applications.

The macOS build is signed and notarized by Apple, so it opens normally.

## Windows (x64), experimental

1. Unzip the archive into a folder you own, for example
   `%LOCALAPPDATA%\Codewhale`.
2. Run `launch.cmd` from that folder.

This build is not code-signed yet. Windows SmartScreen may say it "protected
your PC". Choose **More info**, then **Run anyway**, only if the file's
checksum matches the release.

## Linux (x64), experimental

1. Extract the archive: `tar -xzf codewhale-*.tar.gz`.
2. Run `./launch.sh` from the extracted folder.

This build is not signed. It needs a desktop session (X11 or Wayland).

## First run

Codewhale asks you to connect a model provider. Add your own API key in
Settings, Models. The key is stored on your computer.

## Updates

Preview builds don't update themselves yet. Download the next release when it
is published.
