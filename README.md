# nodusretis-org
Prereleases NodusRetis (alpha tests)

The installers are on the [latest release](https://github.com/wvmscs/nodusretis-org/releases/latest).
Each release has one file to check them, `SHA256SUMS.asc`: the SHA-256 of every file,
signed with the GPG key [`signer.pub.asc`](signer.pub.asc)
(`9934918FAC077C3D02BFFF1D405354B48708C96F`).

```sh
gpg --import signer.pub.asc
gpg --verify SHA256SUMS.asc
sha256sum -c SHA256SUMS.asc --ignore-missing   # macOS: shasum -a 256 -c SHA256SUMS.asc --ignore-missing
```
