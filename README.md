Automatic weekly build of [angle][] OpenGL ES implementation for Windows (x64 and arm64) and macOS (x64 and arm64).

Download binary builds as zip archives from [latest release][] page.

## Building Locally

### Windows
Run `build.cmd` batch file, make sure you have installed all necessary dependencies (see the beginning of file).

### macOS
Run `build.sh` shell script:
```bash
./build.sh [x64|arm64]
```

If no architecture is specified, it will be auto-detected based on your system.

[angle]: http://angleproject.org/
[latest release]: https://github.com/mmozeiko/build-angle/releases/latest
