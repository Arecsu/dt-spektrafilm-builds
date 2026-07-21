# Darktable Spektrafilm — Builds

 Automated builds from the [spektrafilm-draft](https://github.com/Arecsu/darktable/tree/spektrafilm-draft) branch.

Come work together! Feedback, issues, anything is welcome at [discuss.pixls.us](https://discuss.pixls.us/t/spektrafilm-darktable-module-implementation-discussion/58744)

> **⚠️ HIGHLY EXPERIMENTAL** — back up your darktable data dir before testing: Linux `~/.config/darktable/`, macOS `~/Library/Application Support/darktable/`, Windows `%APPDATA%\darktable\`. Use `--library <path>` to keep your main setup safe.

**Latest version:** 20260721-128c2bb

## Latest Builds

| Platform | Architecture | Download |
|----------|-------------|----------|
| Linux AppImage | x86_64 | [darktable-spektrafilm-20260721-128c2bb-x86_64.AppImage](https://github.com/Arecsu/dt-spektrafilm-builds/releases/download/spektrafilm-builds/darktable-spektrafilm-20260721-128c2bb-x86_64.AppImage) |
| Linux AppImage | ARM64 | [darktable-spektrafilm-20260721-128c2bb-aarch64.AppImage](https://github.com/Arecsu/dt-spektrafilm-builds/releases/download/spektrafilm-builds/darktable-spektrafilm-20260721-128c2bb-aarch64.AppImage) |
| Windows | x86_64 | [darktable-spektrafilm-20260721-128c2bb-x86_64.exe](https://github.com/Arecsu/dt-spektrafilm-builds/releases/download/spektrafilm-builds/darktable-spektrafilm-20260721-128c2bb-x86_64.exe) |
| macOS | ARM64 (Apple Silicon) | [darktable-spektrafilm-20260721-128c2bb-arm64.dmg](https://github.com/Arecsu/dt-spektrafilm-builds/releases/download/spektrafilm-builds/darktable-spektrafilm-20260721-128c2bb-arm64.dmg) |
| macOS | x86_64 (Intel) | [darktable-spektrafilm-20260721-128c2bb-x86_64.dmg](https://github.com/Arecsu/dt-spektrafilm-builds/releases/download/spektrafilm-builds/darktable-spektrafilm-20260721-128c2bb-x86_64.dmg) |

## Recent Commits

| Date | Commit | Author | Message |
|------|--------|--------|---------|
| 2026-07-21 | [128c2bb](https://github.com/Arecsu/darktable/commit/128c2bb) | piratenpanda | add development section with push pull and gamma settings |
| 2026-07-20 | [505a5b1](https://github.com/Arecsu/darktable/commit/505a5b1) | piratenpanda | fix comment |
| 2026-07-20 | [0e7b7d2](https://github.com/Arecsu/darktable/commit/0e7b7d2) | piratenpanda | fix grain changing exposure and add picker to pre compression boost |
| 2026-07-19 | [44cd6a2](https://github.com/Arecsu/darktable/commit/44cd6a2) | Arecsu | spektrafilm: fix fireflies in grain recovery USM |

## Required: Film & Print Data Pack

Download the [spektrafilm-data-pack.zip](https://github.com/Arecsu/dt-spektrafilm-builds/raw/main/spektrafilm-data-pack.zip) and extract to your darktable config dir:

| Platform | Extract to |
|----------|-----------|
| Linux | `~/.config/darktable/spektrafilm/` |
| macOS | `~/Library/Application Support/darktable/spektrafilm/` |
| Windows | `%APPDATA%\darktable\spektrafilm\` |

After extracting you should see `profiles/` + `pack.json` + `spectra_lut.f32` inside.
