# logic-trace releases

High-performance waveform viewer for digital logic analyzers.

## Downloads

Check the [Releases](https://github.com/djmazure/logic-trace-releases/releases) page for the latest builds.

### Available artifacts

| Platform | Contents |
|----------|----------|
| Linux x86_64 (tarball) | `logic_gui` + `logic_cli` + assets |
| Linux x86_64 (AppImage) | Self-contained, just `chmod +x` and run |
| Windows x86_64 (zip) | `logic_cli.exe` (CLI only) |

### Quick start (Linux)

```bash
chmod +x logic-trace-*-x86_64.AppImage
./logic-trace-*-x86_64.AppImage myfile.vcd
```

### WSL users

Download the **Linux** AppImage (not the Windows zip). WSL runs Linux binaries natively.
If you don't have WSLg set up, the binary will tell you what to do.
