# Codewhale Desktop

The Codewhale desktop app for macOS, Windows and Linux.

Codewhale runs on your computer with your own model provider key. The
desktop app needs a free Codewhale account: choose **Sign in** or **Create
account** and finish in your browser. Your model key stays on your computer,
and your provider bills you directly for what you use. The `codewhale`
terminal app works without an account.

Codewhale computers, cloud computers your agents can work on, are
invite-only for now.

> **Status: preview.** The source code will be published here soon. Until
> then, this repository hosts preview builds for testers and the place to
> report problems.

## Download

Preview builds are published under [Releases](../../releases). Each release
lists the app version and the Codewhale Engine version it bundles, with
SHA-256 checksums.

| Platform | Build |
| --- | --- |
| macOS (Apple silicon) | Signed and notarized `.dmg` |
| Windows (x64) | Unsigned `.zip`, experimental |
| Linux (x64) | Unsigned `.tar.gz`, experimental |

See [INSTALL.md](INSTALL.md) for install steps and what to expect from the
unsigned builds.

## Feedback

Please report problems and ideas in [Issues](../../issues). Include your
platform, the app version from the About screen, and steps to reproduce.
Never paste API keys or other secrets into an issue.

## Related

- [Codewhale Engine and CLI](https://github.com/codewhale-hq/Codewhale), the
  open-source agent runtime the app bundles.

## License

Apache License 2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE). The
Codewhale name and marks are covered by [TRADEMARKS.md](TRADEMARKS.md).
