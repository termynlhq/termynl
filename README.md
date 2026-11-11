# termynl apps

Downloads for the termynl desktop app and termynl Sync are on the [Releases](https://github.com/termynlhq/termynl/releases) page. This repository holds releases only.

Every file is signed. To check a download:

```
gpg --import termynl-release.asc
gpg --verify SHA256SUMS.asc SHA256SUMS
sha256sum -c SHA256SUMS --ignore-missing
```

Learn more at [termynl.com](https://termynl.com).
