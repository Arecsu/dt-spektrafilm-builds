# Darktable Spektrafilm — Builds

 Automated builds from the [spektrafilm-draft](https://github.com/Arecsu/darktable/tree/spektrafilm-draft) branch.

**Latest version:** 25f0ca0

## Required: Film & Print Data Pack

Download the [spektrafilm-data-pack.zip](https://github.com/Arecsu/dt-spektrafilm-builds/raw/main/spektrafilm-data-pack.zip) and extract to your darktable config dir:

| Platform | Extract to |
|----------|-----------|
| Linux | `~/.config/darktable/spektrafilm/` |
| macOS | `~/Library/Application Support/darktable/spektrafilm/` |
| Windows | `%APPDATA%\darktable\spektrafilm\` |

After extracting you should see `profiles/` + `pack.json` + `spectra_lut.f32` inside.

## Latest Builds

| Platform | Architecture | Download |
|----------|-------------|----------|
| Linux AppImage | x86_64 | [Darktable-25f0ca0401-x86_64.AppImage](https://github.com/Arecsu/dt-spektrafilm-builds/releases/download/spektrafilm-builds/Darktable-25f0ca0401-x86_64.AppImage) |
| Linux AppImage | ARM64 | [Darktable-25f0ca0401-aarch64.AppImage](https://github.com/Arecsu/dt-spektrafilm-builds/releases/download/spektrafilm-builds/Darktable-25f0ca0401-aarch64.AppImage) |
| Windows | x86_64 | [darktable-25f0ca0401-win64.exe](https://github.com/Arecsu/dt-spektrafilm-builds/releases/download/spektrafilm-builds/darktable-25f0ca0401-win64.exe) |
| macOS | ARM64 (Apple Silicon) | [darktable--arm64.dmg](https://github.com/Arecsu/dt-spektrafilm-builds/releases/download/spektrafilm-builds/darktable--arm64.dmg) |
| macOS | x86_64 (Intel) | [darktable--x86_64.dmg](https://github.com/Arecsu/dt-spektrafilm-builds/releases/download/spektrafilm-builds/darktable--x86_64.dmg) |

Come work together! Feedback, issues, anything is welcome at [discuss.pixls.us](https://discuss.pixls.us/t/spektrafilm-darktable-module-implementation-discussion/58744)

> **⚠️ HIGHLY EXPERIMENTAL** — back up your darktable data dir before testing: Linux `~/.config/darktable/`, macOS `~/Library/Application Support/darktable/`, Windows `%APPDATA%\darktable\`. Use `--library <path>` to keep your main setup safe.
