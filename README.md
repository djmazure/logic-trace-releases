# logic-trace

High-performance waveform viewer for digital logic engineers.

**Website**: [routertl.dev/logic-trace](https://routertl.dev/logic-trace)
**Documentation**: [routertl.dev/logic-trace/doc](https://routertl.dev/logic-trace/doc)

## Downloads

Check the [Releases](https://github.com/djmazure/logic-trace-releases/releases) page for the latest builds.

### Available artifacts

| Platform | Format | Contents |
|----------|--------|----------|
| Linux / WSL | AppImage | Self-contained, just `chmod +x` and run |
| Linux / WSL | tar.gz | `logic_gui` + `logic_cli` + assets |
| Windows | zip | `logic_cli.exe` (CLI only) |

### Quick start (Linux / WSL)

```bash
chmod +x logic-trace-*-x86_64.AppImage
./logic-trace-*-x86_64.AppImage myfile.vcd
```

### WSL users

Download the **Linux** AppImage (not the Windows zip). WSL runs Linux binaries natively.
Install GL libs first:

```bash
sudo apt install libopengl0 libgl1 libglx-mesa0
```

### Verify downloads

Each release includes a `SHA256SUMS.txt` file. To verify your download:

```bash
# Download SHA256SUMS.txt from the same release
sha256sum -c SHA256SUMS.txt
```

This confirms the files haven't been modified since they were built.

## Author

Daniel J. Mazure — [routertl.dev](https://routertl.dev)
