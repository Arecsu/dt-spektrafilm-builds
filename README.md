# Darktable Spektrafilm — Builds

Automated builds from the [spektrafilm-draft](https://github.com/Arecsu/darktable/tree/spektrafilm-draft) branch of Arecsu/darktable.

## Downloads

## Required: Film & Print Data Pack

The module needs film stock + print data to work. Download and extract to your darktable config dir:

[spektrafilm-data-pack.zip](https://github.com/Arecsu/dt-spektrafilm-builds/raw/main/spektrafilm-data-pack.zip)

| Platform | Extract to |
|----------|-----------|
| Linux | `~/.config/darktable/spektrafilm/` |
| macOS | `~/Library/Application Support/darktable/spektrafilm/` |
| Windows | `%APPDATA%\darktable\spektrafilm\` |

After extracting, you should see `profiles/` + `pack.json` + `spectra_lut.f32` inside that directory.

> This data pack rarely changes — only when new film stocks are added or the model is updated.

## Latest Builds

| Platform | Architecture | Download |
|----------|-------------|----------|
| Linux AppImage | x86_64 | _pending_ |
| Linux AppImage | ARM64 | _pending_ |
| Windows | x86_64 | _pending_ |
| macOS | ARM64 (Apple Silicon) | _pending_ |
| macOS | x86_64 (Intel) | _pending_ |

Come work together! Feedback, issues, anything is welcome at [discuss.pixls.us](https://discuss.pixls.us/t/spektrafilm-darktable-module-implementation-discussion/58744)

> **⚠️ HIGHLY EXPERIMENTAL — You WILL lose data.**
> This is pre-release development software built from an unstable branch. It may corrupt your darktable database, break your edits, or crash.
> **Always back up your darktable data directory before opening with this build:**
> - Linux: `~/.config/darktable/`
> - macOS: `~/Library/Application Support/darktable/`
> - Windows: `%APPDATA%\darktable\`
> 
> Use a separate library (`darktable --library <path>`) to keep your main setup safe.
> 
> **No support, no guarantees.** If it breaks, you get to keep both pieces.
