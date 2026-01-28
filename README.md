# Planet Samson Desktop

Release artifacts for Planet Samson Desktop application.

## Install

### macOS / Linux (Homebrew)

```bash
brew tap planetsamson/tap
brew install planetsamson
```

### macOS

Download the `.dmg` installer from [Releases](https://github.com/planetsamson/desktop-releases/releases), open it, and drag Planet Samson to your Applications folder.

### Linux

**Debian/Ubuntu (.deb):**
```bash
sudo dpkg -i planetdan-linux-x64.deb
```

**AppImage:**
```bash
chmod +x planetdan-linux-x64.AppImage
./planetdan-linux-x64.AppImage
```

### Windows

Download the `.msi` installer from [Releases](https://github.com/planetsamson/desktop-releases/releases) and run it.

## Verify Downloads

Each release includes a `SHA256SUMS` file. To verify your download:

```bash
sha256sum -c SHA256SUMS --ignore-missing
```
