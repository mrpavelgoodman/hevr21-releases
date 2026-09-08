# hevR-21 releases

Desktop builds of [hevR-21](https://hevr21.com), published here so the download
page has somewhere public to point. The application source is not in this
repository; only the release assets are.

Each release carries:

| File | System |
| --- | --- |
| `hevR-21-<version>-universal.dmg` | macOS 12 or later, Intel and Apple Silicon |
| `hevR-21-<version>-x64-Setup.exe` | Windows 10 or later, x64 |
| `hevR-21-<version>-x64-Portable.zip` | Windows, no installer |
| `hevR-21-<version>-amd64.deb` | Debian, Ubuntu and derivatives, x86-64 |

`SHA256SUMS.txt` is attached to every release. Verify a download against it
before installing:

```bash
shasum -a 256 -c SHA256SUMS.txt --ignore-missing
```

The builds are not code signed yet, so macOS and Windows both warn on first
launch. https://hevr21.com/download has the steps for each system.

Issues and questions: goodmandzen@gmail.com
