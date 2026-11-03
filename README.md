# mectl Releases

Prebuilt binaries for the mectl command-line client. Application source is maintained
privately; this repository contains distribution information and release assets only.
Using mectl requires company network access and appropriate credentials.

## Homebrew

Supported: Apple Silicon and Intel macOS, and Linux x86-64.

```sh
brew install janfonas/tap/mectl
mectl version
```

To upgrade, run `brew update` followed by `brew upgrade mectl`.

## Manual Downloads

Download the archive for your platform from [Releases](https://github.com/janfonas/mectl-releases/releases).
macOS and Linux archives contain `mectl`; Windows archives contain `mectl.exe`.
Extract the archive and place the executable in a directory on your `PATH`.
Linux ARM64 is not currently supported.

Each release provides `SHA256SUMS`. Verify the downloaded archive with a SHA-256 tool
before installing it. Preserve `THIRD_PARTY_NOTICES.txt` when redistributing the binary;
it is included in every archive and provided as a separate release asset.

Public availability of binaries does not grant an open-source license to mectl.
Third-party components retain the terms recorded in their accompanying notices.